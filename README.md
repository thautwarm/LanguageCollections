# programming-languages-implemented-by-myself

And most of them are designed by myself.


- hmf: [https://github.com/RemuLang/hmf](https://github.com/RemuLang/hmf)

    Implementation of HMF type system based on [type-systems/first-class-polymorphisms](https://github.com/tomprimozic/type-systems/tree/master/first_class_polymorphism), in Python. As an investigation to work out the type inference problems of Proud programming languages.


- proud: [https://github.com/RemuLang/proud](https://github.com/RemuLang/proud)

    This is based on [Damas-Milner type system](https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system),but the development is current stuck due to the difficulty of inferring [higher rank types](https://wiki.haskell.org/Rank-N_types).

    Proud is a very practical static typed programming language,
    whose syntax is close to ML family/Haskell, and the type system is very strong, with following extraordinary contents:

    - [Row polymorphisms](https://en.wikipedia.org/wiki/Row_polymorphism)/extensible records. Compiling to tuples,which can remove many use cases of hashmaps, to speed up program execution, and make better static guarantee for dictionaries.

    - Higher rank types[WIP]. Necessary to implement monads as powerful as that in Haskell.
    
    - Module as records. Eliminating the special module constructs in traditional functional programming languages,
    bringing about better consistency.

    - [Type holes, and scoped type variables](https://pdfs.semanticscholar.org/e458/ad8bd20ca978e7d9b0915f9404df2f777b0c.pdf). A rudimentary way to achieve programmable type inference, e.g., check some type implicitly inferred is expected.

    - Custom operators, with custom precedences, and custom associativity




- urgent: [https://github.com/RemuLang/urgent-lang](https://github.com/RemuLang/urgent-lang)

    Practical programming language on Python platform, targeting Python bytecode instructions. It brings the most advanced language features and functional programming constructs to Python world. It has following stable features:
    - [Tail call optimizations](https://en.wikipedia.org/wiki/Tail_call)
    - [Auto currying](https://en.wikipedia.org/wiki/Currying)
    - [Variants/algebraic data types](https://en.wikipedia.org/wiki/Algebraic_data_type)
    - Very rich [pattern matching](https://en.wikipedia.org/wiki/Pattern_matching#Tree_patterns)(including [view patterns](http://dlicata.web.wesleyan.edu/pubs/lpj07views/lpj07views-anglohaskell.pdf), or patterns, and patterns, etc.). [This documentation of F#](https://docs.microsoft.com/en-us/dotnet/fsharp/language-reference/pattern-matching) is a good guideline to pattern matching.
    - [Lexical scopes with let/let-and/let-rec-and bindings](https://en.wikipedia.org/wiki/Let_expression).
    - [Locally opening module(zero-cost)](https://caml.inria.fr/pub/docs/manual-ocaml/moduleexamples.html)
    - Custom operators, with custom precedences, and custom associativity
    - Python FFI
    - Compiling to standalone .pyc file.

- muridesu: [https://github.com/LanguageAsGarbage/muridesu-lang](https://github.com/LanguageAsGarbage/muridesu-lang)
    
    A very mature programming language based on CPython AST, implemented in 3 hours and a half, and the motivation for this project is to teach some programmers never underestimate professional compiler researchers and academic world, and also a mild argument against the so-called "民科".

- Sijuiacion: [https://github.com/RemuLang/sijuiacion-lang](https://github.com/RemuLang/sijuiacion-lang)

    Actual indirect jumps(Label As Value) and switch cases implemented in CPython VM, via taking advantage of
    the CPython's `END_FINALLY` instruction.

- ML-To-Scheme. [https://github.com/thautwarm/ml-to-scheme](https://github.com/thautwarm/ml-to-scheme)

    A simple dialect of ML language, which is compiled to Racket.
    In this way, writing racket becomes quite simple,
    with good readability for people who're used to infix notations and not used to deeply nested parentheses.

- JML.jl: [https://github.com/thautwarm/JML.jl](https://github.com/thautwarm/JML.jl)

    A ML dialect implemented in Julia. REPL only. Just a demo for showing [MLStyle.jl](https://github.com/thautwarm/MLStyle.jl)'s capabilities in Julia User Meetup Beijing 2019.

- YAPyPy. [https://github.com/Xython/YAPyPy](https://github.com/Xython/YAPyPy)

    A Python implemented in pure CPython, which is extremely extensible in pure Python level.
    It can be run with CPython 3.6 and CPython 3.7(and accepts all Python3 code!), tested on existing codebase of Python community(Scikit-Learn, NumPy, SciPy, etc.),
    and supports new features like PEP572.

    P.S: It's implemented by a group of very kind people(including me, haha), others are all the friends I'm so proud of!

- Reley[static typing not implemented]. [https://github.com/thautwarm/reley](https://github.com/thautwarm/reley)

    Statically compiled language based on CPython to deal with complex works.
    For people to write fast, safe and concise codes on Python VM.

- RUSH. [https://github.com/thautwarm/rtpy](https://github.com/thautwarm/rtpy)

    A terminal implemented by my CLI library(`rtpy`) which is scalable, intuitive, and effective.

- RBNF. [https://github.com/thautwarm/RBNF](https://github.com/thautwarm/RBNF)

    There is a DSL for `rbnf`.

- Rem. [https://github.com/thautwarm/Rem](https://github.com/thautwarm/Rem)

    Dynamic Language with all modern syntax sugars.

- Flowpython. [https://github.com/thautwarm/flowpython](https://github.com/thautwarm/flowpython)

    Python with tasty features and syntax sugars.

- RMalt. [https://github.com/thautwarm/rmalt](https://github.com/thautwarm/rmalt)

    the Malt programming language.

- dbg-lang. https://github.com/Xython/auto-orm

    Automatically build ORM(object-relational mapping) components from a concise DSL.

- \* Squirrel(not exactly a language) [https://github.com/thautwarm/SquirrelLanguage](https://github.com/thautwarm/SquirrelLanguage)


    Transpiler to CPP14.















