# vue-jd
- An interactive mockup of a mobile [web store](https://www.jd.com/)

## Front-End Structure
- Page structure: HTML5/CSS3/JS
- Framework: Vue 2.0
- Stage management pattern: Vuex
- Data processing framework: Axios
- Router: Vue-Router
- Image rendering: Vue-LazyLoad

## Server Structure
- Back-end development: Node.js
- Service settings/routing/processing: Express.js
- Database communications: MySQL
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

With MySQL database installed, open migou.sql

Use `npm` to install local server third-party framework (Requires [Node.js](https://nodejs.org/))

```
cd vue-jd
```

```
npm install or cnpm install
```

```
npm run dev
```

Next, open the back-end server

```
node server.js
```

## Menu Structure
<pre>
.
├── README.md           
├── libs               		// packages of common back-end tools' framework (formatting/MD5 encryption etc.)
├── route              		// back-end connection menu
├── server.js          		// back-end server settings file
├── webpack.config.js  		// webpack settings file
├── index.html         		// project entrance file
├── package.json       		// project settings file
├── src                		// production menu
│   ├── assets         		// css js and image source
│   ├── components     		// vue components
│   ├── store          		// vuex state manager
│   ├── App.vue        		// project panorama/Vue
│   ├── main.js        		// webpack editing entrance
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
