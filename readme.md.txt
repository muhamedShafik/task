IntroductIon to Web development
● What is Web Development?
Web development is the process of building and maintaining websites or web applications that
you see and use on the internet.
It involves:
• Creating how the website looks (design and layout),
• Making it work properly (functions and features),
• Storing and managing data (like user info, products, etc.).
•
● Frontend vs. Backend vs. Fullstack
 Frontend Development (Client-Side)
• What the user sees and interacts with.
• Involves designing pages, buttons, forms, colors, fonts, etc.
• Main technologies used:
o HTML – structure of the page
o CSS – style and design
o JavaScript – interactivity
 Example: A shopping website’s product page and "Add to Cart" button.
 Backend Development (Server-Side)
• Works behind the scenes – not visible to users.
• Manages data, servers, and security.
• Processes requests like logging in, saving orders, or fetching data.
• Technologies used:
o Languages: PHP, Python, Java, Node.js
o Databases: MySQL, MongoDB
 Example: When you log in, backend checks your username and password.
 Fullstack Development
• A fullstack developer works on both frontend and backend.
• They can build complete websites or applications from start to finish.
● Web Development Lifecycle
This is the step-by-step process of making a website:
1. Plan
• Understand the purpose of the website.
• Decide what features are needed.
• Identify who will use it (target audience).
2. Design
• Create the look and feel of the website.
• Use tools like Figma or Adobe XD to make sample layouts (wireframes).
3. Develop
• Write the actual code using frontend and backend technologies.
• Connect the design with real functions.
4. Test
• Check for bugs, errors, or broken links.
• Make sure it works on different devices (mobile, desktop).
5. Deploy
• Publish the website on the internet using hosting services (like GoDaddy, Hostinger,
etc.).
• Make it live and available to users.
 ● Static vs. Dynamic Websites
