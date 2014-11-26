gost
====

Simple static file server. Current version is 0.1.1.
Thisi is a fork of [gost](https://github.com/golang-id/gost)

## Install

```bash
$ go install github.com/brunetto/gost
```

## Usage

Running static file server on `http://localhost:8080` with current directory as document root:

```bash
$ gost
```

You can specify optional `port`, `path` (to be served as the document root), `ip` and `url`:

```bash
$ gost -port=12345 -path="/home/gedex/my_static_web"
```

See the help:

```bash
$ gost --help
Usage of gost:
  -path="./": Path served as document root.
  -port=8080: Port to listen
```

## Credits

* [gost](https://github.com/golang-id/gost)
* [Serving Static Files with HTTP](https://code.google.com/p/go-wiki/wiki/HttpStaticFiles)
* [Node.JS static file web server](https://gist.github.com/rpflorence/701407)

## License

See [LICENSE](./LICENSE) file.
