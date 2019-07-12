# Jd.com Portable Web Store
- Vue2.0+Vuex+Axios+NodeJs+Express+MySQL

## Front-End Structure
- Page structure: HTML5, CSS3, JS
- Framework: Vue
- Data processing framework: Axios
- Router: Vue-Router
- Image rendering: Vue-LazyLoad

## Server Structure
- Back-end development: Nodejs
- Service settings/routing/processing: Express
- Database communications: Mysql
- Front-end receiver: Body-Parser
- Cookie & session processing: Cookie-Parser & Cookie-Session

## Web Store Features
1. Home page
2. Categories
3. Shopping cart
4. User profile
5. Sign-up
6. Login-in
7. Product details
8. Product search

## Installation

Installed MySQL database, insert migou.sql

Use `npm` to install local server third-party framework (Need [Node.js](https://nodejs.org/))

```
cd vue-jd
```

```
npm install or cnpm install
```

```
npm run dev
```

Open back-end server

```
node server.js
```

## Menu Structure
<pre>
.
├── README.md           
├── libs               		// packages of common back-end tools' framework (formatting/MD5 encryption etc.)
├── route              		// Back-end connection menu
├── server.js          		// Back-end server settings file
├── webpack.config.js  		// webpack settings file
├── index.html         		// Project entrance file
├── package.json       		// Project settings file
├── src                		// Production menu
│   ├── assets         		// css js and image source
│   ├── components     		// Vue components
│   ├── store          		// vuex state manager
│   ├── App.vue        		// Project panorama/Vue
│   ├── main.js        		// Webpack editing entrance
│   └── router.config.js    	// vue router settings file
</pre>

## Sample Screenshots

![](http://i.imgur.com/hc4Kdcv.png)

![](http://i.imgur.com/e1dli1Y.png)

![](http://i.imgur.com/j9bdh5O.png)

![](http://i.imgur.com/KNlLcjv.png)

![](http://i.imgur.com/m2H0mLg.png)

![](http://i.imgur.com/8GpE1qc.png)

![](http://i.imgur.com/sIfHd0z.png)
