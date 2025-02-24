<h1>🛍️ Product Information API with Angular</h1>

<p>This is a comprehensive Product Information application built with ASP.NET Core for the backend and Angular for the frontend. This application allows users to manage product information with functionality for creating, reading, updating, and deleting product records.</p>

<h2>📑 Table of Contents</h2>
<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#technologies">Technologies</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#api-documentation">API Documentation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

<h2 id="features">🚀 Features</h2>
<ul>
  <li>Create, Read, Update, and Delete product records.</li>
  <li>Responsive user interface built with Angular.</li>
  <li>Integration with ASP.NET Core Web API for backend operations.</li>
  <li>Search and filter products by various attributes.</li>
  <li>Simple and clean code structure for easy understanding and maintenance.</li>
</ul>

<h2 id="technologies">🛠️ Technologies</h2>
<ul>
  <li><strong>Frontend:</strong> Angular, Bootstrap</li>
  <li><strong>Backend:</strong> ASP.NET Core Web API</li>
  <li><strong>Database:</strong> [Your choice of database, e.g., SQL Server, SQLite]</li>
  <li><strong>State Management:</strong> [e.g., Angular Services, NgRx, etc.]</li>
</ul>

<h2 id="getting-started">⚙️ Getting Started</h2>

<h3>🔧 Prerequisites</h3>
<p>Make sure you have the following installed:</p>
<ul>
  <li><a href="https://nodejs.org/" target="_blank">Node.js</a> (v12 or later)</li>
  <li><a href="https://dotnet.microsoft.com/download" target="_blank">ASP.NET Core SDK</a> (v3.1 or later)</li>
  <li>[Your choice of database]</li>
</ul>

<h3>📂 Clone the Repository</h3>
<pre><code>https://github.com/MdAshikur-Rahman-Ashik/Asp_Net_Core_Api_ProductsAPI_Information_ProAngular
</code></pre>

<h3>Frontend Setup</h3>
<ol>
  <li>Navigate to the Angular project directory:</li>
  <pre><code>cd Asp_Net_Core_Api_ProductsAPI_Information_ProAngular</code></pre>
  <li>Install the required packages:</li>
  <pre><code>npm install</code></pre>
  <li>Start the Angular application:</li>
  <pre><code>ng s</code></pre>
</ol>

<h3>Backend Setup</h3>
<ol>
  <li>Navigate to the ASP.NET Core Web API project directory:</li>
  <pre><code>cd Asp_Net_Core_Api_ProductsAPI_Information_ProAngular</code></pre>
  <li>Restore the dependencies:</li>
  <pre><code>dotnet restore</code></pre>
  <li>Update your database connection string in <code>appsettings.json</code>.</li>
  <li>Run the migrations (if any):</li>
  <pre><code>dotnet ef database update</code></pre>
  <li>Start the ASP.NET Core Web API:</li>
  <pre><code>dotnet run</code></pre>
</ol>

<h2 id="api-documentation">📄 API Documentation</h2>
<p>Refer to the API documentation in the backend repository to understand the endpoints available for CRUD operations. Here are some common endpoints:</p>
<ul>
  <li><code>GET /api/products</code> - Get all products.</li>
  <li><code>GET /api/products/{id}</code> - Get a specific product by ID.</li>
  <li><code>POST /api/products</code> - Create a new product record.</li>
  <li><code>PUT /api/products/{id}</code> - Update an existing product record.</li>
  <li><code>DELETE /api/products/{id}</code> - Delete a product record.</li>
</ul>

<h2 id="usage">💻 Usage</h2>
<p>Once both the frontend and backend servers are running, navigate to <a href="http://localhost:4200" target="_blank">http://localhost:4200</a> in your browser to access the Angular application. You can now create, read, update, and delete product records using the user interface.</p>

<h2 id="contributing">🤝 Contributing</h2>
<p>Contributions are welcome! If you have suggestions for improvements or want to report issues, please create an issue or submit a pull request.</p>

<h2 id="license">📝 License</h2>
<p>This project is licensed under the MIT License. See the <a href="LICENSE" target="_blank">LICENSE</a> file for more details.</p>


