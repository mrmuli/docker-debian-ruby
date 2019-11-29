### Running Ruby-2.3.x on Debian 9.x

This image is a tiny workaround for the OpenSSL incompatibility in Debian (7.5 and above) [more details](https://github.com/rbenv/ruby-build/wiki#suggested-build-environment)

#### How to use:

```
docker pull docker pull josephmuli/debian-ruby:<tag-name>
```

or as a base image:

```
FROM josephmuli/debian-ruby:<tag-name>
...
```

Available tags can be found on the [Docker Hub](https://hub.docker.com/r/josephmuli/debian-ruby/tags) page 