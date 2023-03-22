# Local Storage and How to Use It

## What is Local Storage?
- A way for web applications to store data locally within a user's browser
- Data stored in local storage remains persistent even when the browser is closed and reopened
- Supported in all modern browsers

## How to Use Local Storage
- Set an item: `localStorage.setItem("key", "value");`
- Get an item: `localStorage.getItem("key");`
- Remove an item: `localStorage.removeItem("key");`
- Clear all items: `localStorage.clear();`
- Note: Local storage only supports strings as values, so objects must be converted to strings before being stored

## Local Storage vs Cookies
- Local storage can store larger amounts of data than cookies
- Data stored in local storage is not sent to the server with every HTTP request, unlike cookies
- Local storage data can be accessed via JavaScript, while cookies can only be accessed via the server-side code
- Local storage is more secure than cookies, as it cannot be accessed by other domains or client-side scripts

---

# Dive Into HTML5: Storage

## What is Storage?
- Storage is a way for web pages to store named key/value pairs locally within a client's browser
- Two types of storage: Local Storage and Session Storage

## Local Storage
- Data stored in local storage remains persistent even when the browser is closed and reopened
- Can store up to 5-10 MB of data depending on the browser
- Accessed via the `localStorage` object

## Session Storage
- Data stored in session storage is lost when the browser is closed
- Accessed via the `sessionStorage` object

## How to Use Storage
- Set an item: `localStorage.setItem("key", "value");`
- Get an item: `localStorage.getItem("key");`
- Remove an item: `localStorage.removeItem("key");`
- Clear all items: `localStorage.clear();`
- Note: Local storage only supports strings as values, so objects must be converted to strings before being stored

## Browser Support
- Local storage and session storage are supported in all modern browsers, including mobile browsers
- Older browsers may not support these features
- Use Modernizr or similar libraries to detect browser support for storage

# Local Storage for Web Applications

- Why would a developer use local storage for a web application?
  - Local storage provides a way for web applications to store data locally within a user's browser, which can improve performance and user experience by reducing server requests and allowing for faster load times.
  
- What information should not be stored in local storage?
  - Local storage is not secure and should not be used to store sensitive information such as passwords, credit card details, or other confidential data. Additionally, large amounts of data should not be stored in local storage as it can slow down the performance of the web application.
  
- Local storage can store what type of data? How would you convert it to that type before storing?
  - Local storage can only store strings as values. To store other data types such as objects, they must be converted to strings using methods such as JSON.stringify() before being stored in local storage. When retrieving the data, it can be converted back to its original data type using methods such as JSON.parse().
