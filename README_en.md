![](https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1638187918372_20211129121158776024.png)

<p align="center"><b> <a href="./README.md"> 中文 </a> | English </b></p>

> This repository is Awesome of the Alibaba Cloud series by Serverless Devs, where you can view most of the Alibaba Cloud related components. In addition to the details in the main text below, you may also want to pay attention to:
> 1. [Combination of Serverless Devs and CICD](https://github.com/Serverless-Devs/Serverless-Devs/blob/master/docs/zh/cicd.md)
> 2. [Function Compute Component Documentation](https://github.com/devsapp/fc) and [Function Compute Quick Start Documentation](https://github.com/devsapp/start-fc)
> 3. [Serverless Application Engine (SAE) Documentation](https://github.com/devsapp/sae) and [Serverless Application Engine (SAE) Quick Start Documentation](https://github.com/devsapp/start- sae)
> For more cases and content, please refer to the following catalogue.

- [Hello World](#hello-world)
- [Web Framework application case](#web-framework-application-case)
- [Static website application case](#static-website-application-case)
- [Scene Collection](#scene-collection)
  - [AI scene](#ai-scene)
  - [Audio and video processing case](#audio-and-video-processing-case)
  - [Database usage under Serverless architecture](#database-usage-under-serverless-architecture)
  - [Others](#others)
    - [Activity scene](#activity-scene)

## Hello World

<table>
<tr>
<th>HTTP functions</th>
<th>Event function</th>
<th>Custom Runtime</th>
<th>Custom Container</th>
</tr>
<tr>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js6/src">fc-http-node.js6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js8/src">fc-http-node.js8</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js10/src">fc-http-node.js10</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js12/src">fc-http-node.js12</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-node.js14/src">fc-http-node.js14</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-php7.2/src">fc-http-php7.2</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-python2.7/src">fc-http-python2.7</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-python3.6/src">fc-http-python3.6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/http-function/fc-http-java8/src">fc-http-java8</a><br>
    <a href="https://github.com/devsapp/start-fc/blob/master/http-function/fc-event-golang1.x/src">fc-http-golang</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js6/src">fc-event-node.js6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js8/src">fc-event-node.js8</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js10/src">fc-event-node.js10</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js12/src">fc-event-node.js12</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-node.js14/src">fc-event-node.js14</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-php7.2/src">fc-event-php7.2</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-python2.7/src">fc-event-python2.7</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-python3.6/src">fc-event-python3.6</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/event-function/fc-event-java8/src">fc-event-java8</a><br>
    <a href="https://github.com/devsapp/start-fc/blob/master/event-function/fc-event-golang1.x/src">fc-event-golang</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/golang/fc-custom-golang-event/src">Golang Event function</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-function/golang/fc-custom-golang-websocket/src">Golang Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs10/fc-custom-nodejs10-event/src">Nodejs10 Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs10/fc-custom-nodejs10-websocket/src">Nodejs10 Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs12/fc-custom-nodejs12-event/src">Nodejs12 Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/nodejs12/fc-custom-nodejs12-websocket/src">Nodejs12 Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/php74/fc-custom-php74-event/src">PHP74-Swoole Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/php74/fc-custom-php74-http/src">PHP74-Swoole HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-event/src">Python37 Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-http/src">Python37 HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/python37/fc-custom-python37-websocket/src">Python37 Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/cpp/fc-custom-cpp-event/src">C++ Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/cpp/fc-custom-cpp-http/src">C++ HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/java8/fc-custom-java8-http/src">Java8-SpringBoot</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/ruby/fc-custom-ruby-event/src">Ruby example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/powershell/fc-custom-powershell-event/src">Powershell example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/f#/fc-custom-fsharp-http/src">F# example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/typescript/fc-custom-typescript-event/src">TypeScript example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/lua/fc-custom-lua-event/src">Lua example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/dart/fc-custom-dart-event/src">Dart example</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-function/rust/fc-custom-rust-event/src">Rust example</a>
</td>
<td align="center">
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-cpp/src">C++ Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-nodejs14/src">Node.js 14 Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-event-python3.9/src">Python3.9 Event function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-cpp/src">C++ HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-springboot/src">Springboot HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/tree/master/custom-container-function/fc-custom-container-http-aspdotnetcore/src">ASP.Net Core HTTP function</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-golang/src">Golang Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-nodejs14/src">Node.js14 Websocket function</a><br>
<a href="https://github.com/devsapp/start-fc/blob/master/custom-container-function/fc-custom-container-websocket-python3.9/src">Python3.9 Websocket function</a>
</td>
</tr>
</table>


## Web Framework application case

There are many ways to deploy a traditional framework to the Alibaba Cloud serverless platform. You can choose Custom, Custom Container, and the runtime of the native programming language. Among them, the Custom and native language runtime solutions are not very different except for the different startup commands/entry functions. They can be implemented according to their own needs. The Custom Container solution is relatively simple, but the cold start speed of the image is relatively high. and native language runtime is slower.

Currently, the Function Compute repository includes deployment cases for the following common frameworks:

<table>
<tr>
<th>No.</th>
<th>:fire:Nodejs</th>
<th>Python</th>
<th>PHP</th>
<th>Go</th>
<th>Java</th>
<th>Others</th>
</tr>
<tr>
<td align="center">1</td>
<td align="center">:fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/express/src">Express [custom]</a></td>
<td align="center">:fire::fire:<a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/flask/src"> Flask [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/thinkphp/src">Think PHP [custom]</a></td>
<td align="center">BeeGo</td>
<td align="center">Tomcat/Jetty</td>
<td align="center">Gatsby</td>
</tr>
<tr>
<td align="center">2</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/egg/src">Egg [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/tornado/src">Tornado [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/laravel/src">laravel [custom]</a></td>
<td align="center"><a href="https://github.com/liufangchen/start-gin">Gin [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/java/springboot">SpringBoot [custom]</a> </td>
<td align="center"><a href="https://github.com/liufangchen/start-hugo">Hugo [custom]</a> </td>
</tr>
<tr>
<td align="center">3</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/next/src">Nextjs [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/bottle/src">Bottle [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/discuz/src">Discuz [custom]</a></td><td></td><td align="center">Quarkus</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">4</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/nuxt-ssr/src">Nuxtjs [custom] </a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/webpy/src">Web.py [python3] </a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/wordpress/src" >WordPress [custom]</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">5</td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/hapi/ src" >Hapi [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/django/src" >Django [python3]</a></td>
<td align="center"> :fire::fire::fire: <a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/zblog/ src" >Zblog [custom]</a></td><td></td><td></td>
<td align="center"></td>
</tr>
<tr>
<td align="center">6</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/koa/src">Koa [custom]</a></td>
    <td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/fastapi/src" >FastAPI [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/ecshop/src" >Ecshop [custom]</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">7</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/nest/src">Nest [nodejs12]</a></td>
<td align="center">Web2py</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/metinfo/src" >Metinfo [custom]</a></td>
    <td></td><td></td><td></td>
</tr>
<tr>
<td align="center">8</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/midway-koa/src">Midway-koa [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/python/pyramid/src" >Pyramid [python3]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/whatsns/src" >Whatsns [custom]</a></td><td></td><td></td><td></td>
</tr>
<tr>
<td align="center">9</td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/thinkjs/src">Think.js [nodejs12] </a></td>
<td align="center"><a href="https://github.com/devsapp/Serverless-Baota" >Serverless-Baota [custom]</a></td>
<td align="center"><a href="https://github.com/devsapp/start-web-framework/tree/master/web-framework/php/typecho/src" >Typecho [custom]</a></td><td></td><td></td><td></td>
</tr>
    <tr>
<td align="center">9</td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><a href="https://github.com/devsapp/start-fc-kodbox" >Kodbox [custom]</a></td><td></td><td></td><td></td>
</tr>
</table>

> In addition to the above cases, two simple practical applications are provided:
> - [Express framework based todoList app](https://github.com/devsapp/start-web-framework/blob/master/example/todolist-app/src): `s init todolist-app`
> - [Django framework based blog application](https://github.com/devsapp/start-web-framework/blob/master/example/django-blog/src): `s init django-blog`  
    
> SSR frameworks
> - [nuxt-ssr](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/nuxt-ssr/src): `s init start-nuxt-ssr`

> In order to compare the framework migration differences between the Custom runtime and the programming language native runtime, you can refer to the following cases for your own comparison:
>
> | Framework name | Custom runtime | Node.js 12 runtime |
> | ----- | ----------- | ----------------|
> | Egg.js | [egg](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/egg/src) | [egg-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/egg/src) |
> | Express.js | [express](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/express/src) | [express-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/express/src) |
> | Koa.js | [koa](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/koa/src) | [koa-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/koa/src) |
> | Hapi.js | [hapi](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/custom-runtime/hapi/src) | [hapi-app](https://github.com/devsapp/start-web-framework/tree/master/web-framework/nodejs/nodejs-runtime/hapi/src) |


## Static website application case

- Static website case:
    - [hexo app](https://github.com/devsapp/start-website/tree/master/hexo/src) `s init website-hexo`
    - [docusaurus app](https://github.com/devsapp/start-website/tree/master/docusaurus/src) `s init website-docusaurus`
    - [vuepress app](https://github.com/devsapp/start-website/tree/master/vuepress/src) `s init website-vuepress`

> Of course, the static website cases listed above are all deployed to object storage after building, etc. You can also deploy directly to Function Compute (although this is not a recommended practice), you can refer to the [start-static-site documentation](https://github.com/devsapp/start-static-site) , you can also try to execute the command `s init start-static-site` to initialize

## Scene Collection

### AI scene

- [PyTorch case](https://github.com/devsapp/start-ai/tree/master/start-pytorch/src) `s init start-pytorch`
- [Tensorflow case](https://github.com/devsapp/start-ai/tree/master/start-tensorflow/src) `s init start-tensorflow`
- [OCR case](https://github.com/devsapp/start-ai/tree/master/start-ocr/src) `s init start-ocr`
- [Object detection case](https://github.com/devsapp/start-ai/tree/master/image-prediction-app/src) `s init image-prediction-app`

### Audio and video processing case

- [Flexible and highly available highly customized audio and video processing](https://github.com/devsapp/start-ffmpeg/tree/master/ffmpeg-app/src): `s init ffmpeg-app`
- [Apply to live video stream screenshot](https://github.com/devsapp/start-ffmpeg/tree/master/rtmp-snapshot/src): `s init rtmp-snapshot`
- [One-to-browser panorama recording](https://github.com/devsapp/start-ffmpeg/tree/master/headless-ffmpeg/src): `s init headless-ffmpeg`

### Database usage under Serverless architecture

- python case
    - [mysql case](https://github.com/devsapp/start-fc-db/tree/main/python/mysql/src): `s init start-fc-mysql-python`
    - [redis case](https://github.com/devsapp/start-fc-db/tree/main/python/redis/src): `s init start-fc-redis-python`
    - [mongodb case](https://github.com/devsapp/start-fc-db/tree/main/python/mongodb/src): `s init start-fc-mongodb-python`
    - [sql-server case](https://github.com/devsapp/start-fc-db/tree/main/python/sql_server/src): `s init start-fc-sql-server-python`
    - [postgresql case](https://github.com/devsapp/start-fc-db/tree/main/python/postgresql/src): `s init start-fc-postgresql-python`
    - [Lindorm case](https://github.com/devsapp/start-fc-db/tree/main/python/lindorm/src): `s init start-fc-lindorm-python`

### Others
- Screenshot web application based on puppeteer:
    - [Node.js-based case](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-nodejs/src): `s init puppeteer-nodejs`
    - [Container-based case](https://github.com/devsapp/start-puppeteer/tree/master/puppeteer-container/src): `s init puppeteer-container`
- [word to pdf application](https://github.com/devsapp/start-word2pdf): `s init start-word2pdf`
- [Application of pdf to image](https://github.com/devsapp/start-pdf2img): `s init start-pdf2img`
- [E-commerce backend management system](https://github.com/devsapp/start-fc-mall-admin): `s init start-fc-mall-admin`
- [Modern Application Solutions](https://github.com/devsapp/modern-web-application): `s init modern-web-application`

#### Activity scene

> This part records some small cases of activities, for learning purposes only

- [Red and white game based on function computing](https://github.com/devsapp/fc-nes-game): `s init fc-nes-game`
- [Function Computation Based Blindbox Game](https://github.com/devsapp/blindbox-game): `s init blindbox-game`
- [Creative Activities Jamsatck Site](https://github.com/devsapp/start-jamstack-activities): `s init start-jamstack-activities`
- [Barrage Application of Serverless Architecture](https://github.com/devsapp/start-barrage): `s init start-barrage`
