---
title: 2.9. tp.web
---
# Web Module

This modules contains every internal function related to the web (making web requests).

- [[#Documentation]]
    - [[#tp.web.daily_quote()]]
    - [[#tp.web.random_picture(size?: string, query?: string, include_size?: boolean)]]
    - [[#tp.web.request(url: string, path?: string]]
- [[#Examples]]

## Documentation

Function documentation is using a specific syntax. More information [[Templater - Documentation (1.3. Syntax)#Function documentation syntax|here]].

### `tp.web.daily_quote()`

Retrieves and parses the daily quote from `https://github.com/Zachatoo/quotes-database` as a callout.
##### Examples

```javascript
// Daily quote
<% await tp.web.daily_quote() %>
```

### `tp.web.random_picture(size?: string, query?: string, include_size?: boolean)`

Gets a random image from `https://unsplash.com/`.
##### Arguments

- `size`: Image size in the format `<width>x<height>`.
    
- `query`: Limits selection to photos matching a search term. Multiple search terms can be passed separated by a comma.
    
- `include_size`: Optional argument to include the specified size in the image link markdown. Defaults to false.
##### Examples

```javascript
// Random picture
<% await tp.web.random_picture() %>
// Random picture with size
<% await tp.web.random_picture("200x200") %>
// Random picture with size and query
<% await tp.web.random_picture("200x200", "landscape,water") %>
```

### `tp.web.request(url: string, path?: string)`
Makes a HTTP request to the specified URL. Optionally, you can specify a path to extract specific data from the response.
##### Arguments

- `url`: The URL to which the HTTP request will be made.
    
- `path`: A path within the response JSON to extract specific data.
##### Examples

```javascript
// Simple request
<% await tp.web.request("https://jsonplaceholder.typicode.com/todos/1") %>
// Request with path
<% await tp.web.request("https://jsonplaceholder.typicode.com/todos", "0.title") %>
```
## Examples

```javascript
// Daily quote
<% await tp.web.daily_quote() %>

// Random picture
<% await tp.web.random_picture() %>
// Random picture with size
<% await tp.web.random_picture("200x200") %>
// Random picture with size and query
<% await tp.web.random_picture("200x200", "landscape,water") %>

// Simple request
<% await tp.web.request("https://jsonplaceholder.typicode.com/todos/1") %>
// Request with path
<% await tp.web.request("https://jsonplaceholder.typicode.com/todos", "0.title") %>
```

← Go to [[Templater - Documentation (2.8. tp.system)|previous page]] | Go to [[Templater - Documentation (2.10. Contributing)|next page]] →