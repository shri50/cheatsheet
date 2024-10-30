# cheatsheet

📌 𝐂𝐨𝐫𝐞 𝐏𝐫𝐢𝐧𝐜𝐢𝐩𝐥𝐞𝐬
[1.] Client-Server
◾ Separation of concerns, clients request, servers respond.
[2.] Statelessness
◾ Each request is self-contained, no server-side client context.
[3.] Cacheability
◾ Responses can be cached for improved performance.
[4.] Layered System
◾ Components are independent and can be replaced without impacting the system.
[6.] Code on Demand (Optional)
◾ Servers can extend client functionality.
[7.] Uniform Interface
◾ Standardized interaction with resources -
- Unique URIs (Uniform Resource Identifiers).
- Actions on resources are performed through representations.
- Use hyperlinks in responses to guide clients.

📌 𝐇𝐓𝐓𝐏 𝐌𝐞𝐭𝐡𝐨𝐝𝐬
[1.] GET - Retrieve a resource.
[2.] POST - Create a new resource or submit data.
[3.] PUT - Update or replace an existing resource.
[4.] PATCH - Partially modify an existing resource.
[5.] DELETE - Delete a resource.
[6.] HEAD - Similar to GET, but only retrieves headers, not the body.
[8.] OPTIONS - Get information about the communication options for a resource.

📌 𝐒𝐭𝐚𝐭𝐮𝐬 𝐂𝐨𝐝𝐞𝐬
[1.] 2xx (Success)
◾ 200 OK: Request succeeded.
◾ 201 Created: Resource created successfully.
[2.] 3xx (Redirection)
◾ 301 Moved Permanently: Resource moved to a new URI.
◾ 304 Not Modified: Resource has not changed since last request.
[3.] 4xx (Client Error)
◾ 400 Bad Request: Invalid request syntax or parameters.
◾ 401 Unauthorized: Authentication required.
◾ 403 Forbidden: Insufficient permissions.
◾ 404 Not Found: Resource not found.
[4.] 5xx (Server Error)
◾ 500 Internal Server Error: Unexpected error on the server side.
◾ 503 Service Unavailable: Server temporarily overloaded or down for maintenance.

📌 𝐑𝐞𝐬𝐨𝐮𝐫𝐜𝐞 𝐍𝐚𝐦𝐢𝐧𝐠
◾ Nouns - Use nouns for resource names => /users, /products
◾ Plurals - Prefer plural nouns for collections => /users instead of /user
◾ Hyphens - Use hyphens to improve readability => /product-categories
◾ Lowercase - Use lowercase letters for consistency.

📌 𝐁𝐞𝐬𝐭 𝐏𝐫𝐚𝐜𝐭𝐢𝐜𝐞𝐬
[1.] Versioning
[2.] Filtering
[3.] Sorting
[4.] Pagination
[5.] Documentation
[6.] Content Negotiation
[7.] Idempotence
[8.] Caching

📌 𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲
[1.] Authentication (OAuth 2.0,JWT (JSON Web Tokens),API Keys)
[2.] Authorization (RBAC (Role-Based Access Control),ABAC (Attribute-Based Access Control))
[3.] Use HTTPS
[4.] Input Validation
[5.] Output Encoding
[6.] Rate Limiting and Throttling
[7.] CORS (Cross-Origin Resource Sharing)
[8.] Security Headers
[9.] Security Monitoring
