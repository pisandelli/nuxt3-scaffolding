# nuxt3-scaffolding

This is a template for fast starting new Nuxt projects. It comes with a bunch of plugins pre-installed and some nice configurations.  
Check this readme for more information about how to use it. Feel free to open an issue and ask for help or give your thoughts, I'll be very glad.

## Included with this template

* [Pug Template Engine](https://pugjs.org)
* [Stylus Pre-processor](https://stylus-lang.com/)
* [CSS Modules Support](https://github.com/css-modules/css-modules)
* [Layout Compositions](https://every-layout.dev/rudiments/composition/)
* [I18n](https://i18n.nuxtjs.org)
* [Google Fonts API](https://google-fonts.nuxtjs.org)
* [HTML Validation](https://html-validator.nuxtjs.org)
* [Robots txt](https://github.com/nuxt-community/robots-module)
* [Responsive Images Support](https://v1.image.nuxtjs.org)
* [Ready to use Composition Utilities](https://vueuse.org/)
* [Dark Mode Support](https://color-mode.nuxtjs.org/)
* [PurgeCSS Support](https://purgecss.com/guides/nuxt.html)
* [Google Web Vitals Support](https://github.com/nuxt-modules/web-vitals)
* [Icons Libs Support](https://github.com/nuxt-modules/icon)
* [Easy Transitions](https://github.com/MorevM/vue-transitions)
* [Pinia](https://pinia.vuejs.org/)
* [Vitest](https://vitest.dev/)

## Highlights

* Typescript by default
* Predefined Mixins
* Ready to use Utility Classes
* Custom Error page
* Prettier Code Formatting

## A note regarding PUG
Pug is a template engine largely used by many developers and projects around the world. It aims to give you extra tools to write HTML faster. Or as they pointed in their Github page:  

"_Pug is a high-performance template engine heavily influenced by Haml and implemented with JavaScript for Node.js and browsers._"

Pug, like HAML, uses a _pythonic_ way to write code (i.e. indentation-based). This could be odd for most people that is not used to indentation-based languages, but soon you'll realize that you can code much faster and in a cleaner way using this fantastic tool. Pug is not mandatory for this template thought, but we encourage you to give it a try.  

## A note regarding Stylus
Stylus is an expressive, robust, feature-rich CSS language built for nodejs. It uses the same _pythonic_ syntax as Pug and SASS. We decided to use stylus due it's versatility and easy to use. It has some nice features like [JSON parser](https://stylus-lang.com/docs/bifs.html#external-file-functions), useful to create themes based on design tokens (take a look [in this study for using Json for creating CSS using stylus](](https://github.com/pisandelli/pebble)) or creating configuration files from an external API, and [file globbing](https://stylus-lang.com/docs/import.html#file-globbing) keeping `@imports` and `@required` calls very clean and neat.  
But don't be scared by Stylus _pythonic_ way of writing code. As we mentioned before, Stylus is very versatile, so [you can choose when to use brackets, semi-colon, etc](https://stylus-lang.com/docs/css-style.html#css-style-syntax) without any extra configuration. We recommend though to use the pythonic 'classic' syntax, but this decision is up to you and your team.  
You can uninstall Stylus and use whatever CSS pre-processor you want. Just follow the instructions on how to install and configure your preferable pre-processor and start you project.

## CSS Modules  
This template is ready for [CSS Modules](https://github.com/css-modules/css-modules). You can use it right away. You have a pretty example on how to use CSS Modules in the folder `layouts/compositions`. Please check the code for the compositions and see how we use CSS Modules to scope styles.  
Please take som minutes to see [this video by Erik Hanchett about why CSS modules on Vue are so great](https://youtu.be/9WEV51IGSek).
## Exploring directories

Most directories in this template follow the same structure proposed by Nuxt.  
I believe you could be interested in [Nuxt's Docs](https://nuxt.com/)

### Components
 Here you can add you components. Feel free to use the best approach for you and your workflow. In this template we add a _namespace_ example structure.  
 ```
├── components
│   ├── ns
│   │   └── Example.vue
│   └── MyButton.vue
```

You can call your component as this example bellow.

```html
<template>
  <ns-example />
  <my-button />
</template>
```

**NOTE**  
You don't need to explicitly import any component. Nuxt will do this for you automatically. Please check the docs for more info about [nuxt auto-imports](https://nuxt.com/docs/guide/concepts/auto-imports).
## What's planned for the future?

* Improve Documentation
* Add _prefers-color-scheme media_ in compositions when necessary
* Add component factory for compositions
* Create a Dark theme
* Anything that worth in the _Issues_ section
