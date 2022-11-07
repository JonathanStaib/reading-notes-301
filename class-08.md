# Class 08 Reading Notes

## API Design Best Practices

1. REST stands for Representational State Transfer

2. REST APIs are designed around resources. This can be any type of object or data or service that can be utilized by the client.

3. "https://hello.world/hithere/yay" could be an an example of a identifier.

4. The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

5. URIs should be based on nouns not the verbs, so the resource rather than the operations on the resource.

6. An example of an API could be if you go to code fellows website and type /catalog, it should come up with the code fellows catalog.

7. A chatty website API is something you should try to avoid. It is hard for the client to find the information that they are looking for and imposes a bigger load on the server.

8. A GET request will provide a status code of 200 OK if successful

9. A unsuccessful GET request will provide a 203 no content status code.

10. A POST request will provide a status code of 201 Created if successful.

11. A POST request will provide a status code of 400 bad request if unsuccessful.
