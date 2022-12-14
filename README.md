# nuxt-app

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).


### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).


### personal notes
npm install -g create-nuxt-app

create-nuxt-app nombre-del-app

cd to folder

npm run dev


nuxt.js Pages, Routing & views

when we create a dynamic segment for a page (not index.vue which is hard coded)
we need to start with and underscore

$route is a Vue component that we can use

to redirect using nuxt use this
<nuxt-link to="/users"> </nuxt-link>

Validation property
"validate" can be used as an assert,
in the example below we're checking if 
data.params.id returns a number in order to continue
otherwise it does not pass the validation

export default {
        validate (data){
            console.log(data)
            return /[0-9]/.test(data.params.id)
        }
    }


if we want to have nested routes we can create
a .vue with the same name as the route 
folder users might have a users.vue as a wrapper

Layouts, Pages and Components

the layout is your main wrapping element on the page
the layout allows you to define a frame, both from a styling perspective as well as regarding some shared functionalitylike a shared header,
you can have multiple layout sso you can create multiple layoutsfor different parts of your page

the pages on the other hand can have nested pages but can allowsuse components these ordinary normal view components,
which in a nuxt project you would store in the components folder, these are normal vue components that are reusable






folders approach

SPA - single page application
SEO - search engine optimization