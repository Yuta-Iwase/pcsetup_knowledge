# my-mkdocs

## description
This repository is the template for creating document using [mkdocs-material](https://squidfunk.github.io/mkdocs-material/).

## usage

### requirements
* [docker](https://docs.docker.com/get-docker/)

### setup
```sh
docker pull squidfunk/mkdocs-material:6.1.4
```

### run working environment
1. run docker-compose
   ```sh
   docker-compose up
   ```
2. go http://127.0.0.1:8000
3. change files in `work/docs` (ex. `work/docs/index.md`)
4. make sure the page is updated

### build
1. run docker-compose for build  
   win:
   ```sh
   build_docs.bat
   ```
   [Unverified] MacOS, Linux:
   ```sh
   sh build_docs.sh
   ```
2. files will be created in `_site`