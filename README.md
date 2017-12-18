# combinators.github.io ![build status](https://travis-ci.org/combinators/combinators.github.io.svg?branch=source)
## Documentation of the Combinatory Logic Synthesizer (CL)S Framework

This repository houses the official documentation for the Combinatory Logic Synthesizer (CL)S framework.

The documentation is hosted at [combinators.github.io](https://combinators.github.io/).

## Improving the documentation

Clone this repository, edit the [markdown files](src) and test the result in your local browser using
```scala
sbt runMain pamflet.Pamflet src
```

Visit the [Pamflet website](http://www.foundweekends.org/pamflet/) for editing documentation.

When done, open a pull request against branch `source` including your markdown files.

**Do not try to push the generated documentation!**

Travis will automatically build and update the website, once your request has been accepted.

The documentation source is kept in branch `source` and the compiled output in `master`.

## Help and Contributions

Join [combinators/cls-scala](https://gitter.im/combinators/cls-scala) on Gitter.

### Main Authors

- Jan Bessai
- Boris Düdder
- Geroge T. Heineman

### Contributers

-
##### Your name here?
Just the usual: open pull requests and or issues.
Feel free to add yourself to the list in this file, if you contributed something.
