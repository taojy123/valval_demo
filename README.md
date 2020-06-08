# valval_demo

demo for https://github.com/the-benchmarker/web-frameworks/issues/2892


## Run Server
```
docker run -it --rm -p 8012:8012 taojy123/vlang:v0.1.24 bash

git clone https://github.com/taojy123/valval
ln -s $(pwd)/valval ~/.vmodules/valval 

git clone https://github.com/taojy123/valval_demo
cd valval_demo
v run main.v
```


## Try Requests
```
curl -v http://127.0.0.1:8012/
curl -v http://127.0.0.1:8012/user?id=123
curl -v -X post http://127.0.0.1:8012/user
```

