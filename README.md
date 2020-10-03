# MkDocs practice

https://www.mkdocs.org/


## Demo
https://ryomazda.github.io/mkdocs_practice/  
or  
https://mkdocs.pigimaru.com/

Both must look the same. I just tried two different deployment ways.


## Development
### How did I start the project
```sh
pip install mkdocs
mkdocs --version
# mkdocs, version 1.1.2 from /path/to/python3.8/site-packages/mkdocs (Python3.8)
mkdocs new mkdocs_practice
```

### Dynamic Serving
```sh
mkdocs serve
```

### Deploying as github pages
```sh
mkdocs gh-deploy
```

### Building files and Deploying to AWS S3
```sh
mkdocs build
# & manually upload the site/ to the S3 bucket
```
