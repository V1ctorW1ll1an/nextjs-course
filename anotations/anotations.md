# NextJs

## what is nextJs?

enables you to create full-stack Web applications, extending the latest React features

## what's in next?

### Built-in Optimizations

Next.js comes with a variety of built-in optimizations designed to improve your application's speed and Core Web Vitals

<ul>
  <li>[Images](https://image-component.nextjs.gallery/)</li>
  <li>[Fonts](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)</li>
  <li>[Scripts](https://nextjs.org/docs/app/building-your-application/optimizing/scripts)</li>
  <li>[Metadata](https://nextjs.org/docs/app/building-your-application/optimizing/metadata)</li>
  <li>[Static Assets](https://nextjs.org/docs/app/building-your-application/optimizing/static-assets)</li>
  <li>[Bundle analiser](https://nextjs.org/docs/app/building-your-application/optimizing/bundle-analyzer)</li>
  <li>[Lazy loading](https://nextjs.org/docs/app/building-your-application/optimizing/lazy-loading)</li>  
  <li>[Analytics (core web vitals) tools](https://nextjs.org/docs/app/building-your-application/optimizing/analytics)</li>
</ul>

### Dynamic

You can bring a lighter page with the content loading skeleton directly from the server and show it to the user while nextJs loads the content dynamically (you can do this with loading.js file).

consequences

(ux): users have a feedback about the page loading
(ux): users have a smoother experience

streaming

the first components are loaded earlier, not blocking the first painting on the user's screen, which means that the browser and server's priority is to first serve something for the user to see as quickly as possible and only then will it render the rest of the components down and load the js (if it exists) for interacting with the user

## Structure

<li>app: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.</li>
<li>/app/lib: Contains functions used in your application, such as reusable utility functions and data fetching functions.</li>
<li>/app/ui: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.</li>
<li>/public: Contains all the static assets for your application, such as images.</li>
<li>/scripts: Contains a seeding script that you'll use to populate your database in a later chapter.</li>
<li>Config Files: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.</li>

## Language

Typescript: Using TypeScript, you can ensure you don't accidentally pass the wrong data format to your components or database, like passing a string instead of a number to invoice amount.

## Create project and run enviroment

follow the oficial documentation

<li>How to add a global CSS file to your application.</li>
<li>How to add a global CSS file to your application.</li>
<li>How to conditionally add class names with the clsx utility package.</li>
