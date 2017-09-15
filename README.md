# simple-nodejs-wiki-app

This is a simple nodejs wikipedia cmd app. It makes use of wikipedia api to fetch search strings when queried. 

<li> Run the app on the command line </li>
<pre><code> node index.js </code></pre>

it shows the content of the default search query, in this case English.

<li> Input Different word in the query variable to make it interactive </li>
This was done using yargs <pre><code> npm install yargs --save </code></pre>

Then run the app to search for different words like this: 
<pre><code> node index.js -q python </code></pre>

<p> A step by step tutorial on how this project was built can be found: <a href="https://medium.com/@atingenkay/node-js-build-a-simple-wikipedia-viewer-a5030322f5bb">Here</a> </p>
