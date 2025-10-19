# iracelog-protobuf

Protobuf definitions for iRacelog

## Cheatsheet

Login in VS code

```shell
buf registry login --prompt
```

Push to a label

```shell
buf push . --label mpapenbr/issueXX
```

See also [the manual][check-breaking]

Check breaking changes against main version

```shell
buf breaking --against https://github.com/mpapenbr/iracelog-protobuf.git

```

Check breaking changes against local main version

```shell
buf breaking --against '.git#main'

```

---

[check-breaking]: https://buf.build/docs/breaking/overview#git
