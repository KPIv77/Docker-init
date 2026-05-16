# Docker Start
<pr>

## docker
```
docker build -t my-jupyter .
```

## docker run
```
docker run -p 8888:8888 \
  -v $(pwd)/Notebooks:/app/Notebooks \
  my-jupyter
```

