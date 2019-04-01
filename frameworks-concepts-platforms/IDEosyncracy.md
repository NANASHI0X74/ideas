# ~~Intellij mixed with Atom, Eclipse and LLVM~~ IDEosyncracy(working title)

## what it's about:
- a minimalistic IDE with a great UX (comparable to IntelliJ but more minimalistic)
- which is open-source and hackable/ ultra-flexible (comparable to Atom/vim)
- It provides an efficient way to define templates for
  - Code Completion
  - and Refactoring Tasks (e.g. pull up members/ reshape if and switch statements/expressions)
  - more complex Refactoring tasks like interface-ify functions or implement patterns like Visitor or Observer
- it should have its own Package Manager with CLI
  - and virtualenvs comparable to python.
- it should also have a CLI to access any functionality the IDE provides or an API in, for example, python so that you can write scripts to automate tasks and use the IDE from a REPL shell

## nice-to-have
- provide functionality for porting code between different languages
- an LLVM-inspired System of Front- and Backends for different languages
  - which could help with templating,
  - porting Code
  - and figuring out which decisions a programmer has to make when porting code to languages with e.g. different paradigms and other Features
  - smart suggestions for Code which could be
    - made more concise,
    - maintainable/readable,
    - or which could be optimized
  - depending on the languages
- Machine Learning to learn what functionality  is the most useful depending on the context
