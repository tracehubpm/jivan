**JIVAN** (stands for [Java](https://en.wikipedia.org/wiki/Java_(programming_language))
and [Ivan](https://en.wikipedia.org/wiki/Ivan))
is an experimental [static analyzer](https://en.wikipedia.org/wiki/Static_program_analysis)
for Java programs, powered by [LLM](https://en.wikipedia.org/wiki/Large_language_model)
and [ML](https://en.wikipedia.org/wiki/Machine_learning) techniques.

**Motivation**. Machine Learning and Large Language Model techniques offer
promising results in the area of code understanding. In some cases it can
outperform traditional tools like [SpotBugs], [PMD], and [Infer]. Moreover,
our analyzer trys to analyze the social aspect of coding (code authorship
in Git, team responses, etc.). Besides that, here are no publicly available
and easy to use static analyzers for Java, which would be based on some LLM/ML
models.

## How to use?

TBD..

## How to contribute?

Fork repository, make changes, send us a [pull request](https://www.yegor256.com/2014/04/15/github-guidelines.html).
We will review your changes and apply them to the `master` branch shortly,
provided they don't violate our quality standards. To avoid frustration,
before sending us your pull request please run full Maven build:

```bash
mvn clean install
```

You will need [Maven 3.3+], [Java 8+], and [Python 3.11+] installed

[SpotBugs]: https://spotbugs.github.io
[PMD]: https://pmd.github.io
[Infer]: https://fbinfer.com
[Maven 3.3+]: https://maven.apache.org
[Java 8+]: https://openjdk.org/install
[Python 3.11+]: https://www.python.org/downloads/release/python-3110
