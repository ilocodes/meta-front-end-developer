# Introduction to HTTP
Have you noticed the lock icon next to the URL in your web browser? This indicates that HTTPS, the secure version of HTTP, is being used.

HTTP (Hypertext Transfer Protocol) is essential for the web, enabling your browser to communicate with web servers. It transfers web resources like HTML documents, images, and other files.

HTTP is a request-response protocol. Your browser sends an HTTP request to a server, and the server responds. Each request includes a method (GET, POST, PUT, DELETE), a path to the resource, a version, and headers. The method specifies the action: GET retrieves information, POST sends data, PUT updates, and DELETE removes resources. 

HTTP has multiple versions, with 1.1 and 2.0 being the most common. Headers provide additional information about the request, and some requests include a body with content sent by the client.

HTTP responses mirror the request format and include a status code (100-599) indicating the result. These codes are grouped:
- 100-199: Informational
- 200-299: Successful
- 300-399: Redirection
- 400-499: Client errors
- 500-599: Server errors

For example, 404 means "Not Found," and 500 means "Internal Server Error."

When you enter sensitive information like credit card details online, HTTPS ensures secure communication by encrypting the data, so only the intended recipient can decode it. This is indicated by the lock icon in your browser.

