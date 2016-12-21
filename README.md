# vue-avatar

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

```html
  default avatar:
  <avatar></avatar>
  use img-url avatar:
  <avatar img-url="http://mhfm3.tel.cdndm5.com/32/31393/20160811232318_130x174_14.jpg"></avatar>

  use outer-class avatar:
  <avatar outer-class="oc"
  img-url="http://mhfm3.tel.cdndm5.com/32/31393/20160811232318_130x174_14.jpg"></avatar>

  use img-class avatar:
  <avatar img-class="ic"></avatar>
```

## Api
### Properties
| Name                 | Type      | Default      | Description                                                        |
|----------------------|-----------|--------------|--------------------------------------------------------------------|
| img-url            | `String`  | `"a default img src"` |  the img url   |
| outer-class   | `String` | `''`       | the extra outer container class name |
| img-class   | `String` | `''`       | the extra img class name |

| ==================== | ========= | ============ | =================== |

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
