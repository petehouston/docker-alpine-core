# Docker Alpine Core

[![](https://imagelayers.io/badge/petehouston/docker-alpine-core:latest.svg)](https://imagelayers.io/?images=petehouston/docker-alpine-core:latest 'Get your own badge on imagelayers.io')

A really small Docker images with base tools that every developers need to work with.

This is a really small Docker image which based on Alpine Linux which compiles some basic core tools for developers to start with development.

**Base tools in the image:**

* bash. Yes, we always need a shell.
* coreutils (check [this page](http://www.gnu.org/software/coreutils/manual/coreutils.html) for all available tools in the package)
* curl
* wget
* grep
* sed

### How to use?

Well, I guess you know that already.

```
$ docker pull petehouston/docker-alpine-core
```

### Execution

**Via interactive mode**

```
$ docker run -it petehouston/docker-alpine-core /bin/bash
```

**Via Dockerfile**

```
FROM petehouston/docker-alpine-core
...
```

### Notes

Please share your words. Always welcome :)
