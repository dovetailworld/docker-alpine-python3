Python 3.12 Docker image
========================

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[Python 3.x](https://www.python.org/).

This image is only 67MB on disk.


Usage Example
-------------

```bash
$ docker run --rm dovetailworld/alpine-python3 python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!  Or use it interactivelly:

```bash
$ docker run -it --rm dovetailworld/alpine-python3 python3
```

NOTE: `pip`/`pip3` is also available in this image.
