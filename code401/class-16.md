## Spring Security

### Authentication vs Authorization

Authentication is a check for _who_ the user is. Authorization tells the user what they are allowed to do. Authentication in Spring is handled by the `AuthenticationManager` class. Often, this class is subclassed by a `ProviderManager`, which is used to expose logical groups of resources to an authenticated user.

Once authentication is complete, authorization of various resources can occur. The general flow of a Spring Security-enabled app uses the concept of filters and servlets. Filters are somewhat like middleware: they wrap or handle requests before they arrive at the server (servlet), modifying their behavior or state or perhaps rejecting them entirely.