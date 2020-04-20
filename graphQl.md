# GraphQl Commands

## login/logout on GitHub

```bash




```

## show file tree 


```bash

GET /repos/:owner/:repo/contents/:path

```

## Push 

* **First Option**

The push command may not be implemented at the moment. I found a page that describes a way to implement it as an preview feature in the api but i dont know if it will fullfill our needs.

**Sources**

[GraphQl doc](https://developer.github.com/v4/object/push/)


* **Second Option**


```bash

PUT /repos/:owner/:repo/contents/:path

```

Thats the command to create or update a file.
But I'm not shure if it works like a push request.
In the response example a commit is createt so it seems to work similar but I can't see the differece between this command and the Push command above:

**Sources**

[GraphQL Create or Update a File](https://developer.github.com/v3/repos/contents/#create-or-update-a-file)
