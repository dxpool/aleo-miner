<img src="https://www.dxpool.com/help/_nuxt/img/logo.0d86a52.svg" alt="goldshell" height="51" /><img src="https://assets-global.website-files.com/5e990b3bae81cf4a03433c58/5f347d008da2e477a3c61fca_Aleo-logo-white.png" alt="DxPool" height="51"/>

A GPU prover that does not rely the on CPU too much

### How to run
```
./dxa0 -h aleo.ss.dxpool.com -p 9090 -u account.worker
```

### We recommand you to run `dxa0` via [`pm2`](https://github.com/Unitech/pm2), which enables process relaunch when crashed
```
pm2 start -n ap ./dxa0 -- -h aleo.ss.dxpool.com -p 9090 -u account.worker
```

**To check log**
```
pm2 logs ap
```

**To stop**
```
pm2 stop ap
```