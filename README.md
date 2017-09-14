# simpleserver
Used file system modules to serve different pages.
This is a basic nodeJs project, Simple! First attempt.

Explanations: 

* var pathname = url.parse(request.url).pathname;
here, this will return the path name of the host followed by '/'; var uri = url.parse(https://nodejs.org/docs/latest/api/url.html).pathname
will return "/docs//latest/api/url.html"

* var fileName = path.join(process.cwd(), unescape(uri));
here, "process.cwd" returns the current working directory of the process. 