Type Static Website Dynamic Website
Content Fixed; same for every visitor Changes depending on user or data
Speed Faster loading Slower than static but more functional
Cost Cheaper to build More expensive due to complexity
Uses Simple sites like portfolios or landing pages E-commerce sites, social media, blogs
Example A company "About Us" page Amazon, Facebook, YouTube
• Static Website: Like a printed book – same content for everyone.
• Dynamic Website: Like an app – changes based on who is using it.
HoW tHe Web Works
Client-Server Architecture
What is a Client?
• A client is any device or software (like a browser or mobile app) that requests
information from the internet.
• Examples:
o Web browsers like Chrome, Firefox, Safari
o Mobile apps like WhatsApp, Instagram, Facebook
What is a Server?
• A server is a computer that stores websites, data, and applications.
• It listens for client requests and responds with the needed information.
• Types of servers:
o Web Server – Stores and serves web pages
o Database Server – Stores and manages data (e.g., user info)
Real life example
Web Server = Front Counter
o Shows you the menu (website)
o Displays the cakes, pictures, and prices
o Handles your clicks (like “Order Now”)
o Database Server = Kitchen Records
o Stores secret recipes, customer orders, past sales
o When you click “Order Chocolate Cake”, the web server checks with the
database server:
o “Hey! Do we have Chocolate Cake available?”
o The database replies: “Yes, we have 5 left!”
Request-Response Cycle
• The client sends a request to the server.
• The server processes the request and sends back a response.
• Example: When you open www.google.com, your browser (client) requests the page,
and Google’s server sends it back.
IP Address & DNS
What is an IP Address?
• An IP (Internet Protocol) address is a unique number assigned to each device on the
internet.
• It works like a digital address so computers can find each other.
• Two types:
o IPv4 – Example: 192.168.1.1 -
o IPv6 – Example: 2001:0db8:85a3::8a2e:0370:7334 -
What is DNS (Domain Name System)?
• DNS converts domain names (like www.google.com) into IP addresses.
• This allows users to enter easy-to-remember names instead of numbers.
• Humans remember names (like www.google.com), but computers use IP addresses (like
142.250.190.36). DNS converts domain names into IP addresses so your computer
can connect to websites.
Real world example
Website name Contact name in your phone (e.g., "Mom")
IP address Phone number (e.g., "123-456-7890")
DNS server Your phone’s contact list (converts name → number)
Ping and Basic Network Commands
• Ping: A command to check if a server is reachable.
Ping is a tool used to check if a device like a website or computer is reachable over a
network. It works by sending a small packet of data from your device to another device
and waiting for a reply. The time it takes for this round trip is measured in milliseconds
and is called latency. Ping helps you see if a website or server is online, check how fast
your internet connection is, and troubleshoot network problems. For example, when
you ping google.com, your device sends a message and receives a reply showing how
many milliseconds the message took to travel back and forth. This information is useful
to understand the speed and reliability of your network connection.
o Example: ping google.com
• Other useful commands:.
o ipconfig (Windows) or ifconfig (Mac/Linux): Displays your computer’s current IP
address, subnet mask, and other network info.
HTTP/HTTPS
Request Methods
HTTP stands for HyperText Transfer Protocol and is the basic way web browsers and
servers communicate to load websites. When you enter a website address that starts
with "http://", your browser uses HTTP to request and receive web pages from the
server. However, HTTP does not encrypt the data being sent, which means information
like passwords or personal details can be seen by others if intercepted. Because of this,
many websites now use HTTPS, a secure version of HTTP that protects your data by
encrypting it.
Request Methods (GET, POST)
When your browser communicates with a website, it uses request methods to tell the
server what it wants to do. The two most common methods are GET and POST. A GET
request is used to ask the server for data, such as loading a webpage or searching for
something. In this method, the data is sent in the URL and is visible. On the other hand,
a POST request is used to send data to the server, such as when you submit a form. In
this case, the data is sent in the background and is not shown in the URL. While GET is
used mainly for viewing data, POST is used for sending or saving information. These
methods help browsers and servers understand what actions to perform.
Understanding URLs and Query Strings
• A URL is the address of a web page (e.g., https://www.example.com).
•
o A query string is used to send extra information to the server through the URL
o Example: https://example.com/search?q=shoes
o Here, q=shoes tells the server to search for “shoes”.
Why Use Query Strings?
• To search something
?q=shoes
• To filter products
? ?q=shoes
• To track user info (like page numbers, languages, etc.)
HTTP Status Codes
HTTP status codes are numbers that show the result of a website request. They tell you if a page
loaded successfully or if there was a problem.
Code Meaning
200 OK – The request was successful
404 Not Found – Page doesn’t exist
500 Internal Server Error – A problem on the server
HTTPS and SSL/TLS
HTTPS stands for HyperText Transfer Protocol Secure. It is the secure version of HTTP and is
used to safely send data between your browser and a website. HTTPS uses SSL/TLS (Secure
Sockets Layer / Transport Layer Security) to encrypt the data so that no one can read or steal it
while it travels over the internet. This keeps things like passwords, messages, and personal
details private and protected from hackers.
Summary Table
Term Meaning
Client Device/browser sending requests to the internet
Server Computer that responds with data
IP Address Unique address for devices on the internet
DNS Converts domain names to IP addresses
HTTP/HTTPS Protocols used for communication
GET/POST Request methods to get or send data
Term Meaning
Status Codes Messages from server (e.g., 200 OK, 404 Not Found)
SSL/TLS Security layers to encrypt data
 HoW broWsers Work (renderIng process)
Browser Rendering Process
When you open a website, your browser (like Chrome, Firefox, or Safari) follows several steps to
load and display the webpage. These steps are part of the rendering process. The Browser
Rendering Process refers to how a web browser converts HTML, CSS, JavaScript, and other
resources into a visual webpage that users interact with. This process involves several steps that
take place behind the scenes after a user enters a URL or clicks a link.
1. Fetching HTML, CSS, JavaScript
- The browser first downloads (fetches) all the files from the server.
- These files include:
 - HTML – The structure of the page- text, images, buttons
 - CSS – The style of the page- colors, fonts, spacing, layout, and responsiveness
 - JavaScript – The interactivity of the page - JavaScript adds life and interactivity to your
webpage.Making sliders, dropdowns, popups
Language Role in Webpage Example Use
HTML Structure & Content Text, images, buttons, links
CSS Style & Layout Colors, fonts, positioning, layout
JavaScript Interactivity & Behavior Click events, animations, form logic
2. Constructing the DOM and CSSOM Trees
DOM (Document Object Model): It’s a tree-like structure that the browser creates from your
HTML code.It represents everything on your webpage — text, images, buttons, paragraphs, etc.
- CSSOM (CSS Object Model): It’s a similar tree structure, but built from your CSS code.It tells
the browser how the page should look — colors, fonts, spacing, etc.
3. Creating the Render Tree
- The browser combines the DOM and CSSOM to create a Render Tree.
- The Render Tree contains only visible elements with their styles.
4. Painting, Repainting, and Reflowing
Painting:
- The browser draws the elements on the screen.
Repainting:
- Happens when only styles change (e.g., color or font).
Reflowing:
- Happens when layout or size changes. Slower and more performance-heavy.
Developer Tools Overview
Inspecting Elements, Console, and Network Tab
Modern web browsers like Chrome, Firefox, and Edge come with built-in Developer Tools that
help developers see how a webpage is built and how it behaves. One of the most used features
is the Elements tab, which allows you to inspect and interact with the structure of the webpage.
By right-clicking on any part of a website and choosing “Inspect,” you can view the underlying
HTML and CSS. This helps you understand the structure, see applied styles, and even try
changes live in the browser.
The Console tab is where you can see messages, errors, and logs related to the page’s
JavaScript. It’s also a space where you can run JavaScript code manually to test things. If a script
is broken or a button doesn’t work, the console will often show an error message explaining
what went wrong, making it a key tool for debugging.
The Network tab is used to monitor all the resources the page is loading, such as images,
scripts, and stylesheets. It shows you how long each file takes to load and whether any files
failed to load. This helps in identifying performance issues or broken network requests.
Source code: Source code refers to high-level code or assembly code that is generated
by humans/programmers. Source code is easy to read and modify. It is written by the
programmer by using any High-Level Language or Intermediate language which is
human-readable. The source code contains comments that the programmer makes for
better understanding.
Debugging: It is the process of identifying and resolving errors or bugs in a software
system. It’s a critical aspect of software development, ensuring quality, performance, and
user satisfaction on. Despite being me consuming, effective debugging is essential for
reliable and competitive software products.
Summary Table
Term Meaning
HTML, CSS, JS Core files the browser loads to build the
page
DOM Structure created from HTML
CSSOM Style structure created from CSS
Render Tree Combines DOM and CSSOM for visible
layout
Paint Draws elements on the screen
Repaint Changes appearance without layout
change
Reflow Changes layout and position – slower and
more costly
DevTools Tools inside the browser to inspect,
debug, and optimize websites
Inspect Element See and edit HTML/CSS in real-time
Console View JavaScript logs and errors
Network Tab Track file loading and server responses
understandIng tHe Webpage structure
What is the DOM?
DOM stands for Document Object Model.
• When a browser loads a webpage, it takes the HTML code and turns it into a tree-like
structure that the browser can understand and interact with.
• This structure is called the DOM Tree.
• The DOM is not just a visual thing — it's a model of the page's content that allows
browsers (and later JavaScript) to access and manipulate every element on the page.
• DOM stands for Document Object Model. It’s a tree-like structure that represents
everything on a web page — like headings, paragraphs, images, buttons, and more — in
a way that the browser and JavaScript can understand and interact with.
Real-Life Analogy of the DOM:
Think of a website as a house .
• The DOM is like the blueprint of the house.
• HTML is the structure (walls, rooms, doors).
• CSS is the paint and interior decoration.
• JavaScript is what makes things move or change (lights turning on, doors opening).
Now imagine you are a remote controller (JavaScript), and you can interact with the
house via its blueprint (DOM):
Tree Structure of HTML
The DOM organizes HTML elements in a tree format:
<html>
 <head>
 <title>My Website</title>
 </head>
 <body>
 <h1>Welcome</h1>
 <p>This is a paragraph.</p>
 </body>
</html>
The browser builds a tree from this like:
html
├── head
│ └── title
│ └── "My Website"
└── body
 ├── h1
 │ └── "Welcome"
 └── p
 └── "This is a paragraph.".
Parent-Child-Sibling Relationships
• Parent: A node that has one or more nodes inside it.
o Example: <html> is the root parent of the whole page.
• Child: A node that is inside another node.
o Example<head> and <body> are children of <html>
• Sibling: Nodes that share the same parent.
o Example: <h1> and <p> are children of <body> and also siblings.
Understanding these relationships is key to how web pages are structured and later
manipulated.
DOM Manipulation (Introduction)
• DOM manipulation means changing the content or structure of the web page using
programming (usually JavaScript).
• For example, JavaScript can:
o Add new elements to the page.
o Remove elements.
o Change the text inside an element.
o Change styles (like color or size).
We won’t go into the code yet, but just know: the DOM lets us control everything you see on a
webpage dynamically.
Basic Structure of a Webpage
Every HTML document starts with a basic structure that tells the browser what kind of
document it is and how to read it:
html
<!DOCTYPE html>
<html>
 <head>
 <title>My Webpage</title>
 </head>
 <body>
 <h1>Hello, world!</h1>
 <p>This is my first webpage.</p>
 </body>
</html>
 Explanation of Key Tags:
1. <!DOCTYPE html>
• Declares the document type and version of HTML (HTML5 here).
• Tells the browser: “This is an HTML document.”
• Must be the very first line of any HTML file.
2. <html> – Root Element
• The top-level element that wraps the entire HTML content.
• Every HTML page must have exactly one <html> element.
3. <head> – Metadata
• Contains information about the page, not shown on the screen.
• Examples:
o <title> – Sets the page’s title in the browser tab.
o <meta> – Describes page info (like character encoding).
o <link> – Connects to stylesheets.
o <script> – Links to JavaScript files (if any).
4. <body> – Page Content
• Contains everything you see on the webpage: text, images, buttons, videos, forms, etc.
• The main visible part of the page that users interact with.
 Summary Table
Tag Purpose
<!DOCTYPE html> Tells browser it's an HTML5 document
<html> Root element of the entire webpage
<head> Metadata: title, styles, scripts, meta info
<body> Visible content: text, images, links, etc.
DOM Tree model of HTML structure used by browser
Web tools and envIronment setup


Text Editors
Installing VS Code, Setting Up Extensions
- VS Code (Visual Studio Code) is a popular and free text editor for web development.
- Steps to install:
 1. Go to https://code.visualstudio.com/
 2. Download and install the version for your system (Windows/Mac/Linux).
- Recommended Extensions:
 - Prettier: Automatically formats your code.
 - Live Server: Opens your HTML file in a browser and reloads on changes.
Understanding File Structure and Folder Organization
- Organizing files and folders properly makes projects easier to manage.
- A typical web project structure:
 /project-folder
 ├── index.html
 ├── style.css
 ├── script.js
 └── /images
 └── logo.png
- Keep HTML, CSS, JavaScript, and images in separate folders for better clarity.
Command Line Basics
The command line (or terminal) lets you interact with your computer using text commands.
Navigating the File System (cd, ls, mkdir)
- cd: Change directory
 Example: cd Documents
- ls: List files and folders in the current directory
 Example: ls
- mkdir: Make a new folder
 Example: mkdir new-folder
Creating, Renaming, and Deleting Files (touch, rm)
- touch: Create a new file
 Example: touch index.html
- rm: Remove (delete) a file
 Example: rm index.html
Basic Commands (clear, pwd)
- clear: Clears the terminal screen
- pwd: Shows the current directory (print working directory)
 Example: /home/user/Documents
gIt and versIon control

What is Version Control?
Version control is a system that helps track and manage changes to files over time. It’s useful for
developers to collaborate, manage different versions, and go back to earlier stages if needed.
Why Version Control is Essential for Web Development
- Keeps track of all changes made to code
- Helps revert to previous versions if something goes wrong
- Makes collaboration easy with a team
- Organizes and manages the development workflow
Git vs. GitHub (Local vs. Remote Repositories)
- Git: A tool installed on your computer to manage code versioning locally.
- GitHub: An online platform where Git repositories can be stored and shared remotely.
- Git is for local tracking; GitHub is for collaboration and backup.
Installing and Setting Up Git
Basic Configuration
After installing Git, open your terminal or command prompt and set up your user details:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Creating a New Repository
To start tracking a project folder with Git, use:
git init
Basic Git Commands
Checking the Status
To check which files are changed or ready to commit:
git status
Adding Files to Staging
To prepare files for a commit:
git add .
Committing Changes
To save your changes:
git commit -m "Your commit message"
Viewing Commit History
To see a list of all previous commits:
git log
Working with GitHub
Creating a GitHub Account
- Visit https://github.com
- Sign up and create a new repository
Pushing a Repository to GitHub
To connect your local Git project to GitHub:
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
Cloning a Repository
To download a GitHub repository to your computer:
git clone https://github.com/username/repo.git
Pulling Updates
To get the latest changes from GitHub:
git pull
basIc Web desIgn concepts

Wireframing: Creating a Simple Layout Sketch
Wireframing is the process of creating a basic outline or blueprint of a webpage layout before
designing it. It focuses on structure and placement of elements like headers, images, buttons,
and text.
Box Model Concept: Content, Padding, Border, Margin
The Box Model is a fundamental concept in web design. Every element on a webpage is
considered a rectangular box composed of:
- Content: The actual text or image.
- Padding: Space around the content.
- Border: A line surrounding the padding (optional).
- Margin: Space between this element and other elements.
Color and Typography Basics
Color Schemes:
- Primary colors: Main brand or theme colors.
- Secondary colors: Support the primary colors.
- Accent colors: Used for emphasis (e.g., buttons, highlights).
Fonts and Readability:
- Serif fonts (e.g., Times New Roman): Good for print.
- Sans-serif fonts (e.g., Arial): Clean and easier to read on screens.
Responsive Design
Why Mobile-First Approach?
- Most users access the web on mobile devices first.
- Designing for smaller screens ensures better adaptability.
Basics of Media Queries (Just the Concept):
- Media queries allow designs to adjust based on screen size.
- They help create layouts that look good on all devices (mobile, tablet, desktop).

