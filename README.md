# WebPackUse
学习一下
#使用 npm 全局安装 vue-cli ：
npm i -g @vue/cli
# OR
yarn global add @vue/cli

#创建项目
vue create my-project
#初始完之后，进入到项目根目录：
cd my-project
#启动项目：
npm run serve
稍等一会儿，可以看到自动在浏览器中打开了
#安装postcss-import和postcss-url插件
$ npm install postcss-import和$ npm install postcss-url
#postcss-import相关配置点击这里。主要功有是解决@import引入路径问题。使用这个插件，可以让你很轻易的使用本地文件、node_modules或者web_modules的文件。这个插件配合postcss-url让你引入文件变得更轻松。
#postcss-url相关配置可以点击这里。该插件主要用来处理文件，比如图片文件、字体文件等引用路径的处理。在Vue项目中，vue-loader已具有类似的功能，只需要配置中将vue-loader配置进去。
#autoprefixer插件是用来自动处理浏览器前缀的一个插件。如果你配置了postcss-cssnext，其中就已具备了autoprefixer的功能。在配置的时候，未显示的配置相关参数的话，表示使用的是Browserslist指定的列表参数，你也可以像这样来指定last 2 versions 或者 > 5%。如此一来，你在编码时不再需要考虑任何浏览器前缀的问题，可以专心撸码。这也是PostCSS最常用的一个插件之一。
