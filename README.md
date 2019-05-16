# Portfolio Website Ver2
The second version of my portfolio website

## Table of Contents
1. <b>[Setup](https://github.com/cmdlhz/portfolio_website_ver2#1-setup)</b>
2. <b>[Run the Server](https://github.com/cmdlhz/portfolio_website_ver2#2-run-the-server)</b>
3. <b>[Work](https://github.com/cmdlhz/portfolio_website_ver2#3-work)</b>
4. <b>[Writings](https://github.com/cmdlhz/portfolio_website_ver2#4-writings)</b>
5. <b>[About](https://github.com/cmdlhz/portfolio_website_ver2#5-about)</b>
6. <b>[Account](https://github.com/cmdlhz/portfolio_website_ver2#6-account)</b>
7. <b>[Main Page](https://github.com/cmdlhz/portfolio_website_ver2#7-account)</b>
8. <b>[Navigation](https://github.com/cmdlhz/portfolio_website_ver2#8-navigation)</b>
9. <b>[General](https://github.com/cmdlhz/portfolio_website_ver2#9-general)</b>
10. <b>[Useful Info](https://github.com/cmdlhz/portfolio_website_ver2#10-useful-info)</b>
    - 10.1. [GitHub README Markdown : Useful Techniques](https://github.com/cmdlhz/portfolio_website_ver2#10-github-markdown--useful-techniques)
11. <b>[References](https://github.com/cmdlhz/portfolio_website_ver2#11-references)</b>
    - 11.1. [Front-end](https://github.com/cmdlhz/portfolio_website_ver2#111-front-end) : [Overall](https://github.com/cmdlhz/portfolio_website_ver2#overall) / [CSS](https://github.com/cmdlhz/portfolio_website_ver2#css) / [JS](https://github.com/cmdlhz/portfolio_website_ver2#js) / [Vue](https://github.com/cmdlhz/portfolio_website_ver2#vue) / [Etc](https://github.com/cmdlhz/portfolio_website_ver2#etc)
    - 11.2. [Back-end](https://github.com/cmdlhz/portfolio_website_ver2#112-back-end)
    - 11.3. [DB](https://github.com/cmdlhz/portfolio_website_ver2#113-db)
    - 11.4. [Design](https://github.com/cmdlhz/portfolio_website_ver2#114-design)
    - 11.5. [Etc](https://github.com/cmdlhz/portfolio_website_ver2#115-etc)
    - 11.6. [Inspirations](https://github.com/cmdlhz/portfolio_website_ver2#116-inspirations)
12. <b>[Built With](https://github.com/cmdlhz/portfolio_website_ver2#12-built-with)</b>
13. <b>[Blog Posts](https://github.com/cmdlhz/portfolio_website_ver2#13-blog-posts)</b>
14. <b>[Coming Up](https://github.com/cmdlhz/portfolio_website_ver2#14-coming-up)</b>
15. <b>[Contributing](https://github.com/cmdlhz/portfolio_website_ver2#15-contributing)</b>
16. <b>[License](https://github.com/cmdlhz/portfolio_website_ver2#16-license)</b>
- - -

# 1. Setup 
## 1-1. Backend - Server
* Created a virtual environment.
  - Ran `pyenv virtualenv useful_tips` in terminal.
* Activated the virtual environment.
  - Ran `pyenv activate useful_tips` in terminal.
* Installed Django
  - Ran `pip install django` in terminal.
* Create the server
  - Ran `django-admin startproject server` in terminal.
* Freezed backend packages
  - Ran `pip freeze > requirements.txt` in terminal.
* Created the Tips App
  - Ran `django-admin startapp writings` in terminal.

## 1-2. Frontend - Client
* Install Vue through Vue CLI 3
  - Ran `vue create client` in terminal.
  - Manually selected options
    + Features : Babel, Progressive Web App (PWA) Support, Router, Vuex, CSS Pre-processor, Unit Testing
    + Use history mode for Router : Yes
    + Pick a CSS pre-processor? : Sass/SCSS
    + Pick a linter / formatter config : ESLint with error prevention only
    + Pick additional lint features : Lint on Save
    + Pick a unit testing solution: Mocha + Chai
    + What do you prefer placing config? : In dedicated config files
* Installed Vuetify
  - Ran `vue add vuetify` in terminal.
    + Choose a preset? : Default (recommended)
      - The default preset has [a-la-carte](https://vuetifyjs.com/en/framework/a-la-carte) already enabled for you.
* High Vulnerability Issue : NPM Package `Tar`
  - Solved the issue by including code of `Tar` in package-lock.json with code in [this link](https://stackoverflow.com/a/55766169/10021131).

# 2. Run the server
* <b>Backend</b> : `pyenv activate useful_tips` - `python manage.py runserver`
* <b>Frontend</b> : `cd client` - `npm run serve`
- - - 

# 3. Work 
- - -

# 4. Writings 
- - -

# 5. About 
- - -

# 6. Account 
## 6.1. Sign Up Page

## 6.2. Log In Page

## 6.3. Account Page
- - -

# 7. Main Page
- - -

# 8. Navigation 
## 8.1. Header
### 8.1.1. ARIA 
[Accessible Rich Internet Applications (ARIA)](https://www.w3.org/TR/wai-aria-1.1/) is a set of attributes that define ways to make web content and web applications (especially those developed with JavaScript) more accessible to people with disabilities.
- Adding `aria-haspopup="true"` to the parent of the dropdown menu to indicates an alternative state.
- `aria-expanded="false"` & `aria-expanded="true"` shows that whether the alternative state is expanded or not.
- Including `aria-label="submenu"` on the actual dropdown menu itself shows that it's a submenu.


## 8.2. Footer
- - -

# 9. General 
## 9.1. MVC Pattern in Django
Django is using the MVC pattern. However, each component is called differently in Django.
* Model 
* View > Template (in Django)
* Controller > View (in Django)

## 9.2. Environment
Because I'm using Python/Django in the backend, I decided not to use [NuxtJS](https://nuxtjs.org/).
- "The default build of vue-server-renderer assumes a *Node.js* environment, which makes it unusable in alternative JavaScript environments such as [PHP V8Js](https://github.com/phpv8/v8js) or [Oracle Nashorn](https://docs.oracle.com/javase/8/docs/technotes/guides/scripting/nashorn/)." ([Vue SSR Guide](https://ssr.vuejs.org/guide/non-node.html))

- - -

# 10. Useful Info
## 10.1. GitHub README Markdown : Useful Techniques 
Please check out [this markdown](https://github.com/cmdlhz/SaferTrip_JL#61-github-markdown--useful-techniques).

## 10.2. Computer Science Fundamentals
- [List of CS courses online](https://github.com/prakhar1989/awesome-courses)
- - -

# 11. References 
## 11.1. Front-end
### Overall
* <b>Collections</b>
    - [Collection of Computer Programming (*in Korean*)](https://github.com/WeareSoft/archive)
* <b>Testing</b>
    - [HTML-CSS-JS](https://html-css-js.com/): An online tool collection of HTML, CSS, JS
    - GreenSock
        + [GreenSock Ease Visualizer](https://greensock.com/ease-visualizer): `Power 0-4`, `Back`, `Elastic`, `Bounce`, `Rough`, `SlowMo`, `Stepped`, `Circ`, `Expo`, `Sine`
    - [Regex 101](https://regex101.com/): a regular expression debugger 
* <b>Tutorials</b>
    - GreenSock
        + [GreenSock for Beginners](https://bit.ly/2IBc8la) on YouTube by [Petr Tichy](https://twitter.com/ihatetomatoes)
    - ScrollMagic
        + [ScrollMagic for Beginners](https://bit.ly/2IBc8la) on YouTube by [Petr Tichy](https://twitter.com/ihatetomatoes)

### CSS
* <b>Style Guide</b>
    - [Airbnb CSS-in-JavaScript Style Guide](https://github.com/airbnb/javascript/tree/master/css-in-javascript#airbnb-css-in-javascript-style-guide)
    - [Airbnb CSS / Sass Styleguide](https://github.com/airbnb/css#airbnb-css--sass-styleguide)
* <b>Testing</b>
    - [Cubic-bezier](http://cubic-bezier.com): A transition effect with variable speed from start to end
    - [Color Picker](https://www.w3schools.com/colors/colors_picker.asp): Comparing similar colors
* <b>Collections</b>
    - [30 Seconds of CSS](https://30-seconds.github.io/30-seconds-of-css/): A curated collection of useful CSS snippets
* <b>Tutorials</b>
    - [Flexbox Froggy](https://flexboxfroggy.com/): A game for learning CSS flexbox
    - [Grid Garden](http://cssgridgarden.com/): A game for learning CSS grid layout
    - [CSS Animation Tutorial Series](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iGYgmEd2dm3zAKzyCGDtM5) by [Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)
* <b>Blogs</b>
    - [Solved with CSS! Dropdown Menus](https://css-tricks.com/solved-with-css-dropdown-menus/)
    - [The CSS Handbook: a handy guide to CSS for developers](https://medium.freecodecamp.org/the-css-handbook-a-handy-guide-to-css-for-developers-b56695917d11)

### JS
* <b>Style Guide</b>
    - [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript#airbnb-javascript-style-guide-)
* <b>Tutorials</b>
    - [The Modern JavaScript Tutorial](https://javascript.info/)
        + [An Introduction](https://javascript.info/getting-started)
        + [JavaScript Fundamentals](https://javascript.info/first-steps)
        + [Code Quality](https://javascript.info/code-quality)
        + [Objects: The Basics](https://javascript.info/object-basics)
        + [Data Types](https://javascript.info/data-types)
        + [Advanced Working with Functions](https://javascript.info/advanced-functions)
        + [Object Properties Configuration](https://javascript.info/object-properties)
        + [Prototypes, Inheritance](https://javascript.info/prototypes)
        + [Classes](https://javascript.info/classes)
        + [Error Handling](https://javascript.info/error-handling)
        + [Promises, Async/Await](https://javascript.info/async)
        + [Generators, Advanced Iteration](https://javascript.info/generators-iterators)
        + [Modules](https://javascript.info/modules)
* <b>Collections</b>
    - [ES 6: New Features: Overview & Comparison](http://es6-features.org/#Constants)
* <b>Blog Posts</b>
    - [JavaScript ES2015 Classes and Prototype Inheritance](https://www.accelebrate.com/blog/javascript-es6-classes-and-prototype-inheritance-part-1-of-2/)
* <b>Theories</b>
    - [Details of the object model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model) : `Class`-based vs. `prototype`-based languages

### Vue
* <b>Collections</b>
    - [Awesome Vue](https://github.com/vuejs/awesome-vue) 
* <b>Blog Posts</b>
    - [React vs. Vue (vs. Angular)](https://medium.com/fundbox-engineering/react-vs-vue-vs-angular-163f1ae7be56) : Comparisons in "*Learning Curve*", "*Code Style*", "*Single File Components*", "*Performance*", "*Flexibility*", "*Tooling*", "*Mobile*", "*Community*", "*Maturity*", "*Support*", and "*Hiring Talent*" by Yogev Ahuvia on Jun 29, 2018
    - [26 Time Saving Tips for Vue](https://michaelnthiessen.com/26-time-saving-tips/) by Michael Thiessen in January 2019
    - [10 Chart.js example charts to get you started](https://tobiasahlin.com/blog/chartjs-charts-to-get-you-started/)
* <b>Tips</b>
    - [How to use various themes of icons from Google's Material Design in Vuetify](https://github.com/vuetifyjs/vuetify/issues/4164)

### Design
* <b>Practice</b>
    - [The Bézier curve](https://bezier.method.ac/) : A game for mastering the pen tool
* <b>Blog Posts</b>
    - [Behance vs Dribbble: The Ultimate Comparison](https://graphicmama.com/blog/behance-vs-dribbble-ultimate-comparison/)

### Etc..
* <b>Collections</b>
    - [Giphy](https://giphy.com/)
    - [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
    - [Google Fonts : Korean](https://googlefonts.github.io/korean/)
* <b>Blog Posts</b>
    - [How I landed a full stack developer job without a tech degree or work experience](http://bit.ly/2D06sl5) by [Charlie Jeppsson](https://github.com/charliejeppsson)
* <b>Plugins</b>
    - [New Moon](https://taniarascia.github.io/new-moon/) : the optimized dark theme including syntax highlighting for web development 
* <b>Git</b>
    - [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
    - [git — Rebase vs Merge](https://medium.com/datadriveninvestor/git-rebase-vs-merge-cc5199edd77c)
    - [How to revert a Git repository to a previous commit](https://stackoverflow.com/q/4114095/10021131)
    - [How to delete the preset configuration?](https://forum.vuejs.org/t/how-delete-the-preset-configuration/34526/2)

## 11.2. Back-end
* <b>Python</b>
    - [How to loop with indexes in Python](https://treyhunner.com/2016/04/how-to-loop-with-indexes-in-python/) by Trey Hunner on Apr 25, 2016.
* <b>NuxtJS</b>
    - [Vue SSR Guide](https://ssr.vuejs.org) by [VueJS](https://vuejs.org)
    - [The Complete Nuxt Guide](https://medium.com/@onlykiosk/the-complete-nuxt-guide-940751e1a6a5) by [OnlyKiosk Dev Tech](https://medium.com/@onlykiosk)

## 11.3. DB
* <b>Visualization</b>
    - [DrawSQL](https://drawsql.app/) : Create, visualize and collaborate on database entity relationship diagrams

## 11.4. Computer Science
* <b>Fundamentals</b>
    - [https://teachyourselfcs.com/](https://teachyourselfcs.com/)

## 11.4. Design
* <b>Figma</b>
    - [4 Figma Tips For Prototyping Like A Pro](https://trydesignlab.com/blog/4-figma-tips-prototype-like-a-pro-ux-ui-design/)

## 11.5. Etc
* <b>Setup</b>
  - [Simple Movies web app with Vue, Vuetify and Django. Part 1: Setup](https://medium.com/@samy_raps/simple-movies-web-app-with-vue-vuetify-and-django-part-1-setup-6351c02327a5)
* <b>Testing</b>
    - [Mocha](https://mochajs.org/), the core framework : It provides common testing functions including describe and it and the main function that runs tests.
    - [Chai](https://www.chaijs.com/) : the library with many assertions. It allows to use a lot of different assertions
* <b>Coding Challenges</b>
    - [The 10 Best Coding Challenge Websites for 2018](https://medium.com/coderbyte/the-10-best-coding-challenge-websites-for-2018-12b57645b654)
* <b>Online Code Editor</b>
    - [StackBlitz](https://stackblitz.com/)
    - [Code SandBox](https://codesandbox.io/)
* <b>Etc</b>
    - [Post Image](https://postimages.org/) : Get permanent links for images

## 11.6. Inspirations
* <b>Interactive Experience</b>
    - [Website Awwwards](https://www.awwwards.com/) : scores based on design, usability, creativity, content, and mobile
    - [Form Follows Function](http://fff.cmiscm.com/#!/main)
    - Bunts Spenden @ [website](http://buntspenden.bleech.de/en/)
        + [awwwards submission](https://www.awwwards.com/sites/buntspenden)
    - 12 Dishes @ [website](http://12dishes.com/)
        + [awwwards winner](https://www.awwwards.com/sites/around-the-world-in-12-dishes) of Jan 27, 2016.
        + [youtube explanation](https://youtu.be/Wu7OHhdqT0c)
    - [Fly Acts - Multi-channel App](https://www.flyacts.com/multi-channel-app/)

* <b>Portfolio Website</b>
    - [Ji-hoon Suh](https://jihoonsuh.com/)
    - [Jeremiah Shaw](http://www.jermshaw.com/)
    - [Derek Mei](https://www.derekmei.com/)
    - [nykim](https://gmlwjd9405.github.io/2018/05/04/how-to-write-a-resume-for-a-developer.html)

* <b>Programming Work</b>
    - [Tania Rascia](https://www.taniarascia.com/)
    - [José Manuel Pérez](https://jmperezperez.com/projects/)
- - -

# 12. Built With
* <b>Front End</b>
    - HTML
    - CSS
        + [Sass](https://sass-lang.com/)
        + [Animate CSS](https://daneden.github.io/animate.css/)
    - JavaScript
        + [GreenSock Animation Platform (GSAP)](https://greensock.com/gsap) : Professional-grade javascript animation for the modern web
        + [ScrollMagic](http://scrollmagic.io/) : Javascript library for magical scroll interactions
        + [AnimeJS](https://animejs.com/):  a lightweight JavaScript animation library
        + [HeadroomJS](https://wicky.nillia.ms/headroom.js/) : A JS widget that allows you to react to the user's scroll
        + [SweetAlert2](https://sweetalert2.github.io/) : A beautiful, responsive, customizable replacement for JavaScript's popup boxes
        + [PrismJS](https://prismjs.com/) : a lightweight, extensible syntax highlighter
    - [Vue](https://vuejs.org/)
        + [Vuetify](https://vuetifyjs.com/en/) : a material component framework for Vue apps
        + [VeeValidate](https://baianat.github.io/vee-validate/) : Template Based Validation Framework for Vue.js
        + [Vue ChartJS](https://vue-chartjs.org/) : Easy and beautiful charts with [Chart.js](https://www.chartjs.org/) and Vue.js
        + [chartjs-plugin-datalabels](https://chartjs-plugin-datalabels.netlify.com/) : Display labels on data for any type of charts
        + [Vue-Particles](https://vue-particles.netlify.com/) : Vue.js component for particles backgrounds

SSR compatible
* <b>Back End</b>
    - [Python](https://www.python.org/)
        + [Django](https://www.djangoproject.com/)
* <b>DB</b>
    - [MySQL](https://www.mysql.com/)
- - -

# 13. Blog Posts
- - -

# 14. Coming Up
I plan to learn the following:
* <b>Overall</b>
    - * [Web Developer Roadmap](https://github.com/cmdlhz/developer-roadmap)       
* <b>Front-end</b>
    - CSS
        + [Flexbox](https://flexbox.io/) by Wes Bos
        + [CSS Grid](https://cssgrid.io/) by Wes Bos
    - JavaScript
        + [30 Day Vanilla Coding Challenge](https://javascript30.com/) by Wes Bos | [GitHub](https://github.com/wesbos/JavaScript30) 
    - [TypeScript](https://www.typescriptlang.org/) : a typed superset of JavaScript that compiles to plain JavaScript
        + [TypeScript Basics](http://bit.ly/2Uc9PLx) by Java Brains
        + [Make a Blockchain by using TypeScript](https://academy.nomadcoders.co/p/build-a-blockchain-with-typescript) by Nomad Coders
    - [Vue Developer Roadmap](https://github.com/flaviocopes/vue-developer-roadmap)
* <b>DB</b>
    - [MongoDB](https://www.mongodb.com/) : a cross-platform document-oriented database program (<i>No SQL!</i>)
    - [PostgreSQL](https://www.postgresql.org/) :  a powerful, open source object-relational database system
* <b>Etc</b>
    - [VIM](https://www.vim.org/) : a text editor (<i>Force you to use only the keyboard!</i>)
- - -

# 15. Contributing
If you see any typos or formatting errors in the website, please do not hesitate to open a pull request and fix it! :)
- - -

# 16. License
This project is open source and available under the [MIT License](https://github.com/cmdlhz/portfolio_website_ver2/blob/master/LICENSE).
- - -

2019 © Jen Lim 