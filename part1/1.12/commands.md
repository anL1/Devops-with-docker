Frontend commands:

```
docker build -t frontend .
docker run -it --rm -p 5000:5000 frontend
```

Backend commands:

```
docker build -t backend .
docker run -it --rm -p 8000:8000 -v $(pwd)/logs.txt:/mydir/logs.txt backend
```

