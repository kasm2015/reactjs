<b><h2>Reactjs</h2></b>
This repository is created for the purpose learning ReactJS for beginners.

This project was bootstrapped with <a href="https://github.com/facebook/create-react-app">Create React App.</a>

<hr/>
<h2>Creating an App</h2>

<b>You’ll need to have Node 8.16.0 or Node 10.16.0 or later version on your local development machine</b> (but it’s not required on the server). You can use nvm (macOS/Linux) or nvm-windows to easily switch Node versions between different projects.

To create a new app, you may choose one of the following methods:
<br/>
<b>npx</b>

<div class="highlight highlight-source-shell"><pre>Syntax : npx create-react-app <i>name-of-your-react-app</i></pre></div>

<br/>

<div class="highlight highlight-source-shell"><pre>Example : npx create-react-app <i>my-first-react-app</i></pre></div>

<p>It will create a directory called <code>my-app</code> inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:</p>

<pre><code>my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
</code></pre>

<b><pre>Components: reusable pieces of React code to control part of the user interface. Components capture the structure of UI, and can have internal data to track the user behavior throughout the lifetime of the app.</pre></b>

<b><pre>State: dynamic data in a React component. This is often used to track variables that will be re-rendered in the UI based on events that occur in the application.</pre></b>

<b><pre>👉 Remember the React State Rule: Never Directly Modify State. Instead use the `this.setState` method.</pre></b>

<b><pre>Props: data in a React component that gets passed down from its parent. In the parent component, it will pass data down to the child component through attributes in the child component’s JSX.</pre></b>
