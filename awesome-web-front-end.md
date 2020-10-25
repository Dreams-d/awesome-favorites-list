<div align="center">
  <h1>Awesome-Web-Front-End-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Web 前端基本技术 JavaScript、CSS、HTML 相关框架、库、工具等。</p>
</div>

<br />

（Recommend）推荐看看 W3C（World Wide Web Consortium，万维网联盟） 官方网站，:point_right: https://www.w3.org/

## 目录

*Resource navigation list.*

- [技术规范标准（Technical Specifications）](#技术规范标准)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [构建工具（Build Tools）](#构建工具)
- [HTML](#html)
  - [工具库（Library）](#html-工具库)
- [CSS](#css)
  - [工具库（Library）](#css-工具库)
  - [字体图标（Font Icon）](#字体图标)
- [JavaScript](#javascript)
  - [代码风格规范（Code Style Specifications）](#代码风格规范)
  - [工具库（Library）](#js-工具库)
- [UI 组件（UI Component）](#ui-组件)
  - [组件库（Component Library）](#组件库)
  - [独立组件（Independent Components）](#独立组件)
- [数据可视化（Data Visualization）](#数据可视化)
- [开发框架（Framework）](#开发框架)
- [更多（More）](#更多)
  - [CDN](#cdn)
  - [在线工具（Online Tools）](#在线工具) 
  - [文章（Article）](#文章)
  - [其它（Others）](#其它)

## 技术规范标准

*Official technical specifications.*

- [W3C](https://www.w3.org/) - 万维网联盟创建于 1994 年，是 Web 技术领域最具权威和影响力的国际中立性技术标准机构。
- [ECMA International](http://www.ecma-international.org/) - ECMA 国际是一家国际性会员制度的信息和电信标准组织，负责行业标准的制定，例如 ECMA Script。
- [ECMAScript Official Specification Standard](https://www.ecma-international.org/publications/standards/Ecma-262.htm) - ECMAScript 官方规范标准。
- [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [WebAssembly](https://webassembly.org/) - WebAssembly 官方网站，可在浏览器中运行 C/C++ 代码。
- [Chrome Blink status](https://www.chromestatus.com/) - Google Chrome 的 Blink 引擎功能特性的官方实现和标准化的开发状态查询列表。
- [Firefox status](https://platform-status.mozilla.org/) - Firefox 的 Web 平台功能的官方实现和标准化路线图查询列表。
- [Webkit](https://webkit.org/) - Webkit 浏览器引擎的官方网站，可查询其功能特性的实现和标准化状态。
- [JSON Specification](http://www.json.org/) - JSON 数据格式规范。
- [JSON Schema](http://json-schema.org/) - JSON 数据校验。
- [JSON5 Specification](https://spec.json5.org/) - JSON5 数据格式规范，是对 JSON 格式的扩展，支持注释等特性。
- [NDJSON Specification](http://ndjson.org/) - Newline Delimited JSON 数据格式规范。
- [TypeScript](http://www.typescriptlang.org/) - JavaScript 的超集，强类型语言。

[`Go Top ↑`](#awesome-web-front-end-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [MDN Developer Document](https://developer.mozilla.org/en-US/) - MDN Web Docs 网站提供开放网络（Open Web）技术有关的信息，包括用于网站和渐进式网络应用的 HTML、CSS 和 API，是提供给 Web 开发者最好的学习资料和技术文档，**可作为官方标准参阅学习**。
- [Can I use](https://caniuse.com/) - 可以查询特定 Web API（H5、CSS3）在各个浏览器平台的实现和标准化状态，**非官方网站**。
- [cssdb](https://cssdb.org/) - CSS 新特性列表。
- [CSS BEM](https://en.bem.info/) - CSS 类名的 BEM 命名风格和规则。
  - [BEM Cheat Sheet](https://9elements.com/bem-cheat-sheet/)
- [30 seconds](https://github.com/30-seconds) - 30 seconds 是一个系列，包含 JS、React.js、CSS 相关的编程技巧。
- [JS The Right Way](http://jstherightway.org/) - 一些 JavaScript 最佳实践。
- [SJSJ](https://github.com/HugoGiraudel/SJSJ) - JavaScript 术语介绍。
- [33 js concepts](https://github.com/leonardomso/33-js-concepts) - 包含了丰富的 JavaScript 相关的知识概念，学习资源。
- [印记中文](https://docschina.org/) - 包含了许多前端技术库的中文翻译文档。
- [jQuery API 中文文档](http://jquery.cuishifeng.cn/) - 一个国内开发者维护的 jQuery API 中文文档，非常实用。
- [favorite JavaScript utilities](https://1loc.dev/) - JavaScript 编程技巧，一行代码。
- [CSS Triggers](https://csstriggers.com/) - 一些改变会导致重绘、重布局的 CSS 属性。
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。

[`Go Top ↑`](#awesome-web-front-end-list)

## 构建工具

*Build tool, packaging tool used to develop web app, realize web engineering.*

### 打包工具/任务管理

*Packaging tools && Task management.*

- [webpack](https://webpack.js.org/) - 打包工具，适合开发 Web 应用。
  - [awesome-webpack](https://github.com/webpack-contrib/awesome-webpack) - Webpack 相关资源，**官方认证**。
  
- [Gulp](https://gulpjs.com/)
- [Grunt](https://gruntjs.com/)  
  
### 编译器

*Code compilation conversion.*

- [Babel](https://babeljs.io/) - 编译工具，可将 TypeScript、ES6/7/8 代码编译为 JavaScript（ES5） 代码。
- [Sass](https://sass-lang.com/) - CSS 预处理器，可提供类似编程语言的能力（变量、方法、作用域、嵌套）来编写 CSS。
- [PostCSS](https://postcss.org/) - CSS 后处理器，提供众多插件来实现还未被广泛实现和标准化的 CSS 功能特性，最终将其编译为目标平台支持的 CSS 代码。
  - [postcss-normalize](https://github.com/csstools/postcss-normalize)    

### PWA

*[Progressive web apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps).*

- [WorkBox](https://developers.google.com/web/tools/workbox/) - Google 专门为构建 PWA （Progressive Web App，渐进式 Web 应用）提供的一套开发工具，支持多个平台，并提供了方便的 webpack 插件。

### 其它

*Others.*

- [SystemJS](https://github.com/systemjs/systemjs) - 动态 ES Module 加载器。

[`Go Top ↑`](#awesome-web-front-end-list)

## HTML

> [W3C HTML 官方规范标准（W3C HTML Official Specification Standard）](https://www.w3.org/html/)

### HTML 工具库

*HTML tool library, dealing with compatibility issues, etc.*

- [html5shiv](https://github.com/aFarkas/html5shiv) - 在旧浏览器（IE9 以下）上提供对 HTML5 新标签（例如 footer、nav）的支持。

[`Go Top ↑`](#awesome-web-front-end-list)

## CSS

> [W3C CSS 官方规范标准（W3C CSS Official Specification Standard）](https://www.w3.org/Style/CSS/)

### CSS 工具库

*CSS tool library, dealing with compatibility issues, etc.*

- 兼容性（Polyfill）
  - [Respond](https://github.com/scottjehl/Respond) - 在旧浏览器（IE 6-8）上提供对 CSS3 Media Queries（媒体查询）的支持。
  - [selectivizr](http://selectivizr.com/) - 在旧浏览器（IE 6-8）上提供对 CSS3 新选择器的支持，注意 `style` 标签内样式不解析，动态生成的 DOM 也不解析。

- CSS 重置（CSS Reset）
  - [Normalize.css](http://necolas.github.io/normalize.css/) - 现代化的 Reset CSS 工具库，统一浏览器默认样式。
  - [sanitize.css](https://csstools.github.io/sanitize.css/)

- 动画（Animate）
  - [Animate.css](https://daneden.github.io/animate.css/) - 丰富的 CSS 动画工具库。
  - [Hover.css](http://ianlunn.github.io/Hover/) - 添加鼠标悬停动画效果。
  - [Imagehover.css](http://imagehover.io/) - 添加鼠标悬停动画效果。
  
- CSS In JS
  - [JSS](https://cssinjs.org) - 一种 CSS-in-JS 的解决方案。
  - [styled components](https://www.styled-components.com) - 一种 CSS-in-JS 的解决方案。

- 实用工具（Utils）
  - [Tailwind CSS](https://tailwindcss.com/) - 可定制设计的低级 CSS 框架，不提供组件样式，仅提供预设的工具类，来进行组合创建样式。
    - [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
    
### 字体图标

*Font icon, vector icon.*

- 字体（Font）
  
- 图标（Icon）
  - [Bootstrap Icons](https://icons.getbootstrap.com/) - SVG 图标库，**Bootstrap 官方发布**。
  - [Font Awesome](https://fontawesome.com/) - 提供了非常多的免费图标的库，使用率非常高。
  - [Material Icons](https://material.io/tools/icons/) - Material Design 风格的图标库，**Google 官方发布**。
  - [Material Design Icons](http://materialdesignicons.com/) - 遵循 Google Material Design 的图标库，**非官方**。
  - [material design palette](https://www.materialpalette.com/) - Google Material Design 设计工具，提供官方图标（Material Icons）下载，**非官方**。
  - [Fabric Icons](https://developer.microsoft.com/en-us/fabric#/styles/web/icons) - 微软官方提供的一套图标库，**Microsoft 官方发布**。
  - [IonIcons](https://ionicons.com) - ionic 框架团队制作的图标库。
  - [Octicons](https://octicons.github.com/) - GitHub 官方制作的图标库，**GitHub 官方发布**。
  - [Feather](https://feathericons.com/)
  - [Flat Icon](https://www.flaticon.com/)
  - [Icons8](https://icons8.com/) - 提供免费的图标设计工具。

[`Go Top ↑`](#awesome-web-front-end-list)

## JavaScript

> [ECMAScript 官方规范标准（ECMAScript Official Specification Standard）](https://www.ecma-international.org/publications/standards/Ecma-262.htm)

*（Recommend）推荐一个其它的收藏库，:point_right: https://github.com/sorrycc/awesome-javascript*

- [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [OpenJS Foundation](https://openjsf.org/) - 开源 JS 基金会，由 Node 基金会和 JS 基金会合并而成。

### 代码风格规范

*Code Style Specifications.*

- [JavaScript Standard Style](https://standardjs.com/) - 支持 JSX 等语法，社区维护。
- [Airbnb JavaScript Style Guide](https://airbnb.io/javascript/) - 支持 React 技术栈，**Airbnb 公司发布**。
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) - 仅支持原生 JavaScript，**Google 公司发布**。

### JS 工具库

*JavaScript tool libraries (browser-side), such as file manipulation, Canvas drawing, HTTP requests, etc.*

- 兼容性（Polyfill）
  - [core-js](https://github.com/zloirock/core-js) - 现代 JavaScript 标准库。
  - [Promise Polyfill](https://github.com/taylorhakes/promise-polyfill) - 为浏览器提供 Promise API 支持。
  - [webp-hero](https://github.com/chase-moskal/webp-hero) - 为浏览器提供 WebP 格式图片支持。
  - [unfetch](https://github.com/developit/unfetch) - 提供简单的 Fetch API 支持。

- 文档（Doc）
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。
  - [highlight.js](https://highlightjs.org/) - 页面代码高亮。
  
- 测试（Test）
  - [Mocha](https://mochajs.org/)
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  - [faker.js](https://github.com/marak/faker.js) - 生成大量随机测试数据，可用来开发过程中进行 API 调试。
  - [Chance](https://chancejs.com/) - 生成随机的测试数据。
  - [Perfume.js](https://zizzamia.github.io/perfume/) - 性能监控工具。
 
- 移动端调试（Mobile debugging）
  - [Eruda](https://eruda.liriliri.io/) - 移动端 Web 调试工具。
  - [vConsole](https://github.com/Tencent/vConsole) - 移动端 Web 调试工具，腾讯（Tencent）出品。
 
- 实用工具（Utils）
  - [Underscore](https://underscorejs.org/) - JavaScript 的工具函数库，提供了大量非常有用的工具函数。
  - [Lodash](https://lodash.com/) - JavaScript 的工具函数库，参考自 Underscore，功能更丰富。
  - [Ramda](https://ramdajs.com/) - JavaScript 的工具函数库，适用于函数式编程。
  - [RxJS](https://rxjs.dev/) - 响应式编程（Reactive Extensions）的 JavaScript 实现，对异步数据集合处理很方便。
  - [clsx](https://github.com/lukeed/clsx) - 非常轻量的 CSS 类名拼接工具。
  - [polished](https://polished.js.org/) - CSS 样式辅助工具。
  - [chroma.js](https://vis4.net/chromajs/) - 颜色字符串解析、计算工具，功能很强大。
  - [color](https://github.com/Qix-/color) - 颜色字符串解析、计算工具，更轻量。
  - [TinyColor](https://github.com/bgrins/TinyColor) - 颜色字符串解析、计算工具，更轻量一些。（:warning: 不再更新）
  - [one.color](https://github.com/One-com/one-color) - 颜色字符串解析、计算工具，支持 RGB, HSV, HSL, CMYK 等。
  - [Fuse.js](https://fusejs.io/) - 模糊搜索工具。
  - [uuid](https://github.com/uuidjs/uuid) - 生成随机唯一 id。
 
- 文档对象模型（DOM）
  - [jQuery](https://jquery.com/) - 前几年非常流行的 DOM 操作工具库，处理了兼容性的细节问题。
  - [Zepto.js](https://zeptojs.com/) - 兼容 jQuery API 的轻量级工具库，适合移动端使用。
  - [Lozad.js](https://github.com/ApoorvSaxena/lozad.js) - 轻量、高性能图片懒加载工具，使用了 [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)。
  - [clipboard.js](https://clipboardjs.com/) - 现代的粘贴板工具库。
  
- 事件（Event）
  - [Hammer.js](http://hammerjs.github.io/) - 支持移动端触摸事件，以及手势操作、多点触控。
  - [interact.js](https://interactjs.io/) - 同上。
  - [Dragula](https://bevacqua.github.io/dragula/) - 拖放事件处理，可用于列表项的拖放、顺序调整等。
  - [SortableJS](https://sortablejs.github.io/Sortable/) - 列表项拖放调整辅助库，支持 React.js、Vue.js 等。
  - [Mousetrap](https://github.com/ccampbell/mousetrap) - 处理键盘事件。
  - [Hotkeys](https://wangchujiang.com/hotkeys/) - 处理键盘事件。
  - [Hotkey](https://github.com/github/hotkey) - 处理键盘事件。
  - [Selecto.js](https://github.com/daybrush/selecto) - 拖动选择元素，支持鼠标和触摸事件。

- 日期时间（Date && Time）
  - [Moment.js](https://momentjs.com/) - 功能强大的日期、时间处理库。
  - [Luxon](https://moment.github.io/luxon/) - 现代化、api 友好的日期、时间处理库，Moment.js 团队开发。
  - [date-fns](https://date-fns.org/)
  - [Day.js](https://github.com/iamkun/dayjs) - 现代化、轻量级日期、时间处理库。
  - [ms](https://github.com/vercel/ms) - 毫秒格式化工具。

- 数据与缓存（Data && Cache）
  - [crypto-js](https://github.com/brix/crypto-js) - JavaScript 加密库。
  - [SJCL](http://bitwiseshiftleft.github.io/sjcl/) - JavaScript 加密库。
  - [localForage](https://github.com/localForage/localForage) - 离线存储，对 IndexedDB、WebSQL、localStorage 的封装。

- 科学计算（Compute - Math && High precision && Scientific Computing）
  - [math.js](https://mathjs.org/)
  - [stdlib](https://stdlib.io/)

- 绘图（Canvas && Draw）
  - [DOM to Image](https://github.com/tsayen/dom-to-image/) - 利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [html2canvas](https://html2canvas.hertzen.com) - 截屏，利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [Create.js](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Two.js](https://two.js.org/) - Web 二维绘图工具库，基于 Canvas、Svg、WebGL。
  - [Paper.js](http://paperjs.org/) - 矢量绘图工具。
  - [Fabric.js](http://fabricjs.com/) - 矢量绘图工具。
  - [Pencil.js](https://pencil.js.org/) - 2D 绘图库。

- 动画（Animate）
  - [Anime.js](https://animejs.com/) - 动画引擎，轻量的 JavaScript 动画工具库。
  - [Velocity.js](http://velocityjs.org/) - 动画引擎，为元素提供动画效果。
  - [mo.js](https://mojs.github.io/) - 丰富，强大的运动图形动画工具库。
  - [KUTE.js](https://thednp.github.io/kute.js/) - 高性能动画引擎。
  - [Popmotion](https://popmotion.io/) - 实用、灵活的 JavaScript 动画工具套件。
  - [tween.js](https://createjs.com/tweenjs) - 动画工具库。
  - [ScrollReveal](https://scrollrevealjs.org/) - 为滚动进入视区的元素提供动画效果。
  - [lax.js](https://github.com/alexfoxy/laxxx) - 简单、轻量的工具库，创建平滑的滚动动画。
  - [vivus.js](https://github.com/maxwellito/vivus) - 为 SVG 提供动画效果。
  - [SVG.js](https://svgjs.com/) - 轻量级 SVG 动画库。
  - [Typed.js](https://github.com/mattboldt/typed.js) - 为输入框输入提供动画效果。
  - [Rough Notation](https://roughnotation.com/) - 为元素提供注释效果和动画。

- 二维码（QR Code）
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成。
  - [Awesome-qr.js](https://www.bitcat.cc/webapp/awesome-qr/index.html) - 个性化二维码生成。（:warning: 不再更新）

- 文件（File）
  - utils
    - [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - Web 浏览器客户端文件保存 api 实现。
    - [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js) - Web 浏览器客户端异步保存文件 api 实现，解决了 FileSaver 的大小限制问题。
  - json5
    - [JSON5](https://json5.org/) - JSON5 格式数据解析、序列化。
  - zip
    - [JSZip](https://github.com/Stuk/jszip) - 创建/读写 zip 文件。
  - xlsx
    - [exceljs](https://github.com/exceljs/exceljs) - 读、写 xlsx、csv 文件。  
    - [xlsx](https://sheetjs.com/) - 读、写 xlsx、csv 文件（写功能部分特性不免费）。
  - csv
    - [Papa Parse](https://www.papaparse.com/)
  - docx
    - [docx](https://github.com/dolanmiu/docx) - 生成 docx 文档。
  - pdf
    - [PDF-LIB](https://pdf-lib.js.org/) - 解析和操作 PDF 文件。
    - [jsPDF](https://github.com/MrRio/jsPDF) - Web 客户端生成 PDF 文件。
  - image
    - [Pica](http://nodeca.github.io/pica/demo/) - 图片质量调整。
    - [merge-images](https://github.com/lukechilds/merge-images) - 图片拼接合并。
    - [blurify](https://github.com/JustClear/blurify) - 图片模糊化。
    - [Compressor.js](https://fengyuanchen.github.io/compressorjs/) - 图片压缩。
    - [Lena.js](https://fellipe.com/demos/lena-js/) - 图片滤镜。
  - audio
    - [howler.js](https://howlerjs.com/) - 强大的音频处理工具库，支持所有的编解码器，跨浏览器支持。
  - markdown
    - [Marked](https://marked.js.org/) - markdown 文件解析，转换成 HTML 文件。

- HTTP 请求（HTTP - Ajax / Promise / fetch）
  - [axios](https://github.com/axios/axios) - 基于 Promise 的 HTTP 客户端工具库。

- 套接字（Socket / TCP）
  - [socket.io-client](https://socket.io/) - 优秀的实时通信客户端框架。

[`Go Top ↑`](#awesome-web-front-end-list)

## UI 组件

*UI Component*

### 组件库

*UI component library, providing a set of components with consistent design style.*

#### Bootstrap

- [Bootstrap](https://getbootstrap.com/) - 最流行的 CSS UI 框架。
- [Bootswatch](https://bootswatch.com/) - 开源免费的 Bootstrap 主题集合，**非官方**。

#### Google Material Design

- [Material Design Lite](https://getmdl.io/) - 基于 Material Design 的轻量级 CSS UI 框架，**Google 官方发布**。（:warning: 不再更新）
- [Material Components Web](https://material.io/develop/) - 基于 Material Design 的 Web 组件库，**Google 官方实现**。
- [Materialize](https://materializecss.com/) - 最流行的实现了 Google Material Design 的 CSS UI 框架。

#### 其它（Others）

- [Office UI Fabric Core](https://developer.microsoft.com/en-us/fabric) - Office 风格的 UI 库，**Microsoft 官方发布**。
- [Semantic UI](https://semantic-ui.com) - 很受欢迎的组件库。（:warning: 不再更新）
- [UIkit](https://getuikit.com/) - 轻量级的现代化前端 CSS 框架。
- [Pure.CSS](https://purecss.io/) - 一组小的，响应式的 CSS 模块。
- [Skeleton](http://getskeleton.com/)
- [Framework7](https://framework7.io/) - 跨平台 UI 库，支持 Android/ios/Desktop 平台，且主题样式设计适配相应平台。
- [Metro 4](https://metroui.org.ua/)
- [Layui](https://www.layui.com/) - 适合后端开发使用。

### 独立组件

*Independent UI components, only providing component modules that implement an interactive function.*

- 时间日期选择器（DatePicker & TimePicker）
  - [flatpickr](https://flatpickr.js.org/)
  - [layDate](https://www.layui.com/laydate/)

- 轮播（Carousel）
  - [Swiper](https://swiperjs.com/)
  - [slick-carousel](https://kenwheeler.github.io/slick/)
  - [Glider.js](https://nickpiscitelli.github.io/Glider.js/)
  - [Flickity](https://flickity.metafizzy.co/)
  - [lory.js](http://loryjs.github.io/lory/)
  - [keen-slider](https://keen-slider.io/)
  
- 模态框（Modal box）
  - [SweetAlert](https://sweetalert.js.org/) - 浏览器 Alert 弹框的替代，更漂亮美观。（:warning: 不再更新）
  - [SweetAlert2](https://sweetalert2.github.io/) - SweetAlert 的继承者。
  
- 图片浏览（Image Browse）
  - [Viewer.js](https://fengyuanchen.github.io/viewerjs/) - 图片列表预览。
  - [Image Compare Viewer](https://image-compare-viewer.netlify.app/) - 图片对比预览。
  - [Cropper.js](https://fengyuanchen.github.io/cropperjs/) - 图片裁剪。

- 表格（Table）
  - [Grid.js](https://gridjs.io/) - 高级表格插件。
  - [Frappe Datatable](https://frappe.io/datatable)

- H5 媒体（Audio & Video）
  - [video.js](https://videojs.com/) - 兼容大部分视频格式的视频播放器。
  - [MediaElement.js](http://www.mediaelementjs.com/) - 非常漂亮的视、音频播放器。
  - [Plyr](https://plyr.io/) - 很棒的视、音频播放器。
  - [clappr](http://clappr.io/) - 视频播放器。
  - [APlayer](https://aplayer.js.org/) - 非常漂亮的音乐播放器。
  - [DPlayer](http://dplayer.js.org/) - 视频播放器。
  - [Vime](https://vime-js.com/) - 视频播放器。

- 文件上传（File Upload）
  - [FilePond ](https://pqina.nl/filepond/) - 文件上传。
  - [DropzoneJS](https://www.dropzonejs.com/) - 文件上传组件，支持拖放文件、图片预览功能。

- 拖拽布局（Drag Layout）
  - [Packery](https://packery.metafizzy.co/) - 拖动网格布局。
  - [gridstack.js](https://gridstackjs.com/)
  
- 其它（Others）
  - [TOAST UI Calendar](https://github.com/nhn/tui.calendar) - 强大的日历日程组件。
  - [reveal.js](https://revealjs.com/) - 创建漂亮的演示文稿（幻灯片）。
  - [Cleave.js](https://nosir.github.io/cleave.js/) - 格式化输入框内容。
  - [TOAST UI Editor](https://ui.toast.com/tui-editor/) - 所见即所得编辑器。
  - [fullPage](https://alvarotrigo.com/fullPage/) - 全屏滚动页面。

[`Go Top ↑`](#awesome-web-front-end-list)

## 数据可视化

*Data visualization libraries, such as chart libraries, 3D engines, etc.*

- [D3](https://d3js.org/) - 数据驱动的可视化库，非常著名，许多图表库基于此开发。
- [three.js](https://threejs.org/) - 强大的 JavaScript 3D 动画库。
- [PixiJS](https://www.pixijs.com/) - 高性能 2D WebGL 渲染引擎。
- [Chart.js](https://www.chartjs.org/) - 最流行的轻量级图表库。
- [Frappe Charts](https://frappe.io/charts) - 高性能 SVG 图标库。
- [Frappe Gantt](https://frappe.io/gantt) - 甘特图。
- [Echarts](http://echarts.apache.org/) - 国内百度团队开发的图表库，功能丰富。
- [C3](https://c3js.org/) - 基于 D3 的可重用图表库。
- [GSAP](https://greensock.com/) - 现代化的高性能动画工具库。
- [Shifty](https://jeremyckahn.github.io/shifty/doc/index.html) - 轻量级、高性能的低级动画工具库。
- [Textures.js](https://riccardoscalco.it/textures/) - 创建 SVG 模式。
- [carbon-charts](https://carbon-design-system.github.io/carbon-charts/) - 遵循 Carbon 风格图表库，**IBM 公司发布**。

[`Go Top ↑`](#awesome-web-front-end-list)

## 开发框架

*Web front-end development framework (library).*

- [React.js](https://reactjs.org/) -  前端响应式 UI 库，其技术生态圈非常繁荣，Facebook 公司发布。
  - [Awesome-React.js](./awesome-reactjs.md) - React.js 生态技术汇总。
  
- [Vue.js](https://vuejs.org/)

- [Angular.js](https://angularjs.org/) - 一个比较重型的功能齐全的前端开发框架，Google 公司发布。

- [Svelte](https://svelte.dev/) - 更轻量的前端 UI 库。
  - [Sapper](https://sapper.svelte.dev/) - 基于 Svelte 的 Web App 开发框架。

- [Hyperapp](https://hyperapp.dev/) - 轻量的，纯函数式，声明式开发框架。

[`Go Top ↑`](#awesome-web-front-end-list)

## 更多

*More useful related resources.*

### CDN

*Content distribution network, static resource hosting.*

- Global
  - [jsDelivr](https://www.jsdelivr.com/)
  - [UNPKG](https://unpkg.com/)
  - [cdnjs](https://cdnjs.com/)
  - [Google Hosted Libraries](https://developers.google.com/speed/libraries/)
  
- China
  - [BootCDN](https://www.bootcdn.cn/) - Bootstrap 中文网维护。
  - [75CDN](https://cdn.baomitu.com) - 奇虎 360 前端团队奇舞团维护。
  - [Staticfile CDN](https://staticfile.org/) - 七牛云与掘金维护。
  - [loli.net](https://css.loli.net/)

### 在线工具

*Some online resources, such as CDN, image compression tools, online IDE, etc.*

- Web 安全（Web Security）
  - [SRI Hash Generator](https://www.srihash.org/) - [SRI](https://www.w3.org/TR/SRI/) 的 hash 生成。

- Web 优化（Web Optimization）
  - [web.dev](https://web.dev/)
  - [Varvy SEO tool](https://varvy.com/) - 一个在线网站 SEO、性能检测工具，提供优化建议和技巧。
  - [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Google 提供的在线网站性能检测工具，提供优化建议和技巧，**Google 官方提供**。
  - [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - Google 提供的一个网站优化检测分析工具，已被集成在 Chrome 开发工具中，也可以作为 Chrome 扩展或者命令行工具使用，**Google 官方提供**。
  - [What Web Can Do](https://whatwebcando.today/) - 可以检测当前设备所支持的 Web API，主要检测硬件设备传感器等，**非官方网站**。
    
- 图片压缩（Image Compression）
  - [Compress PNG](https://compresspng.com/)
  - [Picdiet](https://www.picdiet.com/)
  - [TinyPNG](https://tinypng.com/)
  - [Optimizilla](https://imagecompressor.com/)
  - [压缩图](https://www.yasuotu.com/)
  - [色彩笔](http://www.secaibi.com/tools/)
  
- 在线 IDE、编辑器（IDE / Editor）
  - [StackBlitz](https://stackblitz.com/)
  - [JSFiddle](https://jsfiddle.net/)
  - [CodeSandbox](https://codesandbox.io/)
  - [CodePen](https://codepen.io/)
  - [WebAssembly Studio](https://webassembly.studio/) - 在线的 WebAssembly 编辑器，**Mozilla 发布**。
  
- 其它（Others）
  - [enjoyCSS](https://enjoycss.com/) - 便捷的组件样式设计输出在线工具。
  - [bit](https://bit.dev/) - 构建可重用组件的协作平台。
  - [Prettier Playground](https://prettier.io/playground/) - Prettier 代码格式化工具的在线版本。
  - [Color Hunt](https://colorhunt.co/) - 配色方案。
  - [Open Color](https://yeun.github.io/open-color/) - 配色方案。
  - [Sorted CSS Colors](https://enes.in/sorted-colors/)  
  - [Doka](https://doka.photo/) - 图片编辑工具。
  - [easings.co](https://easings.co/) - 测试动画函数效果。
  - [Keyframes](https://keyframes.app/) - CSS 预览小工具。

### 文章

*Some technical discussion articles.*

- [What forces layout / reflow](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) - 一些会导致重绘、重布局的 DOM 操作。
- [You might not need jQuery](http://youmightnotneedjquery.com/)
- [CSS Tricks](https://css-tricks.com/) - CSS 技术文章。
- [The complete guide to CSS media queries](https://polypane.app/blog/the-complete-guide-to-css-media-queries/)

### 其它

*Other unclassified resources.*

- WebAssembly(wasm)
  - [Emscripten](https://emscripten.org/) - 用于编译为使用 LLVM 构建的 asm.js 和 WebAssembly 的工具链，可在 Web 浏览器中运行 C/C++ 代码。
  - [Cheerp](https://www.leaningtech.com/cheerp/) - 与 Emscripten 类似。
  - [Perspective](https://github.com/finos/perspective) - 基于 C++ 的 wasm 数据可视化组件。

- [JavaScript Open Source Award](https://osawards.com/javascript/) - JavaScript 开源项目奖，**非官方**。

[`Go Top ↑`](#awesome-web-front-end-list)

```json
{
  "result": {
    "构建工具": {
      "构建工具": [
        {
          "desc": "依赖管理",
          "link": "https://github.com/bower/bower",
          "name": "bower"
        },
        {
          "desc": "程序管理",
          "link": "https://github.com/Homebrew/brew",
          "name": "brew"
        },
        {
          "desc": "同步浏览",
          "link": "https://github.com/BrowserSync/browser-sync",
          "name": "browser-sync"
        },
        {
          "desc": "依赖管理",
          "link": "https://github.com/cnpm/cnpm",
          "name": "cnpm"
        },
        {
          "desc": "JS引擎",
          "link": "https://github.com/ry/deno",
          "name": "deno"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/fex-team/fis3",
          "name": "fis3"
        },
        {
          "desc": "版本控制",
          "link": "https://github.com/git/git",
          "name": "git"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/gruntjs/grunt",
          "name": "grunt"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/gulpjs/gulp",
          "name": "gulp"
        },
        {
          "desc": "Gulp依赖",
          "link": "https://github.com/gulpjs/gulp-cli",
          "name": "gulp-cli"
        },
        {
          "desc": "Node版本管理",
          "link": "https://github.com/tj/n",
          "name": "n"
        },
        {
          "desc": "JS引擎",
          "link": "https://github.com/nodejs/node",
          "name": "node"
        },
        {
          "desc": "依赖管理",
          "link": "https://github.com/npm/npm",
          "name": "npm"
        },
        {
          "desc": "NPM镜像管理",
          "link": "https://github.com/Pana/nrm",
          "name": "nrm"
        },
        {
          "desc": "Node版本管理",
          "link": "https://github.com/creationix/nvm",
          "name": "nvm"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/parcel-bundler/parcel",
          "name": "parcel"
        },
        {
          "desc": "AMD项目构建",
          "link": "https://github.com/requirejs/requirejs",
          "name": "require"
        },
        {
          "desc": "ESM项目构建",
          "link": "https://github.com/rollup/rollup",
          "name": "rollup"
        },
        {
          "desc": "CMD项目构建",
          "link": "https://github.com/seajs/seajs",
          "name": "sea"
        },
        {
          "desc": "ESM项目构建",
          "link": "https://github.com/vitejs/vite",
          "name": "vite"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/webpack/webpack",
          "name": "webpack"
        },
        {
          "desc": "Webpack依赖",
          "link": "https://github.com/webpack/webpack-cli",
          "name": "webpack-cli"
        },
        {
          "desc": "依赖管理",
          "link": "https://github.com/yarnpkg/yarn",
          "name": "yarn"
        },
        {
          "desc": "项目构建",
          "link": "https://github.com/yeoman/yeoman",
          "name": "yeoman"
        }
      ],
      "Webpack转换器": [
        {
          "desc": "JS转换",
          "link": "https://github.com/babel/babel-loader",
          "name": "babel-loader"
        },
        {
          "desc": "CSS转换",
          "link": "https://github.com/webpack-contrib/css-loader",
          "name": "css-loader"
        },
        {
          "desc": "Eslint转换",
          "link": "https://github.com/webpack-contrib/eslint-loader",
          "name": "eslint-loader"
        },
        {
          "desc": "CSS转换",
          "link": "https://github.com/yibn2008/fast-css-loader",
          "name": "fast-css-loader"
        },
        {
          "desc": "Sass转换",
          "link": "https://github.com/yibn2008/fast-sass-loader",
          "name": "fast-sass-loader"
        },
        {
          "desc": "文件转换",
          "link": "https://github.com/webpack-contrib/file-loader",
          "name": "file-loader"
        },
        {
          "desc": "Handlebars转换",
          "link": "https://github.com/pcardune/handlebars-loader",
          "name": "handlebars-loader"
        },
        {
          "desc": "HTML转换",
          "link": "https://github.com/webpack-contrib/html-loader",
          "name": "html-loader"
        },
        {
          "desc": "图像压缩",
          "link": "https://github.com/tcoopman/image-webpack-loader",
          "name": "image-loader"
        },
        {
          "desc": "Less转换",
          "link": "https://github.com/webpack-contrib/less-loader",
          "name": "less-loader"
        },
        {
          "desc": "Postcss转换",
          "link": "https://github.com/postcss/postcss-loader",
          "name": "postcss-loader"
        },
        {
          "desc": "文本转换",
          "link": "https://github.com/webpack-contrib/raw-loader",
          "name": "raw-loader"
        },
        {
          "desc": "React模块热替换",
          "link": "https://github.com/gaearon/react-hot-loader",
          "name": "react-hot-loader"
        },
        {
          "desc": "Sass转换",
          "link": "https://github.com/webpack-contrib/sass-loader",
          "name": "sass-loader"
        },
        {
          "desc": "Style转换",
          "link": "https://github.com/webpack-contrib/style-loader",
          "name": "style-loader"
        },
        {
          "desc": "TS转换",
          "link": "https://github.com/TypeStrong/ts-loader",
          "name": "ts-loader"
        },
        {
          "desc": "Tslint转换",
          "link": "https://github.com/wbuchwalter/tslint-loader",
          "name": "tslint-loader"
        },
        {
          "desc": "URL转换",
          "link": "https://github.com/webpack-contrib/url-loader",
          "name": "url-loader"
        },
        {
          "desc": "Vue转换",
          "link": "https://github.com/vuejs/vue-loader",
          "name": "vue-loader"
        }
      ],
      "Webpack扩展器": [
        {
          "desc": "资源插入",
          "link": "https://github.com/SimenB/add-asset-html-webpack-plugin",
          "name": "add-asset-html-webpack-plugin"
        },
        {
          "desc": "目录清空",
          "link": "https://github.com/johnagan/clean-webpack-plugin",
          "name": "clean-webpack-plugin"
        },
        {
          "desc": "高强压缩",
          "link": "https://github.com/webpack-contrib/compression-webpack-plugin",
          "name": "compression-webpack-plugin"
        },
        {
          "desc": "文件复制",
          "link": "https://github.com/webpack-contrib/copy-webpack-plugin",
          "name": "copy-webpack-plugin"
        },
        {
          "desc": "CSS排序",
          "link": "https://github.com/beckan/csscomb-webpack-plugin",
          "name": "csscomb-webpack-plugin"
        },
        {
          "desc": "深度摇树优化",
          "link": "https://github.com/vincentdchan/webpack-deep-scope-analysis-plugin",
          "name": "deep-scope-analysis-webpack-plugin"
        },
        {
          "desc": "TS进程克隆",
          "link": "https://github.com/Realytics/fork-ts-checker-webpack-plugin",
          "name": "fork-ts-checker-webpack-plugin"
        },
        {
          "desc": "错误提示",
          "link": "https://github.com/geowarin/friendly-errors-webpack-plugin",
          "name": "friendly-errors-webpack-plugin"
        },
        {
          "desc": "缓存优化",
          "link": "https://github.com/mzgoddard/hard-source-webpack-plugin",
          "name": "hard-source-webpack-plugin"
        },
        {
          "desc": "资源插入",
          "link": "https://github.com/jharris4/html-webpack-tags-plugin",
          "name": "html-tags-webpack-plugin"
        },
        {
          "desc": "HTML入口配置",
          "link": "https://github.com/jantimon/html-webpack-plugin",
          "name": "html-webpack-plugin"
        },
        {
          "desc": "图像压缩",
          "link": "https://github.com/Klathmon/imagemin-webpack-plugin",
          "name": "imagemin-webpack-plugin"
        },
        {
          "desc": "Lodash按需导入",
          "link": "https://github.com/lodash/lodash-webpack-plugin",
          "name": "lodash-webpack-plugin"
        },
        {
          "desc": "CSS分离",
          "link": "https://github.com/webpack-contrib/mini-css-extract-plugin",
          "name": "mini-css-extract-webpack-plugin"
        },
        {
          "desc": "CSS压缩",
          "link": "https://github.com/NMFR/optimize-css-assets-webpack-plugin",
          "name": "optimize-css-assets-webpack-plugin"
        },
        {
          "desc": "并行处理",
          "link": "https://github.com/trivago/parallel-webpack",
          "name": "parallel-webpack-plugin"
        },
        {
          "desc": "进度显示",
          "link": "https://github.com/clessg/progress-bar-webpack-plugin",
          "name": "progress-bar-webpack-plugin"
        },
        {
          "desc": "CSS压缩",
          "link": "https://github.com/webpack-contrib/purifycss-webpack",
          "name": "purifycss-webpack-plugin"
        },
        {
          "desc": "速度分析",
          "link": "https://github.com/stephencookdev/speed-measure-webpack-plugin",
          "name": "speed-measure-webpack-plugin"
        },
        {
          "desc": "CSS校验",
          "link": "https://github.com/webpack-contrib/stylelint-webpack-plugin",
          "name": "stylelint-webpack-plugin"
        },
        {
          "desc": "JS压缩(ES6)",
          "link": "https://github.com/webpack-contrib/terser-webpack-plugin",
          "name": "terser-webpack-plugin"
        },
        {
          "desc": "图像压缩",
          "link": "https://github.com/JowayYoung/tinyimg-webpack-plugin",
          "name": "tinyimg-webpack-plugin"
        },
        {
          "desc": "JS压缩(ES5)",
          "link": "https://github.com/webpack-contrib/uglifyjs-webpack-plugin",
          "name": "uglifyjs-webpack-plugin"
        },
        {
          "desc": "进度显示",
          "link": "https://github.com/nuxt/webpackbar",
          "name": "webpack-bar"
        },
        {
          "desc": "构建提示",
          "link": "https://github.com/RoccoC/webpack-build-notifier",
          "name": "webpack-build-notifier"
        },
        {
          "desc": "模块分析",
          "link": "https://github.com/webpack-contrib/webpack-bundle-analyzer",
          "name": "webpack-bundle-analyzer"
        },
        {
          "desc": "数据面板",
          "link": "https://github.com/FormidableLabs/webpack-dashboard",
          "name": "webpack-dashboard"
        },
        {
          "desc": "本地服务",
          "link": "https://github.com/webpack/webpack-dev-server",
          "name": "webpack-dev-server"
        },
        {
          "desc": "配置合并",
          "link": "https://github.com/survivejs/webpack-merge",
          "name": "webpack-merge"
        },
        {
          "desc": "Node模块导入",
          "link": "https://github.com/liady/webpack-node-externals",
          "name": "webpack-node-externals"
        },
        {
          "desc": "CSS精灵图",
          "link": "https://github.com/mixtur/webpack-spritesmith",
          "name": "webpack-spritesmith"
        }
      ]
    },
    "编译工具": {
      "编译工具": [
        {
          "desc": "JS编译",
          "link": "https://github.com/babel/babel",
          "name": "babel"
        },
        {
          "desc": "浏览器类型",
          "link": "https://github.com/browserslist/browserslist",
          "name": "browserslist"
        },
        {
          "desc": "CSS排序",
          "link": "https://github.com/csscomb/csscomb.js",
          "name": "csscomb"
        },
        {
          "desc": "CSS压缩",
          "link": "https://github.com/cssnano/cssnano",
          "name": "cssnano"
        },
        {
          "desc": "Sass引擎",
          "link": "https://github.com/sass/dart-sass",
          "name": "dart-sass"
        },
        {
          "desc": "JS校验",
          "link": "https://github.com/eslint/eslint",
          "name": "eslint"
        },
        {
          "desc": "字体压缩",
          "link": "https://github.com/aui/font-spider",
          "name": "font-spider"
        },
        {
          "desc": "字体压缩(升级版)",
          "link": "https://github.com/allanguys/font-spider-plus",
          "name": "font-spider-plus"
        },
        {
          "desc": "并行处理",
          "link": "https://github.com/amireh/happypack",
          "name": "happypack"
        },
        {
          "desc": "CSS编译",
          "link": "https://github.com/less/less.js",
          "name": "less"
        },
        {
          "desc": "Sass引擎",
          "link": "https://github.com/sass/node-sass",
          "name": "node-sass"
        },
        {
          "desc": "CSS编译",
          "link": "https://github.com/postcss/postcss",
          "name": "postcss"
        },
        {
          "desc": "HTML编译",
          "link": "https://github.com/posthtml/posthtml",
          "name": "posthtml"
        },
        {
          "desc": "代码美化",
          "link": "https://github.com/prettier/prettier",
          "name": "prettier"
        },
        {
          "desc": "CSS压缩",
          "link": "https://github.com/purifycss/purifycss",
          "name": "purifycss"
        },
        {
          "desc": "CSS编译",
          "link": "https://github.com/sass/sass",
          "name": "sass"
        },
        {
          "desc": "CSS校验",
          "link": "https://github.com/stylelint/stylelint",
          "name": "stylelint"
        },
        {
          "desc": "CSS编译",
          "link": "https://github.com/stylus/stylus",
          "name": "stylus"
        },
        {
          "desc": "JS压缩(ES6)",
          "link": "https://github.com/terser-js/terser",
          "name": "terser"
        },
        {
          "desc": "TS校验",
          "link": "https://github.com/palantir/tslint",
          "name": "tslint"
        },
        {
          "desc": "JS编译",
          "link": "https://github.com/Microsoft/TypeScript",
          "name": "typescript"
        },
        {
          "desc": "JS压缩(ES5)",
          "link": "https://github.com/mishoo/UglifyJS2",
          "name": "uglifyjs"
        }
      ],
      "Postcss插件": [
        {
          "desc": "前缀垫片",
          "link": "https://github.com/postcss/autoprefixer",
          "name": "autoprefixer"
        },
        {
          "desc": "新语法垫片",
          "link": "https://github.com/MoOx/postcss-cssnext",
          "name": "postcss-cssnext"
        },
        {
          "desc": "内联垫片",
          "link": "https://github.com/postcss/postcss-import",
          "name": "postcss-import"
        },
        {
          "desc": "预设环境",
          "link": "https://github.com/csstools/postcss-preset-env",
          "name": "postcss-preset-env"
        }
      ],
      "Babel插件": [
        {
          "desc": "Eslint配置",
          "link": "https://github.com/babel/babel-eslint",
          "name": "babel-eslint"
        },
        {
          "desc": "JS压缩",
          "link": "https://github.com/babel/minify",
          "name": "babel-minify"
        },
        {
          "desc": "Element按需导入",
          "link": "https://github.com/ElementUI/babel-plugin-component",
          "name": "babel-plugin-component"
        },
        {
          "desc": "AntDesign按需导入",
          "link": "https://github.com/ant-design/babel-plugin-import",
          "name": "babel-plugin-import"
        },
        {
          "desc": "Lodash按需导入",
          "link": "https://github.com/lodash/babel-plugin-lodash",
          "name": "babel-plugin-lodash"
        }
      ],
      "Stylelint插件": [
        {
          "desc": "美化配置",
          "link": "https://github.com/prettier/stylelint-config-prettier",
          "name": "stylelint-config-prettier"
        },
        {
          "desc": "标准配置",
          "link": "https://github.com/stylelint/stylelint-config-standard",
          "name": "stylelint-config-standard"
        }
      ],
      "Eslint插件": [
        {
          "desc": "美化配置",
          "link": "https://github.com/prettier/eslint-config-prettier",
          "name": "eslint-config-prettier"
        },
        {
          "desc": "标准配置",
          "link": "https://github.com/standard/eslint-config-standard",
          "name": "eslint-config-standard"
        },
        {
          "desc": "错误提示",
          "link": "https://github.com/royriojas/eslint-friendly-formatter",
          "name": "eslint-friendly-formatter"
        },
        {
          "desc": "HTML校验",
          "link": "https://github.com/BenoitZugmeyer/eslint-plugin-html",
          "name": "eslint-plugin-html"
        },
        {
          "desc": "Import校验",
          "link": "https://github.com/benmosher/eslint-plugin-import",
          "name": "eslint-plugin-import"
        },
        {
          "desc": "Node校验",
          "link": "https://github.com/mysticatea/eslint-plugin-node",
          "name": "eslint-plugin-node"
        },
        {
          "desc": "Prettier校验",
          "link": "https://github.com/prettier/eslint-plugin-prettier",
          "name": "eslint-plugin-prettier"
        },
        {
          "desc": "Promise校验",
          "link": "https://github.com/xjamundx/eslint-plugin-promise",
          "name": "eslint-plugin-promise"
        },
        {
          "desc": "React校验",
          "link": "https://github.com/yannickcr/eslint-plugin-react",
          "name": "eslint-plugin-react"
        },
        {
          "desc": "标准校验",
          "link": "https://github.com/standard/eslint-plugin-standard",
          "name": "eslint-plugin-standard"
        },
        {
          "desc": "Vue校验",
          "link": "https://github.com/vuejs/eslint-plugin-vue",
          "name": "eslint-plugin-vue"
        }
      ],
      "Tslint插件": [
        {
          "desc": "标准配置",
          "link": "https://github.com/blakeembrey/tslint-config-standard",
          "name": "tslint-config-standard"
        },
        {
          "desc": "React校验",
          "link": "https://github.com/palantir/tslint-react",
          "name": "tslint-plugin-react"
        }
      ]
    }
  }
}



{
  "result": {
    "前端框架平台": {
      "脚手架": [
        {
          "desc": "Angular脚手架",
          "link": "https://github.com/angular/angular-cli",
          "name": "angular-cli"
        },
        {
          "desc": "React/Vue脚手架",
          "link": "https://github.com/JowayYoung/bruce-cli",
          "name": "bruce-cli"
        },
        {
          "desc": "Cordova脚手架",
          "link": "https://github.com/apache/cordova-cli",
          "name": "cordova-cli"
        },
        {
          "desc": "React脚手架",
          "link": "https://github.com/facebook/create-react-app",
          "name": "create-react-app"
        },
        {
          "desc": "Ionic脚手架",
          "link": "https://github.com/ionic-team/ionic-cli",
          "name": "ionic-cli"
        },
        {
          "desc": "Phonegap脚手架",
          "link": "https://github.com/phonegap/phonegap-cli",
          "name": "phonegap-cli"
        },
        {
          "desc": "Vue脚手架",
          "link": "https://github.com/vuejs/vue-cli",
          "name": "vue-cli"
        }
      ],
      "数据框架": [
        {
          "desc": "Angular1",
          "link": "https://github.com/angular/angular.js",
          "name": "angular1"
        },
        {
          "desc": "Angular2",
          "link": "https://github.com/angular/angular",
          "name": "angular2"
        },
        {
          "desc": "Omi",
          "link": "https://github.com/Tencent/omi",
          "name": "omi"
        },
        {
          "desc": "Preact(类React)",
          "link": "https://github.com/developit/preact",
          "name": "preact"
        },
        {
          "desc": "React",
          "link": "https://github.com/facebook/react",
          "name": "react"
        },
        {
          "desc": "Vue",
          "link": "https://github.com/vuejs/vue",
          "name": "vue"
        }
      ],
      "设计框架": [
        {
          "desc": "Jquery移动端UI",
          "link": "https://github.com/amazeui/amazeui",
          "name": "amaze-ui"
        },
        {
          "desc": "React桌面端UI",
          "link": "https://github.com/ant-design/ant-design",
          "name": "ant-design"
        },
        {
          "desc": "React移动端UI",
          "link": "https://github.com/ant-design/ant-design-mobile",
          "name": "ant-design-mobile"
        },
        {
          "desc": "React桌面端中台UI",
          "link": "https://github.com/ant-design/ant-design-pro",
          "name": "ant-design-pro"
        },
        {
          "desc": "Jquery双端UI",
          "link": "https://github.com/twbs/bootstrap",
          "name": "bootstrap"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/didi/cube-ui",
          "name": "cube-ui"
        },
        {
          "desc": "Vue桌面端UI",
          "link": "https://github.com/ElemeFE/element",
          "name": "element"
        },
        {
          "desc": "Jquery双端UI",
          "link": "https://github.com/designmodo/Flat-UI",
          "name": "flat-ui"
        },
        {
          "desc": "Jquery双端UI",
          "link": "https://github.com/zurb/foundation-sites",
          "name": "foundation"
        },
        {
          "desc": "无依赖移动端UI",
          "link": "https://github.com/framework7io/framework7",
          "name": "framework7"
        },
        {
          "desc": "博客框架",
          "link": "https://github.com/hexojs/hexo",
          "name": "hexo"
        },
        {
          "desc": "Vue桌面端UI",
          "link": "https://github.com/iview/iview",
          "name": "iview"
        },
        {
          "desc": "React双端UI",
          "link": "https://github.com/mui-org/material-ui",
          "name": "material-ui"
        },
        {
          "desc": "Angular1双端UI",
          "link": "https://github.com/angular/material",
          "name": "material1"
        },
        {
          "desc": "Angular2+双端UI",
          "link": "https://github.com/angular/material2",
          "name": "material2"
        },
        {
          "desc": "Jquery双端UI",
          "link": "https://github.com/olton/Metro-UI-CSS",
          "name": "metro-ui"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/ElemeFE/mint-ui",
          "name": "mint-ui"
        },
        {
          "desc": "无依赖移动端UI",
          "link": "https://github.com/dcloudio/mui",
          "name": "mui"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/museui/muse-ui",
          "name": "muse-ui"
        },
        {
          "desc": "Angular双端UI",
          "link": "https://github.com/ng-bootstrap/ng-bootstrap",
          "name": "ng-bootstrap"
        },
        {
          "desc": "React小程序UI",
          "link": "https://github.com/NervJS/taro-ui",
          "name": "taro-ui"
        },
        {
          "desc": "Vue小程序UI",
          "link": "https://github.com/YanxinNet/uView",
          "name": "u-view"
        },
        {
          "desc": "Vue小程序UI",
          "link": "https://github.com/dcloudio/uni-ui",
          "name": "uni-ui"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/youzan/vant",
          "name": "vant"
        },
        {
          "desc": "Vue小程序UI",
          "link": "https://github.com/youzan/vant-weapp",
          "name": "vant-weapp"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/wangdahoo/vonic",
          "name": "vonic"
        },
        {
          "desc": "Vue移动端UI",
          "link": "https://github.com/airyland/vux",
          "name": "vux"
        },
        {
          "desc": "无依赖小程序UI",
          "link": "https://github.com/Tencent/weui",
          "name": "we-ui"
        }
      ],
      "应用框架": [
        {
          "desc": "Ionic原生",
          "link": "https://github.com/ionic-team/capacitor",
          "name": "capacitor"
        },
        {
          "desc": "无依赖桌面端应用",
          "link": "https://github.com/electron/electron",
          "name": "electron"
        },
        {
          "desc": "无依赖移动端应用",
          "link": "https://github.com/flutter/flutter",
          "name": "flutter"
        },
        {
          "desc": "Angular移动端应用",
          "link": "https://github.com/ionic-team/ionic",
          "name": "ionic"
        },
        {
          "desc": "Ionic基础应用",
          "link": "https://github.com/ionic-team/ionic-conference-app",
          "name": "ionic-conference-app"
        },
        {
          "desc": "Ionic原生",
          "link": "https://github.com/ionic-team/ionic-native",
          "name": "ionic-native"
        },
        {
          "desc": "Ionic图标",
          "link": "https://github.com/ionic-team/ionicons",
          "name": "ionicons"
        },
        {
          "desc": "Angular移动端应用",
          "link": "https://github.com/NativeScript/NativeScript",
          "name": "nativescript"
        },
        {
          "desc": "Angular移动端应用",
          "link": "https://github.com/ionic-team/ng-cordova",
          "name": "ng-cordova"
        },
        {
          "desc": "Vue移动端应用",
          "link": "https://github.com/quasarframework/quasar",
          "name": "quasar"
        },
        {
          "desc": "React移动端应用",
          "link": "https://github.com/facebook/react-native",
          "name": "react-native"
        },
        {
          "desc": "Ionic原生",
          "link": "https://github.com/ionic-team/stencil",
          "name": "stencil"
        },
        {
          "desc": "Vue移动端应用",
          "link": "https://github.com/apache/incubator-weex",
          "name": "weex"
        }
      ],
      "小程序框架": [
        {
          "desc": "Vue小程序",
          "link": "https://github.com/Meituan-Dianping/mpvue",
          "name": "mpvue"
        },
        {
          "desc": "React小程序",
          "link": "https://github.com/NervJS/taro",
          "name": "taro"
        },
        {
          "desc": "Vue小程序",
          "link": "https://github.com/dcloudio/uni-app",
          "name": "uni-app"
        },
        {
          "desc": "Vue小程序",
          "link": "https://github.com/Tencent/wepy",
          "name": "wepy"
        },
        {
          "desc": "无依赖小程序",
          "link": "https://github.com/Tencent/westore",
          "name": "westore"
        }
      ],
      "微前端框架": [
        {
          "desc": "单页应用微前端",
          "link": "https://github.com/umijs/qiankun",
          "name": "qiankun"
        },
        {
          "desc": "单页应用微前端",
          "link": "https://github.com/single-spa/single-spa",
          "name": "single-spa"
        }
      ],
      "React组件": [
        {
          "desc": "动画渲染",
          "link": "https://github.com/ant-design/ant-motion",
          "name": "ant-motion"
        },
        {
          "desc": "可视图表",
          "link": "https://github.com/alibaba/BizCharts",
          "name": "biz-charts"
        },
        {
          "desc": "文本编辑",
          "link": "https://github.com/margox/braft-editor",
          "name": "braft-editor"
        },
        {
          "desc": "可视表格",
          "link": "https://github.com/maticzav/ink-table",
          "name": "ink-table"
        },
        {
          "desc": "参数校验",
          "link": "https://github.com/facebook/prop-types",
          "name": "prop-types"
        },
        {
          "desc": "高德地图",
          "link": "https://github.com/ElemeFE/react-amap",
          "name": "react-amap"
        },
        {
          "desc": "移动拖拽",
          "link": "https://github.com/atlassian/react-beautiful-dnd",
          "name": "react-beautiful-dnd"
        },
        {
          "desc": "复制粘贴",
          "link": "https://github.com/nihey/react-clipboard.js",
          "name": "react-clipboard"
        },
        {
          "desc": "样式隔离",
          "link": "https://github.com/gajus/react-css-modules",
          "name": "react-css-modules"
        },
        {
          "desc": "节点渲染",
          "link": "https://github.com/hot-loader/react-dom",
          "name": "react-dom"
        },
        {
          "desc": "触摸点透",
          "link": "https://github.com/JakeSidSmith/react-fastclick",
          "name": "react-fastclick"
        },
        {
          "desc": "骨架占位",
          "link": "https://github.com/toplan/react-hold",
          "name": "react-hold"
        },
        {
          "desc": "懒加载",
          "link": "https://github.com/jasonslyvia/react-lazyload",
          "name": "react-lazyload"
        },
        {
          "desc": "动态加载",
          "link": "https://github.com/jamiebuilds/react-loadable",
          "name": "react-loadable"
        },
        {
          "desc": "状态管理",
          "link": "https://github.com/mobxjs/mobx-react",
          "name": "react-mobx"
        },
        {
          "desc": "PDF",
          "link": "https://github.com/diegomura/react-pdf",
          "name": "react-pdf"
        },
        {
          "desc": "骨架占位",
          "link": "https://github.com/buildo/react-placeholder",
          "name": "react-placeholder"
        },
        {
          "desc": "状态管理",
          "link": "https://github.com/reduxjs/react-redux",
          "name": "react-redux"
        },
        {
          "desc": "页面路由",
          "link": "https://github.com/ReactTraining/react-router",
          "name": "react-router"
        },
        {
          "desc": "下拉选择",
          "link": "https://github.com/JedWatson/react-select",
          "name": "react-select"
        },
        {
          "desc": "弹簧动画",
          "link": "https://github.com/react-spring/react-spring",
          "name": "react-spring"
        },
        {
          "desc": "Hooks集合",
          "link": "https://github.com/streamich/react-use",
          "name": "react-use"
        },
        {
          "desc": "虚拟滚动",
          "link": "https://github.com/bvaughn/react-virtualized",
          "name": "react-virtualized"
        },
        {
          "desc": "状态管理",
          "link": "https://github.com/facebookexperimental/Recoil",
          "name": "recoil"
        }
      ],
      "Vue组件": [
        {
          "desc": "高德地图",
          "link": "https://github.com/ElemeFE/vue-amap",
          "name": "vue-amap"
        },
        {
          "desc": "装饰器",
          "link": "https://github.com/vuejs/vue-class-component",
          "name": "vue-class-component"
        },
        {
          "desc": "日历",
          "link": "https://github.com/charliekassel/vuejs-datepicker",
          "name": "vue-datepicker"
        },
        {
          "desc": "页面路由",
          "link": "https://github.com/vuejs/vue-router",
          "name": "vue-router"
        },
        {
          "desc": "虚拟滚动",
          "link": "https://github.com/tangbc/vue-virtual-scroll-list",
          "name": "vue-virtual-scroll-list"
        },
        {
          "desc": "虚拟滚动",
          "link": "https://github.com/Akryum/vue-virtual-scroller",
          "name": "vue-virtual-scroller"
        },
        {
          "desc": "状态管理",
          "link": "https://github.com/vuejs/vuex",
          "name": "vuex"
        }
      ]
    },
    "后端框架平台": {
      "服务框架": [
        {
          "desc": "Egg",
          "link": "https://github.com/eggjs/egg",
          "name": "egg"
        },
        {
          "desc": "Express",
          "link": "https://github.com/expressjs/express",
          "name": "express"
        },
        {
          "desc": "Fastify",
          "link": "https://github.com/fastify/fastify",
          "name": "fastify"
        },
        {
          "desc": "Hapi",
          "link": "https://github.com/hapijs/hapi",
          "name": "hapi"
        },
        {
          "desc": "Koa",
          "link": "https://github.com/koajs/koa",
          "name": "koa"
        },
        {
          "desc": "Meteor",
          "link": "https://github.com/meteor/meteor",
          "name": "meteor"
        }
      ],
      "渲染框架": [
        {
          "desc": "TS服务端渲染",
          "link": "https://github.com/nestjs/nest",
          "name": "nest"
        },
        {
          "desc": "React服务端渲染",
          "link": "https://github.com/zeit/next.js",
          "name": "next"
        },
        {
          "desc": "Vue服务端渲染",
          "link": "https://github.com/nuxt/nuxt.js",
          "name": "nuxt"
        },
        {
          "desc": "Angular服务端渲染",
          "link": "https://github.com/angular/universal",
          "name": "universal"
        }
      ],
      "爬虫框架": [
        {
          "desc": "无头浏览器",
          "link": "https://github.com/GoogleChromeLabs/carlo",
          "name": "carlo"
        },
        {
          "desc": "服务端Jquery",
          "link": "https://github.com/cheeriojs/cheerio",
          "name": "cheerio"
        },
        {
          "desc": "无头浏览器",
          "link": "https://github.com/ariya/phantomjs",
          "name": "phantom"
        },
        {
          "desc": "无头浏览器",
          "link": "https://github.com/GoogleChrome/puppeteer",
          "name": "puppeteer"
        }
      ],
      "智能框架": [
        {
          "desc": "人工智能",
          "link": "https://github.com/tensorflow/tfjs",
          "name": "tensorflow"
        },
        {
          "desc": "图像识别",
          "link": "https://github.com/naptha/tesseract.js",
          "name": "tesseract"
        }
      ],
      "数据操作": [
        {
          "desc": "Mongodb数据库",
          "link": "https://github.com/mongodb/mongo",
          "name": "mongodb"
        },
        {
          "desc": "MongoDB指令",
          "link": "https://github.com/Automattic/mongoose",
          "name": "mongoose"
        },
        {
          "desc": "MySQL数据库",
          "link": "https://github.com/mysqljs/mysql",
          "name": "mysql"
        },
        {
          "desc": "MySQL指令",
          "link": "https://github.com/sequelize/sequelize",
          "name": "sequelize"
        }
      ],
      "Express中间件": [
        {
          "desc": "Body处理",
          "link": "https://github.com/expressjs/body-parser",
          "name": "body-parser"
        },
        {
          "desc": "Cookie处理",
          "link": "https://github.com/expressjs/cookie-parser",
          "name": "cookie-parser"
        }
      ],
      "Koa中间件": [
        {
          "desc": "Body处理",
          "link": "https://github.com/dlau/koa-body",
          "name": "koa-body"
        },
        {
          "desc": "跨域处理",
          "link": "https://github.com/zadzbw/koa2-cors",
          "name": "koa-cors"
        },
        {
          "desc": "JSON处理",
          "link": "https://github.com/koajs/json",
          "name": "koa-json"
        },
        {
          "desc": "JWT处理",
          "link": "https://github.com/koajs/jwt",
          "name": "koa-jwt"
        },
        {
          "desc": "日志处理",
          "link": "https://github.com/koajs/logger",
          "name": "koa-logger"
        },
        {
          "desc": "错误处理",
          "link": "https://github.com/koajs/onerror",
          "name": "koa-onerror"
        },
        {
          "desc": "路由处理",
          "link": "https://github.com/koajs/router",
          "name": "koa-router"
        },
        {
          "desc": "SSL处理",
          "link": "https://github.com/turboMaCk/koa-sslify",
          "name": "koa-sslify"
        },
        {
          "desc": "用户代理处理",
          "link": "https://github.com/rvboris/koa-useragent",
          "name": "koa-useragent"
        }
      ],
      "Webpack中间件": [
        {
          "desc": "历史记录",
          "link": "https://github.com/bripkens/connect-history-api-fallback",
          "name": "connect-history-api-fallback"
        },
        {
          "desc": "HTTP代理",
          "link": "https://github.com/chimurai/http-proxy-middleware",
          "name": "http-proxy-middleware"
        },
        {
          "desc": "本地服务",
          "link": "https://github.com/webpack/webpack-dev-middleware",
          "name": "webpack-dev-middleware"
        },
        {
          "desc": "模块热替换",
          "link": "https://github.com/webpack-contrib/webpack-hot-middleware",
          "name": "webpack-hot-middleware"
        }
      ]
    }
  }
}


{
  "result": {
    "全端类库工具": {
      "垫片": [
        {
          "desc": "Promise语法垫片",
          "link": "https://github.com/petkaantonov/bluebird",
          "name": "bluebird"
        },
        {
          "desc": "JS语法垫片",
          "link": "https://github.com/zloirock/core-js",
          "name": "core-js"
        },
        {
          "desc": "JS语法垫片",
          "link": "https://github.com/polyfills/polyfills",
          "name": "polyfills"
        },
        {
          "desc": "Async/Await语法垫片",
          "link": "https://github.com/facebook/regenerator",
          "name": "regenerator"
        }
      ],
      "模板": [
        {
          "desc": "模板引擎整合",
          "link": "https://github.com/tj/consolidate.js",
          "name": "consolidate"
        },
        {
          "desc": "Ejs模板",
          "link": "https://github.com/tj/ejs",
          "name": "ejs"
        },
        {
          "desc": "Handlebars模板",
          "link": "https://github.com/wycats/handlebars.js",
          "name": "handlebars"
        },
        {
          "desc": "Nunjucks模板",
          "link": "https://github.com/mozilla/nunjucks",
          "name": "nunjucks"
        },
        {
          "desc": "Pug模板",
          "link": "https://github.com/pugjs/pug",
          "name": "pug"
        }
      ],
      "函数": [
        {
          "desc": "数字美化",
          "link": "https://github.com/MikeMcl/big.js",
          "name": "big"
        },
        {
          "desc": "数字美化",
          "link": "https://github.com/MikeMcl/bignumber.js",
          "name": "bignumber"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/chancejs/chancejs",
          "name": "chance"
        },
        {
          "desc": "样式选择",
          "link": "https://github.com/JedWatson/classnames",
          "name": "classnames"
        },
        {
          "desc": "Generator自动执行",
          "link": "https://github.com/tj/co",
          "name": "co"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/ecrmnn/collect.js",
          "name": "collect"
        },
        {
          "desc": "比特币",
          "link": "https://github.com/bitpay/copay",
          "name": "copay"
        },
        {
          "desc": "加密解密",
          "link": "https://github.com/brix/crypto-js",
          "name": "crypto"
        },
        {
          "desc": "时间美化",
          "link": "https://github.com/date-fns/date-fns",
          "name": "date-fns"
        },
        {
          "desc": "时间美化",
          "link": "https://github.com/iamkun/dayjs",
          "name": "day"
        },
        {
          "desc": "数字美化",
          "link": "https://github.com/MikeMcl/decimal.js",
          "name": "decimal"
        },
        {
          "desc": "文本过滤",
          "link": "https://github.com/pyloque/fastscan",
          "name": "fastscan"
        },
        {
          "desc": "模糊搜索",
          "link": "https://github.com/mattyork/fuzzy",
          "name": "fuzzy"
        },
        {
          "desc": "时间美化",
          "link": "https://github.com/globalizejs/globalize",
          "name": "globalize"
        },
        {
          "desc": "编码转换",
          "link": "https://github.com/ashtuchkin/iconv-lite",
          "name": "iconv-lite"
        },
        {
          "desc": "不可变数据函数集合",
          "link": "https://github.com/immerjs/immer",
          "name": "immer"
        },
        {
          "desc": "不可变数据函数集合",
          "link": "https://github.com/facebook/immutable-js",
          "name": "immutable"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/dtao/lazy.js",
          "name": "lazy"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/liriliri/licia",
          "name": "licia"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/lodash/lodash",
          "name": "lodash"
        },
        {
          "desc": "数字美化",
          "link": "https://github.com/josdejong/mathjs",
          "name": "math"
        },
        {
          "desc": "MD5",
          "link": "https://github.com/pvorb/node-md5",
          "name": "md5"
        },
        {
          "desc": "时间美化",
          "link": "https://github.com/moment/moment",
          "name": "moment"
        },
        {
          "desc": "Promise队列控制",
          "link": "https://github.com/sindresorhus/p-queue",
          "name": "p-queue"
        },
        {
          "desc": "字节美化",
          "link": "https://github.com/sindresorhus/pretty-bytes",
          "name": "pretty-bytes"
        },
        {
          "desc": "字符解析",
          "link": "https://github.com/ljharb/qs",
          "name": "qs"
        },
        {
          "desc": "函数式编程",
          "link": "https://github.com/ramda/ramda",
          "name": "ramda"
        },
        {
          "desc": "实时数据库",
          "link": "https://github.com/pubkey/rxdb",
          "name": "rxdb"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/andrewplummer/Sugar",
          "name": "sugar"
        },
        {
          "desc": "钩子函数",
          "link": "https://github.com/webpack/tapable",
          "name": "tapable"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/JowayYoung/trample",
          "name": "trample"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/jashkenas/underscore",
          "name": "underscore"
        },
        {
          "desc": "函数集合",
          "link": "https://github.com/node-modules/utility",
          "name": "utility"
        },
        {
          "desc": "类型校验",
          "link": "https://github.com/ansman/validate.js",
          "name": "validate"
        },
        {
          "desc": "文本美化",
          "link": "https://github.com/panzerdp/voca",
          "name": "voca"
        }
      ],
      "文件": [
        {
          "desc": "图像元数据",
          "link": "https://github.com/exif-js/exif-js",
          "name": "exif"
        },
        {
          "desc": "XSS过滤",
          "link": "https://github.com/leizongmin/js-xss",
          "name": "xss"
        }
      ],
      "网络": [
        {
          "desc": "异步回调",
          "link": "https://github.com/caolan/async",
          "name": "async"
        },
        {
          "desc": "网络请求",
          "link": "https://github.com/axios/axios",
          "name": "axios"
        },
        {
          "desc": "即时聊天",
          "link": "https://github.com/conversejs/converse.js",
          "name": "converse"
        },
        {
          "desc": "网络请求",
          "link": "https://github.com/github/fetch",
          "name": "fetch"
        },
        {
          "desc": "JSONP网络请求",
          "link": "https://github.com/webmodules/jsonp",
          "name": "jsonp"
        },
        {
          "desc": "客户端Socket",
          "link": "https://github.com/socketio/socket.io-client",
          "name": "socket-client"
        },
        {
          "desc": "服务端Socket",
          "link": "https://github.com/socketio/socket.io",
          "name": "socket-server"
        },
        {
          "desc": "WebSocket",
          "link": "https://github.com/websockets/ws",
          "name": "ws"
        }
      ],
      "交互": [
        {
          "desc": "二维码",
          "link": "https://github.com/soldair/node-qrcode",
          "name": "qrcode"
        }
      ],
      "测试": [
        {
          "desc": "App自动化测试",
          "link": "https://github.com/appium/appium",
          "name": "appium"
        },
        {
          "desc": "端对端测试",
          "link": "https://github.com/casperjs/casperjs",
          "name": "casper"
        },
        {
          "desc": "端对端测试",
          "link": "https://github.com/cypress-io/cypress",
          "name": "cypress"
        },
        {
          "desc": "断言测试",
          "link": "https://github.com/airbnb/enzyme",
          "name": "enzyme"
        },
        {
          "desc": "单元测试",
          "link": "https://github.com/jasmine/jasmine",
          "name": "jasmine"
        },
        {
          "desc": "单元测试",
          "link": "https://github.com/facebook/jest",
          "name": "jest"
        },
        {
          "desc": "单元测试",
          "link": "https://github.com/karma-runner/karma",
          "name": "karma"
        },
        {
          "desc": "单元测试",
          "link": "https://github.com/mochajs/mocha",
          "name": "mocha"
        },
        {
          "desc": "端对端测试",
          "link": "https://github.com/segmentio/nightmare",
          "name": "nightmare"
        },
        {
          "desc": "端对端测试",
          "link": "https://github.com/angular/protractor",
          "name": "protractor"
        },
        {
          "desc": "Web自动化测试",
          "link": "https://github.com/SeleniumHQ/selenium",
          "name": "selenium"
        }
      ]
    },
    "前端类库工具": {
      "函数": [
        {
          "desc": "Cookie",
          "link": "https://github.com/voltace/browser-cookies",
          "name": "browser-cookies"
        },
        {
          "desc": "浏览器指纹",
          "link": "https://github.com/XavierXuV5/Check-Browser",
          "name": "check-browser"
        },
        {
          "desc": "桌面端函数集合",
          "link": "https://github.com/jquery/jquery",
          "name": "jquery"
        },
        {
          "desc": "移动端函数集合",
          "link": "https://github.com/madrobby/zepto",
          "name": "zepto"
        }
      ],
      "样式": [
        {
          "desc": "动画",
          "link": "https://github.com/daneden/animate.css",
          "name": "animate"
        },
        {
          "desc": "Sass函数",
          "link": "https://github.com/thoughtbot/bourbon",
          "name": "bourbon"
        },
        {
          "desc": "Instagram滤镜",
          "link": "https://github.com/una/CSSgram",
          "name": "cssgram"
        },
        {
          "desc": "抖动动画",
          "link": "https://github.com/elrumordelaluz/csshake",
          "name": "csshake"
        },
        {
          "desc": "图标",
          "link": "https://github.com/FortAwesome/Font-Awesome",
          "name": "font-awesome"
        },
        {
          "desc": "悬浮动画",
          "link": "https://github.com/IanLunn/Hover",
          "name": "hover"
        },
        {
          "desc": "Instagram滤镜",
          "link": "https://github.com/picturepan2/instagram.css",
          "name": "instagram"
        },
        {
          "desc": "样式初始",
          "link": "https://github.com/necolas/normalize.css",
          "name": "normalize"
        },
        {
          "desc": "图标",
          "link": "https://github.com/Remix-Design/RemixIcon",
          "name": "remix-icon"
        }
      ],
      "界面": [
        {
          "desc": "动画",
          "link": "https://github.com/juliangarnier/anime",
          "name": "anime"
        },
        {
          "desc": "日历",
          "link": "https://github.com/simbawus/calendar",
          "name": "calendar-lite"
        },
        {
          "desc": "全屏滑动",
          "link": "https://github.com/alvarotrigo/fullPage.js",
          "name": "fullpage"
        },
        {
          "desc": "弹窗",
          "link": "https://github.com/sentsin/layer",
          "name": "layer"
        },
        {
          "desc": "相册",
          "link": "https://github.com/lokesh/lightbox2",
          "name": "lightbox"
        },
        {
          "desc": "AE动画",
          "link": "https://github.com/airbnb/lottie-web",
          "name": "lottie-web"
        },
        {
          "desc": "动画",
          "link": "https://github.com/miniMAC/magic",
          "name": "magic"
        },
        {
          "desc": "页面路由",
          "link": "https://github.com/visionmedia/page.js",
          "name": "page"
        },
        {
          "desc": "陀螺仪动画",
          "link": "https://github.com/wagerfield/parallax",
          "name": "parallax"
        },
        {
          "desc": "幻灯片",
          "link": "https://github.com/hakimel/reveal.js",
          "name": "reveal"
        },
        {
          "desc": "网站导航",
          "link": "https://github.com/jrainlau/smartour",
          "name": "smartour"
        },
        {
          "desc": "轮播滑动",
          "link": "https://github.com/nolimits4web/swiper",
          "name": "swiper"
        },
        {
          "desc": "补间动画",
          "link": "https://github.com/tweenjs/tween.js",
          "name": "tween"
        },
        {
          "desc": "动画",
          "link": "https://github.com/julianshapiro/velocity",
          "name": "velocity"
        },
        {
          "desc": "波浪",
          "link": "https://github.com/QiShaoXuan/wavejs",
          "name": "wave"
        }
      ],
      "交互": [
        {
          "desc": "图像处理",
          "link": "https://github.com/AlloyTeam/AlloyImage",
          "name": "alloy-image"
        },
        {
          "desc": "图表",
          "link": "https://github.com/apexcharts/apexcharts.js",
          "name": "apexcharts"
        },
        {
          "desc": "表单调节",
          "link": "https://github.com/jackmoore/autosize",
          "name": "autosize"
        },
        {
          "desc": "图表",
          "link": "https://github.com/chartjs/Chart.js",
          "name": "chart"
        },
        {
          "desc": "输入美化",
          "link": "https://github.com/nosir/cleave.js",
          "name": "cleave"
        },
        {
          "desc": "图像处理",
          "link": "https://github.com/fengyuanchen/cropperjs",
          "name": "cropper"
        },
        {
          "desc": "图表",
          "link": "https://github.com/d3/d3",
          "name": "d3"
        },
        {
          "desc": "SVG/Canvas转换",
          "link": "https://github.com/fabricjs/fabric.js",
          "name": "fabric"
        },
        {
          "desc": "媒体构建",
          "link": "https://github.com/Kagami/ffmpeg.js",
          "name": "ffmpeg"
        },
        {
          "desc": "视频处理",
          "link": "https://github.com/Bilibili/flv.js",
          "name": "flv"
        },
        {
          "desc": "水印",
          "link": "https://github.com/loadchange/gwm",
          "name": "gwm"
        },
        {
          "desc": "图表",
          "link": "https://github.com/highcharts/highcharts",
          "name": "highcharts"
        },
        {
          "desc": "代码高亮",
          "link": "https://github.com/highlightjs/highlight.js",
          "name": "highlight"
        },
        {
          "desc": "Canvas截图",
          "link": "https://github.com/niklasvh/html2canvas",
          "name": "html2canvas"
        },
        {
          "desc": "Canvas处理",
          "link": "https://github.com/koggdal/ocanvas",
          "name": "ocanvas"
        },
        {
          "desc": "WebGL处理",
          "link": "https://github.com/pixijs/pixi.js",
          "name": "pixi"
        },
        {
          "desc": "SVG截图",
          "link": "https://github.com/cburgmer/rasterizeHTML.js",
          "name": "rasterizehtml"
        },
        {
          "desc": "防刷验证",
          "link": "https://github.com/google/recaptcha",
          "name": "recaptcha"
        },
        {
          "desc": "录音",
          "link": "https://github.com/xiangyuecn/Recorder",
          "name": "recorder"
        },
        {
          "desc": "文本编辑",
          "link": "https://github.com/ianstormtaylor/slate",
          "name": "slate"
        },
        {
          "desc": "SVG处理",
          "link": "https://github.com/adobe-webplatform/Snap.svg",
          "name": "snap"
        },
        {
          "desc": "WebGL处理",
          "link": "https://github.com/mrdoob/three.js",
          "name": "three"
        },
        {
          "desc": "视频处理",
          "link": "https://github.com/videojs/video.js",
          "name": "video"
        },
        {
          "desc": "水印",
          "link": "https://github.com/brianium/watermarkjs",
          "name": "watermark"
        },
        {
          "desc": "词云",
          "link": "https://github.com/timdream/wordcloud2.js",
          "name": "wordcloud"
        },
        {
          "desc": "树形图",
          "link": "https://github.com/zTree/zTree_v3",
          "name": "ztree"
        }
      ],
      "事件": [
        {
          "desc": "手势监听",
          "link": "https://github.com/any86/any-touch",
          "name": "any-touch"
        },
        {
          "desc": "视差滚动",
          "link": "https://github.com/electerious/basicScroll",
          "name": "basicscroll"
        },
        {
          "desc": "最优滚动",
          "link": "https://github.com/ustbhuangyi/better-scroll",
          "name": "better-scroll"
        },
        {
          "desc": "复制粘贴",
          "link": "https://github.com/zenorocha/clipboard.js",
          "name": "clipboard"
        },
        {
          "desc": "移动拖拽",
          "link": "https://github.com/desandro/draggabilly",
          "name": "draggabilly"
        },
        {
          "desc": "移动拖拽",
          "link": "https://github.com/bevacqua/dragula",
          "name": "dragula"
        },
        {
          "desc": "触摸点透",
          "link": "https://github.com/ftlabs/fastclick",
          "name": "fastclick"
        },
        {
          "desc": "文件处理",
          "link": "https://github.com/mailru/FileAPI",
          "name": "file-api"
        },
        {
          "desc": "文件保存",
          "link": "https://github.com/eligrey/FileSaver.js",
          "name": "file-saver"
        },
        {
          "desc": "手势监听",
          "link": "https://github.com/hammerjs/hammer.js",
          "name": "hammer"
        },
        {
          "desc": "懒加载",
          "link": "https://github.com/tuupola/jquery_lazyload",
          "name": "lazyload"
        },
        {
          "desc": "懒加载",
          "link": "https://github.com/aFarkas/lazysizes",
          "name": "lazysizes"
        },
        {
          "desc": "加载进度条",
          "link": "https://github.com/usablica/progress.js",
          "name": "progress"
        },
        {
          "desc": "跟踪导航",
          "link": "https://github.com/SHERlocked93/progress-catalog",
          "name": "progress-catalog"
        },
        {
          "desc": "加载进度条",
          "link": "https://github.com/kimmobrunfeldt/progressbar.js",
          "name": "progressbar"
        },
        {
          "desc": "摇一摇",
          "link": "https://github.com/alexgibson/shake.js",
          "name": "shake"
        },
        {
          "desc": "手势监听",
          "link": "https://github.com/ElemeFE/smart-gesture",
          "name": "smart-gesture"
        },
        {
          "desc": "移动拖拽",
          "link": "https://github.com/SortableJS/Sortable",
          "name": "sortable"
        },
        {
          "desc": "跟踪导航",
          "link": "https://github.com/LiranCohen/stickUp",
          "name": "stickup"
        },
        {
          "desc": "图片上传",
          "link": "https://github.com/fex-team/webuploader",
          "name": "webuploader"
        },
        {
          "desc": "滚动动画",
          "link": "https://github.com/matthieua/WOW",
          "name": "wow"
        }
      ],
      "状态": [
        {
          "desc": "状态管理",
          "link": "https://github.com/mobxjs/mobx",
          "name": "mobx"
        },
        {
          "desc": "状态管理",
          "link": "https://github.com/reduxjs/redux",
          "name": "redux"
        },
        {
          "desc": "Redux日志打印",
          "link": "https://github.com/LogRocket/redux-logger",
          "name": "redux-logger"
        },
        {
          "desc": "Redux异步管理",
          "link": "https://github.com/redux-saga/redux-saga",
          "name": "redux-saga"
        },
        {
          "desc": "Redux异步管理",
          "link": "https://github.com/reduxjs/redux-thunk",
          "name": "redux-thunk"
        },
        {
          "desc": "事件流",
          "link": "https://github.com/ReactiveX/rxjs",
          "name": "rxjs"
        }
      ],
      "调试": [
        {
          "desc": "移动端调试面板",
          "link": "https://github.com/liriliri/eruda",
          "name": "eruda"
        },
        {
          "desc": "移动端调试面板",
          "link": "https://github.com/wuchangming/spy-debugger",
          "name": "spy-debugger"
        },
        {
          "desc": "移动端调试面板",
          "link": "https://github.com/Tencent/vConsole",
          "name": "vconsole"
        }
      ]
    },
    "后端类库工具": {
      "进程": [
        {
          "desc": "清屏",
          "link": "https://github.com/bahamas10/node-clear",
          "name": "clear"
        },
        {
          "desc": "命令配置",
          "link": "https://github.com/yargs/cliui",
          "name": "cliui"
        },
        {
          "desc": "命令配置",
          "link": "https://github.com/tj/commander.js",
          "name": "commander"
        },
        {
          "desc": "定时任务",
          "link": "https://github.com/node-cron/node-cron",
          "name": "cron"
        },
        {
          "desc": "运行环境",
          "link": "https://github.com/kentcdodds/cross-env",
          "name": "cross-env"
        },
        {
          "desc": "友好提示",
          "link": "https://github.com/enquirer/enquirer",
          "name": "enquirer"
        },
        {
          "desc": "命令美化",
          "link": "https://github.com/sindresorhus/execa",
          "name": "execa"
        },
        {
          "desc": "线程跳转",
          "link": "https://github.com/laverdet/node-fibers",
          "name": "fibers"
        },
        {
          "desc": "交互式问答",
          "link": "https://github.com/SBoudrias/Inquirer.js",
          "name": "inquirer"
        },
        {
          "desc": "交互式问答(答案自动提示)",
          "link": "https://github.com/mokkabonna/inquirer-autocomplete-prompt",
          "name": "inquirer-autocomplete-prompt"
        },
        {
          "desc": "交互式问答(答案文本着色)",
          "link": "https://github.com/LitoMore/inquirer-chalk-pipe",
          "name": "inquirer-chalk-pipe"
        },
        {
          "desc": "多任务执行",
          "link": "https://github.com/SamVerschueren/listr",
          "name": "listr"
        },
        {
          "desc": "进程重启",
          "link": "https://github.com/remy/nodemon",
          "name": "nodemon"
        },
        {
          "desc": "模块管理",
          "link": "https://github.com/JowayYoung/pkg-master",
          "name": "pkg-master"
        },
        {
          "desc": "进程管理",
          "link": "https://github.com/Unitech/pm2",
          "name": "pm2"
        },
        {
          "desc": "定时任务",
          "link": "https://github.com/node-schedule/node-schedule",
          "name": "schedule"
        },
        {
          "desc": "Shell命令",
          "link": "https://github.com/shelljs/shelljs",
          "name": "shell"
        },
        {
          "desc": "GIF动画",
          "link": "https://github.com/faressoft/terminalizer",
          "name": "terminalizer"
        },
        {
          "desc": "命令配置",
          "link": "https://github.com/yargs/yargs",
          "name": "yargs"
        }
      ],
      "文件": [
        {
          "desc": "文件监听",
          "link": "https://github.com/paulmillr/chokidar",
          "name": "chokidar"
        },
        {
          "desc": "提交校验",
          "link": "https://github.com/conventional-changelog/commitlint",
          "name": "commitlint"
        },
        {
          "desc": "文件压缩",
          "link": "https://github.com/node-modules/compressing",
          "name": "compressing"
        },
        {
          "desc": "配置读取",
          "link": "https://github.com/davidtheclark/cosmiconfig",
          "name": "cosmiconfig"
        },
        {
          "desc": "过时提示",
          "link": "https://github.com/alanshaw/david",
          "name": "david"
        },
        {
          "desc": "路径处理",
          "link": "https://github.com/fshost/node-dir",
          "name": "dir"
        },
        {
          "desc": "文件类型",
          "link": "https://github.com/sindresorhus/file-type",
          "name": "file-type"
        },
        {
          "desc": "文件处理",
          "link": "https://github.com/jprichardson/node-fs-extra",
          "name": "fs-extra"
        },
        {
          "desc": "文件大小",
          "link": "https://github.com/alessioalex/get-folder-size",
          "name": "get-folder-size"
        },
        {
          "desc": "文件遍历",
          "link": "https://github.com/isaacs/node-glob",
          "name": "glob"
        },
        {
          "desc": "图像处理",
          "link": "https://github.com/aheckmann/gm",
          "name": "gm"
        },
        {
          "desc": "提交校验",
          "link": "https://github.com/typicode/husky",
          "name": "husky"
        },
        {
          "desc": "图像大小",
          "link": "https://github.com/image-size/image-size",
          "name": "image-size"
        },
        {
          "desc": "图像批处理",
          "link": "https://github.com/JowayYoung/img-master",
          "name": "img-master"
        },
        {
          "desc": "INI解析",
          "link": "https://github.com/npm/ini",
          "name": "ini"
        },
        {
          "desc": "图像判断",
          "link": "https://github.com/sindresorhus/is-image",
          "name": "is-image"
        },
        {
          "desc": "PDF解析",
          "link": "https://github.com/MrRio/jsPDF",
          "name": "js-pdf"
        },
        {
          "desc": "Excel解析",
          "link": "https://github.com/SheetJS/js-xlsx",
          "name": "js-xlsx"
        },
        {
          "desc": "YAML解析",
          "link": "https://github.com/nodeca/js-yaml",
          "name": "js-yaml"
        },
        {
          "desc": "项目初始",
          "link": "https://github.com/yanhaijing/jslib-base",
          "name": "jslib-base"
        },
        {
          "desc": "依赖关系",
          "link": "https://github.com/pahen/madge",
          "name": "madge"
        },
        {
          "desc": "Markdown解析",
          "link": "https://github.com/markdown-it/markdown-it",
          "name": "markdown-it"
        },
        {
          "desc": "Markdown复选框解析",
          "link": "https://github.com/linsir/markdown-it-task-checkbox",
          "name": "markdown-it-task-checkbox"
        },
        {
          "desc": "静态站点生成",
          "link": "https://github.com/segmentio/metalsmith",
          "name": "metalsmith"
        },
        {
          "desc": "路径创建",
          "link": "https://github.com/substack/node-mkdirp",
          "name": "mkdirp"
        },
        {
          "desc": "二进制文件解析",
          "link": "https://github.com/nodejs/node-gyp",
          "name": "node-gyp"
        },
        {
          "desc": "文件树形图",
          "link": "https://github.com/psyrendust/nodetree",
          "name": "nodetree"
        },
        {
          "desc": "文件打开",
          "link": "https://github.com/sindresorhus/open",
          "name": "open"
        },
        {
          "desc": "垫片服务",
          "link": "https://github.com/Financial-Times/polyfill-library",
          "name": "polyfill-library"
        },
        {
          "desc": "垫片服务",
          "link": "https://github.com/Financial-Times/polyfill-service",
          "name": "polyfill-service"
        },
        {
          "desc": "文件复制",
          "link": "https://github.com/timkendrick/recursive-copy",
          "name": "recursive-copy"
        },
        {
          "desc": "文件删除",
          "link": "https://github.com/isaacs/rimraf",
          "name": "rimraf"
        },
        {
          "desc": "图像处理",
          "link": "https://github.com/lovell/sharp",
          "name": "sharp"
        },
        {
          "desc": "更新提示",
          "link": "https://github.com/yeoman/update-notifier",
          "name": "update-notifier"
        },
        {
          "desc": "Vue文件Eslint解析",
          "link": "https://github.com/mysticatea/vue-eslint-parser",
          "name": "vue-eslint-parser"
        },
        {
          "desc": "文件监听",
          "link": "https://github.com/yuanchuan/node-watch",
          "name": "watch"
        },
        {
          "desc": "Webpack资源管理",
          "link": "https://github.com/webpack/webpack-sources",
          "name": "webpack-sources"
        },
        {
          "desc": "Excel解析",
          "link": "https://github.com/mgcrea/node-xlsx",
          "name": "xlsx"
        }
      ],
      "网络": [
        {
          "desc": "本地服务",
          "link": "https://github.com/indexzero/http-server",
          "name": "http-server"
        },
        {
          "desc": "网络请求模拟",
          "link": "https://github.com/typicode/json-server",
          "name": "json-server"
        },
        {
          "desc": "身份校验",
          "link": "https://github.com/auth0/node-jsonwebtoken",
          "name": "jsonwebtoken"
        },
        {
          "desc": "内网穿透",
          "link": "https://github.com/localtunnel/localtunnel",
          "name": "localtunnel"
        },
        {
          "desc": "端口扫描",
          "link": "https://github.com/baalexander/node-portscanner",
          "name": "portscanner"
        },
        {
          "desc": "七牛云储存",
          "link": "https://github.com/qiniu/nodejs-sdk",
          "name": "qiniu"
        },
        {
          "desc": "HTTP请求",
          "link": "https://github.com/request/request",
          "name": "request"
        },
        {
          "desc": "HTTP请求(Promise)",
          "link": "https://github.com/request/request-promise-native",
          "name": "request-promise-native"
        },
        {
          "desc": "文件传输",
          "link": "https://github.com/spmjs/node-scp2",
          "name": "scp2"
        },
        {
          "desc": "文件传输",
          "link": "https://github.com/mscdex/ssh2",
          "name": "ssh2"
        },
        {
          "desc": "NPM私有仓库",
          "link": "https://github.com/verdaccio/verdaccio",
          "name": "verdaccio"
        }
      ],
      "样式": [
        {
          "desc": "图标",
          "link": "https://github.com/sindresorhus/figures",
          "name": "figures"
        },
        {
          "desc": "图标",
          "link": "https://github.com/peerigon/unicons",
          "name": "unicons"
        }
      ],
      "界面": [
        {
          "desc": "面板",
          "link": "https://github.com/chjj/blessed",
          "name": "blessed"
        },
        {
          "desc": "面板(升级版)",
          "link": "https://github.com/yaronn/blessed-contrib",
          "name": "blessed-contrib"
        },
        {
          "desc": "盒子",
          "link": "https://github.com/sindresorhus/boxen",
          "name": "boxen"
        },
        {
          "desc": "表格(升级版)",
          "link": "https://github.com/keymetrics/cli-table-redemption",
          "name": "cli-table-redemption"
        },
        {
          "desc": "表格",
          "link": "https://github.com/Automattic/cli-table",
          "name": "cli-table1"
        },
        {
          "desc": "表格",
          "link": "https://github.com/jamestalmage/cli-table2",
          "name": "cli-table2"
        },
        {
          "desc": "表格",
          "link": "https://github.com/cli-table/cli-table3",
          "name": "cli-table3"
        },
        {
          "desc": "终端宽度",
          "link": "https://github.com/knownasilya/cli-width",
          "name": "cli-width"
        },
        {
          "desc": "表格",
          "link": "https://github.com/eldargab/easy-table",
          "name": "easy-table"
        },
        {
          "desc": "加载动画",
          "link": "https://github.com/sindresorhus/ora",
          "name": "ora"
        },
        {
          "desc": "进度条",
          "link": "https://github.com/visionmedia/node-progress",
          "name": "progress"
        }
      ],
      "文本": [
        {
          "desc": "文本对齐方式",
          "link": "https://github.com/nexdrew/ansi-align",
          "name": "ansi-align"
        },
        {
          "desc": "文本颜色",
          "link": "https://github.com/chalk/chalk",
          "name": "chalk"
        },
        {
          "desc": "文本颜色动画",
          "link": "https://github.com/bokub/chalk-animation",
          "name": "chalk-animation"
        },
        {
          "desc": "文本颜色强调",
          "link": "https://github.com/LitoMore/chalk-pipe",
          "name": "chalk-pipe"
        },
        {
          "desc": "版本解析",
          "link": "https://github.com/npm/node-semver",
          "name": "semver"
        },
        {
          "desc": "字符截断",
          "link": "https://github.com/keenwon/string-break",
          "name": "string-break"
        },
        {
          "desc": "字符宽度",
          "link": "https://github.com/sindresorhus/string-width",
          "name": "string-width"
        },
        {
          "desc": "颜色支持检测",
          "link": "https://github.com/chalk/supports-color",
          "name": "supports-color"
        },
        {
          "desc": "谷歌翻译",
          "link": "https://github.com/googleapis/nodejs-translate",
          "name": "translate"
        }
      ],
      "调试": [
        {
          "desc": "调试日志",
          "link": "https://github.com/visionmedia/debug",
          "name": "debug"
        },
        {
          "desc": "变量检查",
          "link": "https://github.com/ziishaned/dumper.js",
          "name": "dumper"
        },
        {
          "desc": "断点调试",
          "link": "https://github.com/GoogleChromeLabs/ndb",
          "name": "ndb"
        },
        {
          "desc": "Webpack参数校验",
          "link": "https://github.com/webpack/schema-utils",
          "name": "schema-utils"
        }
      ]
    }
  }
}

{
  "result": [
    {
      "desc": "在线编辑器",
      "link": "https://studio.dev.tencent.com",
      "name": "CloudStudio"
    },
    {
      "desc": "在线编辑器",
      "link": "https://codepan.net",
      "name": "CodePan"
    },
    {
      "desc": "在线编辑器",
      "link": "https://codepen.io",
      "name": "CodePen"
    },
    {
      "desc": "在线编辑器",
      "link": "https://codesandbox.io",
      "name": "CodeSandbox"
    },
    {
      "desc": "在线编辑器",
      "link": "https://coding.net",
      "name": "Coding"
    },
    {
      "desc": "在线编辑器",
      "link": "https://stackblitz.com",
      "name": "StackBlitz"
    }
  ]
}

{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "正则校验",
      "link": "https://any86.github.io/any-rule",
      "name": "AnyRule"
    },
    {
      "desc": "浏览器兼容性",
      "link": "https://browserl.ist",
      "name": "BrowserList"
    },
    {
      "desc": "W3C标准",
      "link": "https://caniuse.com",
      "name": "Caniuse"
    },
    {
      "desc": "HTTPS配置",
      "link": "https://certbot.eff.org",
      "name": "Certbot"
    },
    {
      "desc": "变量定制",
      "link": "https://unbug.github.io/codelf",
      "name": "Codelf"
    },
    {
      "desc": "颜色搭配",
      "link": "https://www.colorgg.com",
      "name": "Colorgg"
    },
    {
      "desc": "CSS数据库",
      "link": "https://cssdb.org",
      "name": "CssDB"
    },
    {
      "desc": "CSS触发",
      "link": "https://csstriggers.com",
      "name": "CssTriggers"
    },
    {
      "desc": "贝塞尔曲线",
      "link": "https://cubic-bezier.com",
      "name": "CubicBezier"
    },
    {
      "desc": "运动曲线",
      "link": "https://easings.net",
      "name": "Easings"
    },
    {
      "desc": "编辑器配置",
      "link": "https://editorconfig.org",
      "name": "EditorConfig"
    },
    {
      "desc": "Flex布局",
      "link": "https://xluos.github.io/demo/flexbox",
      "name": "Flexbox"
    },
    {
      "desc": "Grid布局",
      "link": "https://grid.malven.co",
      "name": "Grid"
    },
    {
      "desc": "Material设计",
      "link": "https://material.io",
      "name": "MaterialDesign"
    },
    {
      "desc": "MD校验",
      "link": "https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn",
      "name": "MPE"
    },
    {
      "desc": "Nginx配置",
      "link": "https://nginxconfig.io",
      "name": "NginxConfig"
    },
    {
      "desc": "颜色搭配",
      "link": "https://paletton.com",
      "name": "Paletton"
    },
    {
      "desc": "颜色搜索",
      "link": "https://picular.co",
      "name": "Picular"
    },
    {
      "desc": "SSL分析",
      "link": "https://www.ssllabs.com/ssltest/analyze.html",
      "name": "SslLabs"
    },
    {
      "desc": "浏览器用户代理",
      "link": "http://www.useragents.com",
      "name": "UserAgents"
    },
    {
      "desc": "Vue编译器",
      "link": "https://vuejs-tips.github.io/compiler",
      "name": "VueTips"
    }
  ]
}

{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "代码截图",
      "link": "https://carbon.now.sh",
      "name": "Carbon"
    },
    {
      "desc": "CSS路径裁剪",
      "link": "https://bennettfeely.com/clippy",
      "name": "Clippy"
    },
    {
      "desc": "代码截图",
      "link": "https://codeimg.io",
      "name": "Codeimg"
    },
    {
      "desc": "CSS控件模型",
      "link": "https://qishaoxuan.github.io/css_tricks",
      "name": "CssTricks"
    },
    {
      "desc": "音乐模型",
      "link": "https://generative.fm",
      "name": "Generative"
    },
    {
      "desc": "图片水印",
      "link": "http://tool.c7sky.com/image-watermark",
      "name": "ImageWatermark"
    },
    {
      "desc": "加载图标",
      "link": "https://loading.io",
      "name": "Loading"
    },
    {
      "desc": "MD公式模型",
      "link": "https://www.mathcha.io",
      "name": "Mathcha"
    },
    {
      "desc": "加载图标",
      "link": "https://icons8.com/preloaders",
      "name": "Preloaders"
    },
    {
      "desc": "表格模型",
      "link": "https://www.tablesgenerator.com",
      "name": "TablesGenerator"
    }
  ]
}

{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "抽象语法树",
      "link": "https://astexplorer.net",
      "name": "AstExplorer"
    },
    {
      "desc": "CSS前缀补全",
      "link": "https://autoprefixer.github.io",
      "name": "Autoprefixer"
    },
    {
      "desc": "百度翻译",
      "link": "https://fanyi.baidu.com",
      "name": "BaiduTranslate"
    },
    {
      "desc": "JSON格式化",
      "link": "https://www.bejson.com",
      "name": "BeJson"
    },
    {
      "desc": "油管视频转码",
      "link": "https://www.clipconverter.cc",
      "name": "ClipConverter"
    },
    {
      "desc": "MD5解密",
      "link": "https://www.cmd5.com",
      "name": "Cmd5"
    },
    {
      "desc": "字体转换",
      "link": "https://www.fontke.com/tool/convfont",
      "name": "Convfont"
    },
    {
      "desc": "CSS-Sass转换",
      "link": "https://css2sass.herokuapp.com",
      "name": "Css2Sass"
    },
    {
      "desc": "CSS精灵图",
      "link": "https://www.toptal.com/developers/css/sprite-generator",
      "name": "CssSpritesGenerator"
    },
    {
      "desc": "二维码",
      "link": "https://cli.im",
      "name": "Forage"
    },
    {
      "desc": "HTML-JSX转换",
      "link": "https://magic.reactjs.net/htmltojsx.htm",
      "name": "Html2Jsx"
    },
    {
      "desc": "图标转换",
      "link": "https://www.easyicon.net/covert",
      "name": "Icovert"
    },
    {
      "desc": "JWT解密",
      "link": "https://jwt.io",
      "name": "Jwt"
    },
    {
      "desc": "MD-PDF转换",
      "link": "https://www.markdowntopdf.com",
      "name": "Markdown2Pdf"
    },
    {
      "desc": "MD-网页转换",
      "link": "https://mdnice.com",
      "name": "Mdnice"
    },
    {
      "desc": "二维码",
      "link": "https://www.wwei.cn",
      "name": "Wwei"
    },
    {
      "desc": "有道翻译",
      "link": "https://fanyi.youdao.com",
      "name": "YodoTranslate"
    }
  ]
}

{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "性能监控",
      "link": "https://fundebug.com",
      "name": "Fundebug"
    },
    {
      "desc": "网页加速",
      "link": "https://www.mipengine.org",
      "name": "MIP"
    },
    {
      "desc": "图片压缩",
      "link": "https://www.tuhaokuai.com",
      "name": "QuickPicture"
    },
    {
      "desc": "背景抠图",
      "link": "https://www.remove.bg",
      "name": "Remove"
    },
    {
      "desc": "图片压缩",
      "link": "https://shrinkme.app",
      "name": "ShrinkMe"
    },
    {
      "desc": "图片压缩",
      "link": "https://squoosh.app",
      "name": "Squoosh"
    },
    {
      "desc": "图片压缩",
      "link": "https://tinify.cn",
      "name": "Tinify"
    },
    {
      "desc": "图片压缩",
      "link": "https://tinyjpg.com",
      "name": "TinyJpg"
    },
    {
      "desc": "图片压缩",
      "link": "https://tinypng.com",
      "name": "TinyPng"
    },
    {
      "desc": "图片压缩",
      "link": "https://zhitu.isux.us",
      "name": "Zhitu"
    }
  ]
}

{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "CSS状态统计",
      "link": "https://cssstats.com",
      "name": "CssStats"
    },
    {
      "desc": "互联网数据统计",
      "link": "https://netmarketshare.com",
      "name": "Netmarketshare"
    },
    {
      "desc": "浏览器统计",
      "link": "https://gs.statcounter.com",
      "name": "StatCounter"
    },
    {
      "desc": "趋势统计",
      "link": "https://trends.google.com/trends",
      "name": "Trends"
    },
    {
      "desc": "独角兽公司统计",
      "link": "https://dujiaoshou.io",
      "name": "Unicorn"
    },
    {
      "desc": "W3C标准统计",
      "link": "https://www.w3counter.com",
      "name": "W3Counter"
    },
    {
      "desc": "网站技术统计",
      "link": "https://www.wappalyzer.com",
      "name": "Wappalyzer"
    }
  ]
}


{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "静态资源",
      "link": "https://www.bootcdn.cn",
      "name": "BootCdn"
    },
    {
      "desc": "静态资源",
      "link": "https://cdnjs.com",
      "name": "CDN"
    },
    {
      "desc": "Emoji表情",
      "link": "https://copychar.cc",
      "name": "CopyChar"
    },
    {
      "desc": "Emoji表情",
      "link": "http://www.emojipc.com",
      "name": "EmojiPc"
    },
    {
      "desc": "Emoji表情",
      "link": "https://emoji.muan.co",
      "name": "EmojiSearcher"
    },
    {
      "desc": "字体图标",
      "link": "https://icomoon.io",
      "name": "IcoMoon"
    },
    {
      "desc": "字体图标",
      "link": "https://www.iconfont.cn",
      "name": "IconFont"
    },
    {
      "desc": "字体图标",
      "link": "https://icons8.cn",
      "name": "Icons8"
    },
    {
      "desc": "静态资源",
      "link": "https://www.jsdelivr.com",
      "name": "JsDelivr"
    },
    {
      "desc": "占位图",
      "link": "https://placeholder.com",
      "name": "Placeholder"
    },
    {
      "desc": "图床",
      "link": "https://statically.io/imgpx",
      "name": "Statically"
    },
    {
      "desc": "自定义图标",
      "link": "https://shields.io",
      "name": "Shields"
    }
  ]
}


{
  "code": 200,
  "msg": "读取收藏列表成功",
  "result": [
    {
      "desc": "虚拟专用网络",
      "link": "https://www.ssgodie.win",
      "name": "Convenience"
    },
    {
      "desc": "模拟数据",
      "link": "https://easy-mock.com",
      "name": "EasyMock"
    },
    {
      "desc": "Node应用监控",
      "link": "https://keymetrics.io",
      "name": "Keymetrics"
    },
    {
      "desc": "在线MongoDB",
      "link": "https://mlab.com",
      "name": "MongoLab"
    },
    {
      "desc": "内网穿透",
      "link": "https://ngrok.com",
      "name": "Ngrok"
    },
    {
      "desc": "在线Photoshop",
      "link": "https://ps.gaoding.com",
      "name": "Photopea"
    },
    {
      "desc": "在线流程图",
      "link": "https://processon.com",
      "name": "ProcessOn"
    },
    {
      "desc": "内网穿透",
      "link": "https://www.ngrok.cc",
      "name": "SunnyNgrok"
    },
    {
      "desc": "在线Websocket",
      "link": "https://websocketd.com",
      "name": "Websocketd"
    }
  ]
}
```
