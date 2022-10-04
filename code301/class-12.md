# REST status codes

1. 202 means 'Accepted'. This signifies that the request is valid but still processing. Sometimes used for async requests.
2. Permanent redirect
3. 204
4. 410
5. 403

# APIs

1. This is done for security of username and password.
2. Middleware is used to modify handler functions in Express and other web server libraries. It adds features to handlers like query string parsing, authentication, etc.
3. It is middleware that parses JSON and expects the content type to be JSON only.
4. It extracts a path as an id that can then be used to conditionally route the user to a page or return specific data based on that ID.
5. PUT will replace an entire dataset with the given values. PATCH is used to update particular fields in an existing dataset.
6. In your Mongo Schema definition (provided by Mongoose) you can specify a default in the object literal that defines the field name and data types, like so
````
new Schema({
foo: { type: String, default: 'bar' } 
})
````

7. Internal Server Error. This could be anything, from a client error that causes the server to return its own error to an offline server, etc.
8. 200 is success, and 201 is success plus a resource was created.
