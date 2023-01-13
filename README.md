# Implementing YoMo Stream Function using Deno

Nowadays, JavaScript (or TypeScript) is one of the most popular programming
languages. It's easy to learn, yet still powerful, thus suitable for serverless
mode. YoMo has integrated the Deno runtime for developers to implement JS/TS
serverless functions.

## Install YoMo CLI 

See [YoMo CLI](https://github.com/yomorun/yomo/tree/master/cli/README.md)

### Binary (Recommended)

```bash
$ curl -fsSL https://get.yomo.run | sh

  ==> Resolved version latest to v1.10.0
  ==> Downloading asset for darwin amd64
  ==> Installing yomo to /usr/local/bin
  ==> Installation complete
```

### Or build from source

```bash
$ go install github.com/yomorun/yomo/cmd/yomo@latest
$ yomo version
YoMo CLI Version: v1.10.0
```

## Install Deno runtime

https://deno.land/#installation

## Start the JS/TS serverless function

```sh
yomo run app.ts
```
