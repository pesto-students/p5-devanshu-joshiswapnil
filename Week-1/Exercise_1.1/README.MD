A)	MAIN FUNCTIONALITY OF THE BROWSER

A web browser, also known as a browser, is an application software that allows users to find, access, display, and view websites. Microsoft Internet Explorer, Google Chrome, Mozilla Firefox, and Apple Safari are all popular web browsers.

Web browsers are primarily used to display and access websites on the internet, as well as other content created with programming languages such as Hypertext Markup Language (HTML) and Extensible Markup Language (XML) (XML). Browsers convert Hypertext Transfer Protocol (HTTP) web pages and websites into human-readable content. They can also show other protocols and prefixes, such as secure HTTP (HTTPS), File Transfer Protocol (FTP), email handling (mailto:), and files (file:).

A web browser’s primary function is to render HTML, the code that is used to design or markup web pages. When a browser loads a web page, it processes the HTML, which may contain text, links, and references to images and other items like CSS and JavaScript functions. The browser then renders these objects in the browser window after processing them. A web browser (also known as a browser) is a software application that allows you to access information on the World Wide Web. When a user requests a web page from a specific website, the web browser requests the content from a web server and shows it on the user’s device.

B)	HIGH LEVEL COMPONENTS OF A BROWSER :

1. User Interface
It is an environment allowing users to use certain features like search bar, refresh button, menu, bookmarks, etc.

2. Browser Engine
The bridge connects the interface and the engine. It monitors the rendition engine while manipulating the inputs coming from multiple user interfaces.

3. Networking
The protocol provides an URL and manages all sorts of safety, privacy and communication.
In addition, the store network traffic gets saved in retrieved documents.

4. Data Storage
The cookies store information as the data store is an uniform layer that the browsers use. Storage processes like IndexedDB, WebSQL, localStorage, etc works well on browsers.

5. JavaScript Interpreter
It allows conversion of JavaScript code in a document and the executes it. Then the engine shows the translation on the screen to the users.

C)	RENDERING ENGINE AND ITS USE:

Role of Rendering Engine:
Once a user requests a particular document, the rendering engine starts fetching the content of the requested document. This is done via the networking layer. The rendering engine starts receiving the content of that specific document in chunks of 8 KBs from the networking layer. After this, the basic flow of the rendering engine begins.

Browser rendering engine
The four basic steps include:

The requested HTML page is parsed in chunks, including the external CSS files and in style elements, by the rendering engine. The HTML elements are then converted into DOM nodes to form a “content tree” or “DOM tree.”
Simultaneously, the browser also creates a render tree. This tree includes both the styling information as well as the visual instructions that define the order in which the elements will be displayed. The render tree ensures that the content is displayed in the desired order.
Further, the render tree goes through the layout process. When a render tree is created, the position or size values are not assigned. The entire process of calculating values for evaluating the desired position is called a layout process. In this process, every node is assigned the exact coordinates. This ensures that every node appears at an accurate position on the screen.
The final step is to paint the screen, wherein the render tree is traversed, and the renderer’s paint() method is invoked, which paints each node on the screen using the UI backend layer.
As discussed earlier, every browser has its own unique rendering engine. So naturally, every browser has its own way of interpreting web pages on a user’s screen.

D)	PARSERS (HTML, CSS, ETC) : 

The HTML content at the beginning which goes through a process called tokenization, tokenization is a common process in almost every programming language where code is split into several tokens which are easier to understand while parsing. This is where the HTML's parser understands which is the start and which is the end of the tag, which tag it is and what is inside the tag.

Now we know, html tag starts at the top and then the head tag starts before the html ends so we can figure out that the head is inside html and create a tree out of it.
Just like HTML, CSS goes through a similar process where we have the CSS text and then the tokenization of CSS to eventually create something called a CSSOM or CSS Object Model.

