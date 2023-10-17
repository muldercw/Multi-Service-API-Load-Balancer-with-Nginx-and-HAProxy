
<h1>Multi-Service API Load Balancer</h1>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#customization">Customization</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="introduction">Introduction</h2>

<p>This repository provides a single Docker Compose configuration for setting up a multi-service API load balancer using Nginx, HAProxy, and Flask services. The included services enable efficient load balancing and CORS support for seamless API communication.</p>

<h2 id="prerequisites">Prerequisites</h2>

<p>Before getting started, ensure that you have the following software installed on your system:</p>
<ul>
    <li>Docker</li>
    <li>Docker Compose</li>
</ul>

<h2 id="usage">Usage</h2>

<ol>
    <li>Clone this repository to your local machine:</li>
    <pre><code>git clone repository-url</code></pre>
</ol>
<ol>
    <li>Navigate to the repository directory:</li>
    <pre><code>cd &lt;repository-directory&gt;</code></pre>
</ol>
<ol>
    <li>To launch the services, execute the following command:</li>
    <pre><code>docker-compose up</code></pre>
</ol>
<ol>
    <p>This command will start the Nginx, HAProxy, and three Flask API services. Nginx serves as the frontend, HAProxy handles load balancing, and Flask services simulate API endpoints.</p>
</ol>

<h2 id="accessing-the-services">Accessing the Services</h2>

<ul>
    <li><strong>Nginx (Frontend):</strong> Access the website at <a href="http://localhost">http://localhost</a>.</li>
    <li><strong>HAProxy (Load Balancer):</strong> Access the load balancer at <a href="http://localhost:8080">http://localhost:8080</a>.</li>
    <li><strong>Flask API Services:</strong> Access the API services at <a href="http://localhost:8001">http://localhost:8001</a>, <a href="http://localhost:8002">http://localhost:8002</a>, and <a href="http://localhost:8003">http://localhost:8003</a>.</li>
</ul>

<h2 id="customization">Customization</h2>

<p>You have the flexibility to customize the services and configurations by modifying the Docker Compose file and individual service configurations within this repository.</p>

<h2 id="contributing">Contributing</h2>

<p>We welcome contributions to this project. Feel free to open issues or submit pull requests. Your contributions are valuable and greatly appreciated!</p>

<h2 id="license">License</h2>

<p>This project is distributed under the <a href="LICENSE">GNU General Public License (GPL-3.0)</a>. Refer to the <a href="LICENSE">LICENSE</a> file for comprehensive details regarding the licensing terms.</p>

</body>

</html>
