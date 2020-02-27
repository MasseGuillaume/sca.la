# sca.la

This is an URL shortener for the Scala community.

## Register a URL

If you want to register an URL, create a directory structure and add a file with the following format and send a PR to this GitHub repository: [https://github.com/MasseGuillaume/sca.la/](https://github.com/MasseGuillaume/sca.la/)

```scala
---
title: Test
redirect_to: https://scala-lang.org
---
```

For example:

file           | url                                                            | redirect
---------------|----------------------------------------------------------------|---------------------------------------------------
test.md        | [https://sca.la/test](https://sca.la/test)                     | [https://scala-lang.org/](https://scala-lang.org/)
example/nested | [https://sca.la/example/nested](https://sca.la/example/nested) | [https://scala-lang.org/](https://scala-lang.org/)
