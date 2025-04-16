# Overview of Web Development

Topics covered for this unit:
- Different languages used for web development
- Define programming
- Software engineer purpose and summarization
- Difference between front-end and back-end engineering

## Internet Basics

### HTTP Status Codes

When a server responds to a client, it sends a code along with the response which indicates the status of the request. Whether the response succeeded, failed etc, each outcome will have a different status code. These status codes help the browser know how handle the data that was sent back with the response. 

These responses are grouped in five classes:
1. Informational responses (100-199)
2. Successful responses (200-299)
3. Redirection messages (300-399)
4. Client error responses (400-499)
5. Servor error responses (500-599)

Some familiar HTTP status codes might be:

| Code    | Explanation |
| --------| -------     |
| 200 OK                      | The request has succeeded   |
| 301 Moved Permanently       | The resource has been moved and the client is being redirected     |
| 404 Not Found               | The requested resource was not found   |
| 500 Internal Server Error   | The server encoundered an unexpected error    |


### How do browsers work?
When a request is made to a server for lets say a website, all of the following steps happen in a split second:

1. When a user types in a URL and presses enter, the server processes the request and sends the HTML file back to the client. HTML files hold the content of a website and they also contain links for any additional assets or code that are needed to display the site properly.
2. The browser will begin to search for elements in the HTML file and it will start to make additional HTTP requests for any other external resources used by the HTML file. 
This often includes:

  - One or more CSS stylesheets. CSS stands for cascading style sheets; CSS creates the style and layout of a web page. The browser will request the CSS stylesheet, and when the server sends it back, the browser analyzes the CSS and starts applying the visual styles to the content of the site.
  - The request-response cycle also sends website assets, like images and videos, from the server to the browser. If these files are large, there might even be a noticeable delay before they are rendered by the browser.
  - One or more JavaScript files. JavaScript makes the webpage interactive. This programming language functions as the “behavior” of the web page. A webpage that does not use JavaScript is known as a static webpage.
                                                                                    ==Codecademy==


## Web development

There are numerous languages that need to be known for web development. This section will briefly go over four of the main languages for web development and see what kind of features and skills come with them.

### HTML

As my tutor famously says, "HTML is like the skeleton" of all web pages.
HTML stands for hypertext markup language and provides the structure to all the content on a website, including text, images, buttons, videos, and more.


