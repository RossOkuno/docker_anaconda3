# docker_anaconda3
Build
```
docker-compose build
```

Activate
```
docker-compose up -d
```

Deactivate
```
docker-compose down
```

Login to docker container
```
docker-compose exec dev bash
```
You can install libaries with codna
```
conda install -c conda-forge fbprophet
```
Trash container image
'''
docker-compose down --rmi all --volumes
'''
