# bcnode-hybrid with optimized primitives.es6 made for version 0.8.1 optimization

ref: https://github.com/lgray/bcnode-unpacked/compare/0.7.7...optimizations_077

tg community ref: https://t.me/blockcollideradvanced/39436

1. git clone it or download archive from my repository, unpack, 
enter dir from the command prompt and run the command shown in step 2, 3

2. Build the new image using:

```
docker build -t "blockcollider/bcnode:0.8.1-lp" .
```

3. Afterwards, run it as usual:

```
docker run --name bcnode -p 3000:3000 blockcollider/bcnode:0.8.1-lp start --ws --rovers --ui --node --miner-key <YOUR-KEY>
```
