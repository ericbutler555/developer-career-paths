# Developer Jobs and Career Paths

(as far as I know, and completely skewed by my own opinions)


## Web Developer

Two major forks here: **front-end** or **back-end.** Either can be all-encompassing and very deep dives, and both are vital roles with very bright job outlooks.

Personal opinion is that the industry has been steadily pushing more traditionally "back-end" things to the front-end: client-side web frameworks, serverless functions, cloud databases/APIs, static site generators (JAMstack) -- so front-end is getting harder/wider. This might plateau or reverse but who knows.

You are said to be "full-stack" if you are *regularly* responsible for handling both the browser-rendered (front-end) and server-processed (back-end) code of a website. Just having to do something on the front-end or back-end occasionally to finish the thing you're building on the other end doesn't (in my opinion) qualify as full-stack, but whatever.


### Front-end:

Two types of front-end: presentational (how it looks) and functional (what it can do). *Note these are my terms, not official ones.* A marketing site for a restaurant is mostly presentational (nice-looking, SEO-friendly and easy to read/navigate across devices); their online ordering system is mostly functional (lots of data manipulation adding items to an order, presenting options, handling customer info and payment, etc). Notice that most restaurant sites bounce to another domain to handle online ordering: different developers, different focus.

Lots of places expect that a front-end developer can handle both types, but they are very different skill-sets, primarily how well you know design/CSS vs. data/JS. Bigger/more tech-based companies might split these into different jobs.


#### Front-end Presentation: HTML, CSS, Design

Would focus on and be expected to have decent knowledge of:

- HTML:
  - Semantic markup
  - Accessibility
  - Search engine optimization (SEO)
