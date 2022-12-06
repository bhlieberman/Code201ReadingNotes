# Data persistence in Android

Android apps can persist small amounts of data data locally using the Room library. It wraps SQLite in a simple API designed for smoother usage in the context of Android development. SQLite is extremely fast and small to bundle, so it performs well as an in-memory DB option.

## Components of the Room API

Room comes in three major but easy to understand parts: a class for representing the database, entities for modeling your data in Java, and methods for performing operations against the database.

## Rooms vs. JPA

Room has the concept of `DAO` or Data Access Objects. These are roughly akin to JPA's `Entity`, in that they provid an analogue to an SQL dataset in terms of Java's object system. DAOs model data coming from SQL using Java's types.