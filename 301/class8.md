REST stands for Representational State Transfer.
REST APIs are designed around a client-server model, where the server provides resources that the client can access and manipulate.
An identifier of a resource is a unique string that identifies a specific resource. For example, in a REST API for a blog, the identifier of a blog post could be its slug or ID.
The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.
URIs should be based on the resources being accessed and manipulated.
A good URI should be descriptive, concise, and include only the necessary information to identify the resource being accessed or manipulated. For example, a URI for a blog post could be /blog/posts/1234.
Having a 'chatty' web API means that the API requires a large number of small requests to perform a single operation. This is generally considered a bad thing as it can negatively impact performance.
A successful GET request returns a status code of 200 OK.
An unsuccessful GET request returns a status code of 404 Not Found.
A successful POST request returns a status code of 201 Created.
A successful DELETE request returns a status code of 204 No Content.

Regex is a pattern matching language that allows you to search for, and manipulate strings of text.

Regex is composed of various characters that create a pattern to match against an input string.

Here are some common regex characters:
  - `.` : matches any single character except a newline
  - `*` : matches zero or more of the preceding character
  - `+` : matches one or more of the preceding character
  - `?` : matches zero or one of the preceding character
  - `^` : matches the start of a string
  - `$` : matches the end of a string
  - `[]` : matches a single character from the enclosed set of characters
  - `()` : groups characters together, and captures the matched characters
  - `|` : matches either the expression before or after the `|`

Regex can be used in many programming languages, text editors, and command line tools.

It is a powerful tool for searching and manipulating text, but can be difficult to learn and understand at first.