- CSS:
  - Advanced layout: position, display, float, flex, grid
  - Advanced responsive design: media queries, scaling, collapsible and off-canvas patterns
  - CSS preprocessors: [Sass](https://sass-lang.com/), [Less](http://lesscss.org/), [PostCSS](https://postcss.org/)
  - CSS frameworks: [Bootstrap](https://getbootstrap.com/), [Tailwind](https://tailwindcss.com/), [Foundation](https://get.foundation/sites.html), [Bulma](https://bulma.io/), [Semantic UI](https://semantic-ui.com/), [Materialize](https://materializecss.com/)
  - CSS organization: DRY principles, [BEM](http://getbem.com/introduction/), [SMACSS](http://smacss.com/)
- JS:
  - DOM manipulation
  - Fundamentals: objects, arrays, functions, selectors, loops, conditions
  - [jQuery](https://api.jquery.com/) - still very widely used despite not being "best-practice" anymore
  - API usage and client-side AJAX: jQuery, [Axios](https://github.com/axios/axios), fetch, JSON parsing
  - Cookies and localStorage
  - Front-end security: CORS, XSS, CSRF
- General:
  - Browser compatibility of CSS and JS - use [CanIUse](https://caniuse.com) as a reference
  - Page performance and optimization (Lighthouse)
  - HTML forms and client-side validation
  - Animation with CSS and JS: [Animate.css](https://animate.style), [Greensock](https://greensock.com/)
- CMS development:
  - CMS "themes" are mostly just CSS and JS, with some basic programming as needed
  - [WordPress](https://developer.wordpress.org/themes/) - gigantic ecosystem
  - [Shopify](https://shopify.dev/concepts/themes) - lots of growth here in the last couple years
  - Don't bother with Drupal, Joomla, Magento, etc unless you're forced to use them
- Design:
  - Prototyping: [InVision](https://www.invisionapp.com/), [Figma](https://www.figma.com/), [Sketch](https://www.sketch.com/), [Adobe XD](https://www.adobe.com/products/xd/details.html)
  - User experience and UI design principles
- Digital marketing:
  - Business goals: analytics, KPIs, sales funnels, conversions
  - Ad targeting
  - Privacy: GDPR, CCPA


#### Front-end Functionality: JavaScript Engineer

- Component-based development paradigm
  - JS fundamentals are only *table stakes* for understanding frameworks, it really is a new way to think about webpages and coding
- Front-end frameworks:
  - [React](https://reactjs.org/) - currently most popular, but requires lots of add-ons
  - [Vue](https://vuejs.org/) - leaner and many say is easier to learn
  - [Angular](https://angular.io/) (bleeds into back-end) - heavy but everything built-in
  - [Svelte](https://svelte.dev/) - new and hot, but it's too soon to know if it'll stay relevant
  - **NOT** [AngularJS (v1)](https://angularjs.org/) - this is dead and you don't want to work on legacy projects that kept it
- Languages:
  - ES6 (what you're learning)
  - [TypeScript](https://www.typescriptlang.org/) (basically JS with extra steps, can be confusing but useful)
  - JSX (a way to render HTML in JS)
  - probably lots more...
- CSS abstractions:
  - *JavaScript people tend to dislike CSS so they've bent it to their own designs* 😉
  - CSS-in-JS (various options with this concept)
  - [CSS Modules](https://github.com/css-modules/css-modules)
  - [styled-components](https://styled-components.com/)
  - Scoped CSS
- State management/data layer:
  - [Redux](https://redux.js.org/) - popular but can be very complex, really only valuable for mega-complex data needs
  - [Redis](https://redis.io/) (in-memory storage cache)
  - [GraphQL](https://graphql.org/) - rising fast in popularity
- Developer tools:
  - Package managers: [NPM](https://www.npmjs.com/), [Yarn](https://yarnpkg.com/getting-started)
  - Build tools: [Webpack](https://webpack.js.org/), [Gulp](https://gulpjs.com/), [Grunt](https://gruntjs.com/)
  - Version control: [Git](https://git-scm.com/) (and using git as your deployment pipeline)


### Back-end:

The scope of back-end developer roles fluctuates, but at the very least it's writing code that runs on the server and handles logic based on how the user is interacting with the site. Things like logging into your account on a site and seeing personalized information, storing info submitted through a contact form, or returning search results based on a keyword, are all website functions that require a back-end, even if it's "in the cloud" -- that just means you don't personally host the back-end, it's a back-end somewhere else.

Back-ends might be a little less all-over-the-place than front-end: if your company has built everything in C#, they're not readily going to switch to PHP or Python unless it's for a very contained side-project. The transition cost is typically higher than front-end. So you can focus on just ONE of these languages/frameworks and be employable.

Popular back-end stuff is:

- Programming languages:
  - [Node](https://nodejs.org/en/about/) (back-end JavaScript) - a few years ago people predicted this would unseat every back-end language. then it didn't
  - [C#](https://docs.microsoft.com/en-us/dotnet/csharp/) - used for websites but also other types of development. not popular in small co's but preferred by many big co's. can be a steeper learning curve due to it being object-oriented and strongly-typed
  - [Python](https://www.python.org/) - more popular with coding bootcamps now, which may mean it'll become a top-of-mind option in a few years (note, historically for websites it's had slower performance than other languages)
  - [PHP](https://www.php.net/manual/en/) - still very widespread despite snobby attitudes about it
- Application frameworks:
  - [ASP.NET Core](https://dotnet.microsoft.com/apps/aspnet) (uses C#)
  - [Flask](https://flask.palletsprojects.com/en/1.1.x/) and [Django](https://www.djangoproject.com/) (use Python)
  - [Express](https://expressjs.com/) (uses Node/JS)
  - [Angular](https://angular.io/) (uses JS) - Angular is the only front-end framework that you can't "drop in" to your front-end, you have to build the whole site with it
  - [Laravel](https://laravel.com/) and [WordPress](https://developer.wordpress.org/) (use PHP) - plenty of dev careers exist entirely inside the WP ecosystem, building themes and plugins
  - [Ruby on Rails](https://rubyonrails.org/) (uses Ruby) - not as popular anymore but still good
- Database usage:
  - CRUD operations (create, read, update, and delete)
  - ORM syntax (abstracts SQL commands into code)
  - Security: server-side form validation, SQL injection, hashing and encryption, [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
- Architectural concepts:
  - OOP vs. procedural/functional
  - MVC paradigm
  - [JAMstack](https://jamstack.org/) - kind of an anti-back-end paradigm
  - SSR, CSR, SSG (server-side rendering, client-side rendering, static-site generation)
    - [Next JS](https://nextjs.org/) (built for React)
    - [Gatsby](https://www.gatsbyjs.org/) (built for React)
    - [Nuxt](https://nuxtjs.org/) (built for Vue)
    - [Jekyll](https://jekyllrb.com/) (uses Ruby to compile but mostly HTML and Markdown)
    - [Hugo](https://gohugo.io/) (uses Go)
- API creation:
  - Many APIs are just light abstractions that translate HTTP requests to database SQL queries, then return the db results to the requester as a JSON object
  - REST
  - [GraphQL](https://graphql.org/)
- Web server configuration: .htaccess, nginx.conf, web.config, etc.
  - Routing - translating URLs to files
  - 3rd-party dependencies/packages your code is built on
- Authentication and tokens - how to handle user accounts, permissions, and personalization
- Background jobs - separate heavy processing tasks (like email, file editing, etc) from simple page traffic
- Cron jobs and Task Scheduler - automate things that need to happen at a regular interval, like deleting the server cache every 24 hours or calling an API every morning at 5AM to get and store yesterday's sales figures in a database table
- Testing: test-driven development (TDD), unit tests, integration tests - some shops go all-in on writing code tests, others don't do any


### Mobile Developer:

Three paths here: iOS, Android, or hybrid. All have their own entirely separate programming languages, developer tools/coding environments, and coding paradigms. You could try more than one, but it seems like many devs are either one or the other.

Native development is ideal for maximum performance and the tightest integration with the device/operating system.

Hybrid development is interesting because you can write in JavaScript or a non-native language and have it transpile automatically into (mostly) native iOS/Android code -- which should give you high performance and the ability to use native features (like integrating the phone's camera or push notifications into your app).

- [Native iOS](https://developer.apple.com/documentation/): uses Swift (language) and Xcode (tool)
- [Native Android](https://developer.android.com/): uses Kotlin (language, a variant of Java) and Android Studio (tool)
- Hybrid or cross-platform apps:
  - [React Native](https://reactnative.dev/): integrates with React JS - very popular
  - [Flutter](https://flutter.dev/): language is called Dart - very high satisfaction rating
  - [NativeScript](https://nativescript.org/): integrates with Vue and Angular - not quite as popular
  - [Ionic](https://ionicframework.com/): is closer to website development but produces slightly less-performant apps


### Game Developer:

World-building, strategy, decisioning (if you do x, y happens), physics (how things move), graphics, sound design and probably a bunch of other things go into game development, and video games are an absolutely huge industry. I have heard it can be hard finding stable jobs in gaming but I don't know much at all about it.

- Frameworks:
  - [Unity](https://unity.com/) (uses C# and JS)
  - [Unreal Engine](https://www.unrealengine.com/en-US/) (uses C++)


### VR and AR Developer:

Augmented reality and virtual reality. I know very little about this, but Google, Apple, and Facebook are all still aggressively working on it so the ecosystem could open wide in the future.

- [ARCore](https://developers.google.com/ar) by Google
- [ARKit](https://developer.apple.com/augmented-reality/) by Apple
- [Oculus](https://developer.oculus.com/) owned by Facebook


### Software Engineer:

Developers don't all work on websites. Installed computer programs like Adobe Photoshop or VSCode are themselves worked on by developers. Sketch was created by a small team in the Netherlands and is now a frontrunner prototyping app. IoT devices -- wi-fi cameras, Ring doorbells, smart thermostats and even smart toothbrushes all have software both on the device itself and as part of a traditional back-end environment that the device sends data to via APIs.

- Desktop applications
  - [Electron](https://www.electronjs.org/) (tool to build desktop apps using HTML, CSS and JS)
  - C++
  - C#
- IoT "smart" devices (internet of things)
  - Java
  - C#
  - Python


### Data Science, Machine Learning, AI:

Honestly pretty far outside my comfort zone but these are definitely hurtling forward in very significant ways. Think of anything from improving voice recognition on Alexa devices to improving algorithms that recognize warning signs of cancer on a CT scan.

- Math-heavy
- Algorithms
- Data structures
- "Big Data"
- Languages:
  - Python
  - Java
  - R
- Tools:
  - [D3](https://d3js.org/) - graphics - see [example usage](https://observablehq.com/@d3/gallery)
  - [Tableau](https://www.tableau.com/) - data presentation
  - [TensorFlow](https://www.tensorflow.org/) - machine learning


### Database Architect (DBA):

Back-end developers *query* databases with their code, but especially in bigger companies, databases are built and maintained by dedicated database specialists.

- Types of databases:
  - Relational databases ([MySQL](https://www.mysql.com/), [SQL Server](https://www.microsoft.com/en-us/sql-server/), [PostgreSQL](https://www.postgresql.org/), [SQLite](https://www.sqlite.org/index.html))
    - Data is stored in tables with pre-defined fields (like an Excel spreadsheet)
  - NoSQL databases ([Mongo](https://www.mongodb.com/), [Firebase](https://firebase.google.com/products/firestore))
    - Data is stored as JSON-like objects, extra fields can be added to individual records on the fly
- Major considerations:
  - Performance (return data as quickly and with as little computing power as possible)
  - Data integrity (ensure the data is always dependable/true)
  - Database security and data privacy (prevent hacking, unauthorized access or changes)
  - Data migration (move or share data from place to place without corruption)
  - Data redundancy and loss prevention (set up automated backup procedures)
  - Stored procedures, triggers, etc. (write scripts and logic to make db queries programmatically)


### Systems Administrator:

Code has to live somewhere, like a server. There's a bunch of stuff to do to set up a server correctly for whatever the project is.

- Installing and maintaining server applications
- Types of web servers:
  - [IIS](https://www.iis.net/) (Windows only) - for C#/.NET dev, this is it
  - [Apache](https://httpd.apache.org/) - old trusty standard
  - [Nginx](https://docs.nginx.com/nginx/) - newer, trendier
- Hardware: RAM, etc.
- Virtualization (VMWare, VPS)
- Containerization:
  - [Docker](https://www.docker.com/)
  - [Kubernetes](https://kubernetes.io/)
- Email servers and SMTP
- Server security hardening
- Patching - bugs, version updates
- System logging and monitoring - detect if server is being overloaded or something's failing
- Command-line - SSH, Vim


### Network Engineer:

Work in an office environment or even decentralized setting where a group of people/computers share access to a common network.

- LAN (local area network)
- VPNs
- Intranet systems
- DNS
- Firewalls
- Load balancing (F5)
- Redundancy and failover


### DevOps Engineer:

Facilitates code releases to minimize downtime, bugs/errors, and human effort - through planning, establishing processes, and setting up software (and hardware) built for that purpose. DevOps continues to be a more common and more highly-valued part of the development process, especially at bigger companies that have complex codebases and various projects all happening concurrently.

- CI/CD (continuous integration/continuous deployment)
- Mirrored environments for development, staging, production
- Blue-green deployment
- Automation
- Monitoring
