Erlang Projects Intro
=====================

Introduce Good Erlang Projects 


BossDB
==
 A sharded, caching, pooling, evented ORM for Erlang

Supported databases


* Mnesia
* MongoDB
* MySQL
* PostgreSQL
* Riak (experimental)
* Tokyo Tyrant

Home: [https://github.com/evanmiller/boss_db](https://github.com/evanmiller/boss_db)


ErlyDTL
=======

ErlyDTL compiles Django Template Language to Erlang bytecode.

Home: [https://github.com/evanmiller/erlydtl](https://github.com/evanmiller/erlydtl)

Aleppo
===

  Alternative Erlang Pre-Processor

Aleppo is an alternative to `epp(3erl)`, and is mainly intended for Erlang compiler hackers. The problem with EPP is that it only operates on Erlang source files. Aleppo will operate directly on tokens returned by erl_scan.

    erl_scan -> *aleppo* -> erl_parse -> compile

Home: [https://github.com/evanmiller/aleppo](https://github.com/evanmiller/aleppo)


Jerome
======

Jerome is designed to read and write many rich-text formats, with support for bold, italic, lists, tables, and hyperlinks. At present the number of supported formats is small.

Home: [https://github.com/evanmiller/jerome](https://github.com/evanmiller/jerome)




##Translib
Translib is for Transformer Library. Translib is an Erlang application that contains some parse transformers to extend or modify the semantic of Erlang.

For the moment, Translib contains 6 modules:

- gen_trans: a behaviour module for implementing a parse transformer of Erlang code.
- lambda_expr: a transformer that simplifies the partial application and the composistion of functions in Erlang.
- recfun: a transformer that makes possible to easily write recursive anonymous function.
- clone_module: a transformer that builds modules by cloning the content of another one.
-  multiparser: a "meta" transformer that can perform several parse_transformations.
-  transhell: a "clone" of the Erlang shell that transforms expressions before evaluation calling a multiparser transformer.

Home: [https://code.google.com/p/translib/](https://code.google.com/p/translib/)



##Refactoring Erlang Programs
IntroductionThe goal of this project is to develop a static source code analyser and refactoring for the Erlang functional programming language.
 
Home: [http://plc.inf.elte.hu/erlang/](http://plc.inf.elte.hu/erlang/)





##eper##
Erlang performance related tools.

includes

- sherk (profiler, similar to MacOS shark)
- gperf (real-time graphical CPU load and memory usage monitor)
- dtop (displays real-time info about processes, a la unix top)
- redbug (simple and safe interface to tracing the functionality)

Home: [https://code.google.com/p/eper/](https://code.google.com/p/eper/)



## Erb ##


Erlang/OTP IRC Bot Framework

Home: [https://github.com/wrboyce/erb](https://github.com/wrboyce/erb "Erb")


##Cacherl
Erlang version of memcached with data persistence.

> Cacherl is an Erlang port of famous Memcached trying to take advantage of both Erlang and Memcached. It follows the simple interface of memcached with additional data persistence. All memcached clients (C/PHP/Perl/...) can access Cacherl without any code modification. Moreover, the distributing of cached data is ensured by Erlang instead of memcached client hashing, so we don't need to worry about data invalidation when adding more servers.

svn checkout http://cacherl.googlecode.com/svn/trunk/ cacherl-read-only


Gencron 
======
Periodic command execution in Erlang

gencron provides the gen_cron server for periodic command execution. gen_cron is a very thin extension over gen_server, but it was a common pattern in our code worth abstracting (non-overlapping periodic execution with a force-now feature); perhaps you will find the same. Note this is a library for Erlang development, not a replacement of the OS utility cron. genexpire is an example using gencron. It periodically enforces a (per-node) size limit on Mnesia databases. Another Dukes of Erl release.



Home : [http://code.google.com/p/gencron](http://code.google.com/p/gencron) 
			
			
				

	
Empierl 
=====
 MMO strategy game engine

We are creating an open source engine for web based MMO strategy games such as Travian, with Erlang and other languages.

Home : [http://code.google.com/p/empierl ](http://code.google.com/p/empierl )




Erl-string-lambda
==================
 Impelmentation of String Lambda in Erlang

Implementation of String Lambda in Erlang based on Oliver Steele's Functional Javascript.


Website Link : http://code.google.com/p/erl-string-lambda 




