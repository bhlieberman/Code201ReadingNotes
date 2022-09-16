# Reading 13

## Local storage

### Why would a developer use it?

Local storage enables persistence of data across events like page reloads. A user could enter some kind of input and this could be preserved even if the user navigates away from the page by using some manner of local storage. 

### What should not be stored?

Sensitive data like passwords shouldn't be cached using cookies or other browser-native interfaces because of security concerns.

### Strings

Local storage can only store stringified data. This means that if you pass in an object directly, if you try to read it back you will receive `[Object object]`. You can use the `JSON` API to convert the objects you want to store and retrieve to and from strings respectively. This is done using the `JSON.stringify` and `JSON.parse` methods.
