# vue-splash
The source used for my blogpost on creating a splash screen in vue https://visualbean.medium.com/simple-vue-splash-screen-f734b096d919

The basic idea is to simply add whichever splash/loading screen you want inside your hook point (`<div id="app"></div>`),
Once your app has completed loading whatever it needs (in `beforeMount` and `init`).

In this project we simply mimic loading time by adding 

``` javascript
beforeMount() {
  this.delay(5000);
},
```
to the hello world component.


## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Lints and fixes files
```
yarn run lint
```
