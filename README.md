## Part 1
1. What is HTTP?
    HTTP is Hypertext Transfer Protocol, and it's how browsers and servers communicate.
2. What is a URL?
    A URL is a Uniform Resource Locator, and it's used to retrieve resources on the web.
3. What is DNS?
    A DNS is a Domain Name System, which is a naming system that essentially allows for human-readable text names to be connected to IP addresses, allowing for easier traversal of the internet.
4. What is a query string?
    A query string occurs at the end of a URL. It appears as a '?' and then sends some parameters that then fetch a response.
5. What are two HTTP verbs and how are they different?
    GET and POST. GET is essentially a query that retrieves something, like markdown or data, and POST is how you write to a server for later retrieval.
6. What is an HTTP request?
    An HTTP request is a call to a server to retrieve some markdown, or data.
7. What is an HTTP response?
    An HTTP response is essentially a payload returned to the requestee, it does not occur in a vacuum, and is done in response to a request.
8. What is an HTTP header? Give a couple examples of request and response headers you have seen.
    An HTTP Header contains something you'd want to retrieve. You might request the Hostname you're looking for, or the data your browser thinks it is, or the language your browser wants info in. So you could request that information, then the response may contain some markdown or data from those requests.
9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    You perform a GET request for some headers to a server. The server does some internal work on its end, possibly retrieving some data from another server, for instance, before creating a response payload to send back.

## Part 2
1. Using curl, make a GET request to the icanhazdadjoke.com API to find all jokes involving the word “pirate”
    curl https://icanhazdadjoke.com/search?term=pirate
at does a pirate pay for his corn? A buccaneer!
What did the pirate say on his 80th birthday? Aye Matey!
Why couldn't the kid see the pirate movie? Because it was rated arrr!
Why do pirates not know the alphabet? They always get stuck at "C".
Why are pirates called pirates? Because they arrr!
2. Use dig to find what the IP address is for icanhazdadjoke.com
    dig icanhazdadjoke.com
3. Make a simple web page and serve it using python3 -m http.server. Visit the page in a browser.

