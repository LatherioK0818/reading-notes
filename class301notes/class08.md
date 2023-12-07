# API Design Best Practices - Reading Material

## Questions

1. **What does REST stand for?**
   - Representational State Transfer.

2. **REST APIs are designed around a ____.**
   - Stateless communication model.

3. **What is an identifier of a resource? Give an example.**
   - A Uniform Resource Identifier (URI) is used to identify a resource. Example: `https://api.example.com/users/123`.

4. **What are the most common HTTP verbs?**
   - GET, POST, PUT, DELETE.

5. **What should the URIs be based on?**
   - URIs should be based on the resources and not the actions.

6. **Give an example of a good URI.**
   - `https://api.example.com/products/electronics`.

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
   - A 'chatty' web API makes a large number of small requests. It's generally considered bad as it can lead to increased latency and network overhead.

8. **What status code does a successful GET request return?**
   - 200 OK.

9. **What status code does an unsuccessful GET request return?**
   - 404 Not Found.

10. **What status code does a successful POST request return?**
    - 201 Created.

11. **What status code does a successful DELETE request return?**
    - 204 No Content.

## Things I want to know more about


