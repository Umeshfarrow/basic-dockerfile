# basic-dockerfile
basic-dockerfile for roadmap.sh
Project: https://github.com/Umeshfarrow/basic-dockerfile

Docker build the Project:
```sh
docker build -t name .
```

Run docker to print the default: "Hello, Captain!"
```sh
docker run -it --rm name
```

Run docker to print the your name: replace 'bob' with your name
```sh
docker run -it --rm -e NAME="Bob" name
```
