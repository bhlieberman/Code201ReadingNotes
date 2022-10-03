# SQL vs. NoSQL

<table>
  <tr>
    <th>NoSQL</th>
    <th>SQL</th>
  </tr>
  <tr>
    <td>Hierarchical</td>
     <td>Non-hierarchical</td>

  </tr>
   <td>Horizontally scalable</td>
 <td>Vertically scalable</td>

  <tr>
 <td>Brewer's CAP theorem for data persistence</td>
 <td>ACID</td>

  </tr>

  <tr>
 <td>Simpler queries with no cross-DB relations</td>
 <td>Heavy-duty transactional queries with joins</td>

  </tr>
  <tr>
   <td>Dynamic schema</td>
 <td>Predefined schema</td>

  </tr>
  <tr>
   <td>Usually hosted on one machine</td>
 <td>Hosted in a cluster</td>

  </tr>
</table>

1. Non-hierarchical data that requires many joins.
2. A dataset consisting of medical patient biographical information, doctors' visits, diagnoses, etc.
3. Hierarchical data or anything that requires a dynamic schema.
4. A dataset tracking restaurant reviews.
5. NoSQL
6. SQL is best for vertical scalability and NoSQL for horizontal.

# Video material

1. Structured Query Language
2. It means that it has a schema to define the connections between data stored in individual tables.
3. A table with rows and columns.
4. A definition of the structure of the data and its relationships.
5. Any database that is non-relational with a dynamic schema. It could be key-value, graph, or any other variety.
6. In a document database, all the data is stored together as key-value pairs. These can be queried in the same fashion as a hashmap or JS Object.
7. MongoDB uses documents to store data, which gives the user constant-time lookups as everything is stored in one place.
8. Mongo is more flexible in general because of its dynamic schema. Any changes to one part of the dataset do not require changes across other data points. In SQL, if you modify the schema, many parts of the dataset must be changed to reflect this.
9. They are not optimal for high-performance transactional queries on complex datasets.
