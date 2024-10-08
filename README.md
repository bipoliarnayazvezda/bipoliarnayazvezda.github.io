# AB

Normal build:

```
docker run --rm -it -e HUGO_DESTINATION=docs -v $(pwd):/src klakegg/hugo:0.68.0
```


Run server:

```
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.68.0 server
```