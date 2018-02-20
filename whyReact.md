# In your own words, explain single-page applications and progressive web apps.

* Single-page applications are web applications that load a single HTML page and update that page through AJAX as the user interacts with the app. This allows for the page to interact with the server through the AJAX calls and return the data in JSON format. The app will then use this data to update the page in dynamically without the need to reload/refresh the page. Facebook is a great example of this through comment updates, push notifications and the dynamic update nature of the website. 

* Progressive web apps take the idea of a web application a step further, and utilize certain criteria that must be satisfied so that your web application may be called a progressive web app, these criteria include: 
	* Use of service handlers to make the app available offline and load under bad network conditions (i.e. having a 2G EDGE connection in a developing country)
	* Must be responsive and fit into any for factor: desktop, tablet, mobile, etc..
	* Must be app-like, and exhibit the feel of an application through the use of an app shell model that separates the functionality from the application content.
	* Should always be up-to-date utilizing the service worker update process.
	* Must use HTTPS to prevent snooping and tampering.
	* Must be identifiable as an application by the search engine through W3C manifest and service worker registration scope.
	* Must be installable to the user by offering the ability to add the app to the users home screen without app store relay.
	* Must be easily sharable through URL download that does not require a complex installation. 
> Not all Single page applications strive to be progressive web apps. The use of the progressive web app model is highly dependent on the intentions of the application and the level of user interaction/notification. 

# Either from your research or by inspecting popular sites you frequent (using the Chrome DevTools), give some real-world examples of applications built with React and Angular.

* From my use of these websites, I have seen in the most non-scientific manner that the React sites tend to load and perform better than the Angular counterparts. I am also noticing that most of the websites that are geared towards more interaction and push notifications use React. 

React: Facebook, Instagram, Khan Academy, CodeAcademy, Yahoo Mail, AMC Theatres, Amazon Video, BBC, Airbnb, Netflix, Reddit, Uber.

Angular: Trello Dev, Autodesk, USPS tracking, Barnes & Noble, Citi, McDonald's, T-Mobile.

# Write a summary of the benefits of React vs. Angular. Then ask your mentor about the current state of web development, and ask questions about how they use these two popular technologies in their work.

## React
	* Slimmer and less prescriptive than Angular 2.
	* No dependency injection
	* Made MVC seem like obsolete tech & introduced unidirectional flow. 
	* Takes a barebones approach with "pick what you need" mentality.
	* JSX allows for mistakes to be caught at design time by linter or at compile time. You don't have to wait for runtime to catch errors. Many editors have built-in JSX support.
	* JSX allows to target more than just HTML: custom mark-ups, canvas and native mobile UI.
	* React Native, Materials UI, Next.js, MobX, Storybook
> React benefits come from the simplistic, barebones, yet modular nature of the framework. The fact that it is relatively easy to "jump in, and pick up" makes it a great choice for most. React Native is one of the best for mobile development, by enabling cross-platform development for Android, Windows, and iOS. Simply put, React has a lower entry barrier and a very helpful community.  

## Angular 2- **More of a learning curve**
	* Requires more tech buy in and a lot more boilerplate in apps. 
	* Way more modules come with Angular, and it take the philosophy of "batteries included".
	* Utilizes TypeScript for type correctness.
	* Dependency Injection-Objects dependencies are given to that object through telling the object what they are upon initiation, the dependencies are not stored in objects. This is what I understood after reading a good amount of convoluted articles. Dependencies are separated and are used as a framework that is not related to the object, but can be used on any object. 
	* Jasmine-testing that prints out terrible diffs from my current understanding. 
	* Large bundle that has (AOT) or Ahead of Time Compiling that needs to have the bundle configured properly to perform. 
	* Relies on HTML templates. 
	* AJAX 
	* Iconic 2, Material Design Components, Angular Universal, ngrx/store
> Angular 2 seems to have "everything you need, and more" and this all comes with the framework. Replacing modules is possible, however, this gets time consuming and complex. Angular 2 also has very in-depth documentation on the framework and will introduce many more new concepts that React. Anyone wanting to learn Angular should get comfortable with TypeScript. 


## Angular 2 && React
	* Both are very useful front-end frameworks. 
	* Both use data/state management of preference.
	* Both have a CLI tool. 
	* XSS protection
	* Utilities for unit-testing components
	* Both have their own routing and requests. 

