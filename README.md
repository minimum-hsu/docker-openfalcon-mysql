# open-falcon-mysql

## Build

Enter the following command in the repo directory.

```
$sudo docker build --force-rm=true -t open-falcon-mysql .
```

## Run

```
$sudo docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=password --name mysql open-falcon-mysql
```

You can use your password to replace **password** in *MYSQL_ROOT_PASSWORD*.
