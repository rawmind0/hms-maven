[![](https://images.microbadger.com/badges/image/rawmind/hms-maven.svg)](https://microbadger.com/images/rawmind/hms-maven "Get your own image badge on microbadger.com")

hms-maven
=============

This image is the [maven][maven] base. It comes from [hms-jdk8][hms-jdk8].

## Build

```
docker build -t rawmind/hms-maven:<version> .
```

## Versions

- `3.3.9` [(Dockerfile)](https://github.com/rawmind0/hms-maven/blob/3.3.9/Dockerfile)


## Usage

To use this image include `FROM rawmind/hms-maven` at the top of your `Dockerfile`. You could add the entrypoint to compile, test, release.... your app.

[hms-jdk8]: https://github.com/rawmind0/hms-jdk8/
[maven]: https://maven.apache.org