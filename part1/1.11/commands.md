Commands used:

```
docker build -t volume_ex .
docker run -it --rm -p 8000:8000 -v $(pwd)/logs.txt:/mydir/logs.txt volume_ex
```
