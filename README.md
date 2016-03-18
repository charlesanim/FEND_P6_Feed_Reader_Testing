<h1>Feed Reader Testing - FEND Project 6</h1>
<h3>By: Charles Anim</h3>
<br/>
<h4>View Project</h4>
<hr>
<p>Follow the link to view the project: http://charlesanim.github.io/FEND_P6_Feed_Reader_Testing</p> <br/>
<br/>

<h4>How to run this locally</h4>
<hr>
<p>Option-1 - Simple:</p>
<ul>
	<li>Click "Clone in Desktop" / "Download ZIP"</li>
	<li>Open the folder</li>
	<li>Open `index.html` on your preferred browser</li>
	<li>There should be several test results at the bottom of the screen that says "~ specs, ~ failures"</li>
</ul>	

**Option-2 Using Terminal and Node.js**:
- **Pre-requisite** : Install [node.js](https://nodejs.org/),  [npm](http://blog.npmjs.org/post/85484771375/how-to-install-npm), and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Clone this repo. Open your terminal and run `git clone git@github.com:yhagio/udacity-feedreader-test.git`
- Install [http-server](https://www.npmjs.com/package/http-server) by `npm install -g http-server`
- Then run `http-server` in terminal inside the root of the cloned repo.
- Go to the URL **http://localhost:8080/** in browser.

<h4>Tests</h4> 
<hr>

<p>RSS Feeds:</p>
<ul>
	<li>Test feeds are defined</li>
	<li>Test feed URLs are defined and contain content</li>
	<li>Test feed names are defined and contain content</li>
</ul>
<p>Menu:</p>
<ul>
	<li>Test is hidden on page load</li>
	<li>Test menu icon appears on click</li>
</ul>
<p>First RSS Entry:</p>
<ul>
	<li>Test at least one entry displays on load after async call</li>
</ul>
<p>RSS Entry Change:</p>
<ul>
	<li>Test RSS entry changes on menu select</li>
</ul>
<br/>
<h4>Sources:</h4> 
<hr>
<p>http://jasmine.github.io/2.0/introduction.html</p>
<p>https://www.udacity.com/course/viewer#!/c-ud549-nd/l-3769099021/m-3868728773 (video course)</p>
