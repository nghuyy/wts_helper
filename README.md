# wts_helper
```
git submodule add https://github.com/nghuyy/wts_helper.git
```

```
    implementation fileTree(include: [ '*.aar'], dir: '../wts_helper')
    implementation ('com.github.nkzawa:socket.io-client:0.6.0',{
        exclude group:"org.json", module:"json"
    })
    
```
