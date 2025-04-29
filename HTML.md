<h1 align="center">HTML</h1>

<p>
  
  <li>HTML (HyperText Markup Language) was created by Tim Berners-Lee in 1991 </li>

  <li>HTML is like the skeleton of a website. It's a set of instructions that tells a web browser how to display text, images, videos, and other elements on a webpage. </li>

  <li>HTML file has extensions as ".html" or .htm"</li>

</p>
  <p>    
    <h2>What is Hyper-text ?</h2>
    <ul>
      <li>The term 'Hypertext Markup Language' is composed of two main words: 'hypertext' and 'markup language.' 'Hypertext' refers to the linking of text with other documents, while 'markup language' denotes a language that utilizes a specific set of tags.</li>  
    </ul>
  </p>

<p><h2>Features of HTML</h2>
  <ul>
    <li>It is platform-independent. For example, Chrome displays the same pages identically across different operating systems such as Mac, Linux, and Windows.</li>
    <li>Images, videos, and audio can be added to a web page (For example - YouTube shows videos on their website).</li>
    <li>HTML is a markup language and not a programming language.</li>
    <li>It can be integrated with other languages like CSS, JavaScript, etc. to show interactive (or dynamic) web pages.</li>
  </ul>
</p>

<h1>Let's have a look!</h1>
<ul>
  <li>Go to Google Chrome, open any website, and right-click on the webpage.</li>
  <li>Click on "Inspect".</li>
  <li>Now you will see the HTML code in the Elements section (Other sections are for JavaScript and CSS).</li>
    <p align="center">
      <img src="https://github.com/Aditya948351/Web_Dev/blob/main/uploads/Screenshot%202025-04-29%20194944.png?raw=true" alt="Inspect Screenshot" width="800"/>
    </p>
</ul>

<h2>Building a Website: HTML, CSS, and JavaScript</h2>
<ul>
  <li><strong>HTML:</strong> The skeleton of a webpage, forming the basic structure and frame.</li>
  <li><strong>CSS:</strong> Adds style and design, giving the webpage color, layout, and appeal.</li>
  <li><strong>JavaScript:</strong> Powers interactivity and dynamic content, like the engine of a car.</li>
</ul>

<h2>Lets start with installaing HTML Editor and Tools</h2>
<h3>HTML Editor</h3>
<p>HTML Editor is a tool where you write all your HTML content. You can use any text editor of your choice, but in this tutorial, we are using Visual Studio Code because it’s lightweight and open-source.</p>
<ul>
  <li><strong>Popular Editors:</strong> Notepad++, TextEdit, Sublime Text, Visual Studio Code, WebStorm, and Eclipse.</li>
</ul>

<h3>Installation of HTML Editor</h3>
<p>Follow the installation steps for the HTML editor of your choice. For this tutorial, we will be using Visual Studio Code, which is available for free download.</p>

<p>To get started with HTML development, download Visual Studio Code for your operating system. In this tutorial, I will show you how to install it on Windows, but the process is similar for other operating systems.</p>

<h3>Step-by-Step Guide</h3>
<ul>
  <li><strong>Step 1:</strong> Search for "Visual Studio Code download" on Google.</li>
  <li><strong>Step 2:</strong> Click on the official download link for Visual Studio Code.</li>
  <li><strong>Step 3:</strong> Visual Studio Code is available for multiple operating systems, including Windows, macOS, and Linux.</li>
  <li><strong>Step 4:</strong> Once downloaded, open the installer. This is the interface you will see after the installation is complete.</li>
</ul>

<p>Follow the prompts in the installer to complete the setup. Once installed, you can start writing HTML and other web development code.</p>

<ul>
  <p>also install this Extension to get live Preview of your HTML code in your visual code.</p>
  <p align="center">
    <img src="https://github.com/Aditya948351/Web_Dev/blob/main/uploads/Screenshot%202025-04-29%20203019.png?raw=true"/>
  </p>
</ul>

<h2>HTML Execution: Let's Create Our First HTML Program!</h2>
<p>Let’s mark this as an important milestone: the creation of your first website! And what’s a better way to start than with the traditional "Hello, World!"?</p>

<h3>Step-by-Step Guide</h3>
<ul>
  <li><strong>Step 1:</strong> Click on <strong>File</strong> and select <strong>New File</strong> in your editor.</li>
  <li><strong>Step 2:</strong> Save the file with a name ending in <strong>.html</strong> (for example, <strong>index.html</strong>).</li>
  <li><strong>Step 3:</strong> Create a folder on your Desktop and save the file there. This will create a workspace for your HTML files.</li>
  <li><strong>Step 4:</strong> Press <strong>Shift + 1</strong> to type the exclamation mark, and then press <strong>Enter</strong> to automatically generate the HTML boilerplate code in Visual Studio Code.</li>
</ul>

<p>Once these steps are done, you'll be ready to write your first HTML code!</p>



<h2>✅ Doctype Declaration</h2>

<pre><code>&lt;!DOCTYPE html&gt;</code></pre>

<ul>
  <li>Declares the version of HTML (currently HTML5).</li>
  <li>Helps browsers render the page correctly.</li>
  <li>Future-proofing: Useful if standards evolve over time.</li>
</ul>

<hr />

<h2>🔰 HTML Root Element</h2>

<pre><code>&lt;html&gt; ... &lt;/html&gt;</code></pre>

<ul>
  <li>The <code>&lt;html&gt;</code> tag is the root of every HTML document.</li>
  <li>It wraps all other content including head and body.</li>
</ul>

<hr />

<h2>🧠 Head Section</h2>

<pre><code>
&lt;head&gt;
  &lt;title&gt;Page Title&lt;/title&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;link rel="stylesheet" href="styles.css"&gt;
&lt;/head&gt;
</code></pre>

<ul>
  <li>Contains metadata and links to CSS/JS files.</li>
  <li>Essential for SEO and browser understanding.</li>
</ul>

<hr />

<h2>🏷️ Title Tag</h2>

<pre><code>&lt;title&gt;My Web Page&lt;/title&gt;</code></pre>

<ul>
  <li>Displays the page title in the browser tab.</li>
  <li>Important for user experience and search engines.</li>
</ul>

<hr />

<h2>🖼️ Body Section</h2>

<pre><code>
&lt;body&gt;
  &lt;h1&gt;Welcome&lt;/h1&gt;
  &lt;p&gt;This is where all visible content appears.&lt;/p&gt;
&lt;/body&gt;
</code></pre>

<ul>
  <li>Everything the user sees lives inside the <code>&lt;body&gt;</code> tag.</li>
  <li>Includes headings, paragraphs, images, buttons, etc.</li>
</ul>

<hr />

<h2>📌 Summary – Minimum Valid HTML Page</h2>

<pre><code>
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Sample Page&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Hello, World!&lt;/h1&gt;
  &lt;/body&gt;
&lt;/html&gt;
</code></pre>

<p>Every page should contain at least these elements to ensure proper structure and rendering across browsers.</p>

<hr />

<h3>🚀 Stay Semantic. Stay Professional.</h3>




