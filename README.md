# VueJs template for Atomic Design, Jest and Storybook
![Vue Atomic Design](https://miro.medium.com/max/4000/1*V5oi-JrH4RlEQuYdVrQXig.png)

Related projects:

* [Vue Cli Plugin Atomic Design](https://github.com/milad-alizadeh/vue-cli-plugin-atomic-design) - Vue Atomic Design is an opinionated Vue CLI 3 plugin for using Atomic Design methodology with Vue.js.

## Preview

https://atomic-design.herokuapp.com/

## How to install
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

## Storybook
Vue Atomic Design uses [Storybook](https://storybook.js.org/) as its design system tool. Originally created for React, Storybook is a tool for creating UI Components in isolation. The advantage of using Storybook is that we can create our style guide and our project at the very same time without maintaining both which is great for both small and large scale applications.
Once you install the plugin the storybook will be configured and you can use it by running:

```npm run serve:storybook```

or to generate a static style guide:

```npm run build:storybook```


### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```
