# elk-tutorial

Intro <br>
  * Search Engine based on lucene. <br>
  * It provides a distributed, multitenant-capable full text search engine with an HTTP web interface and schema-free json documents. <br>
  * Develped in java.
  * It distributes data to multiple nodes, shards by itself. <br>

<br>

Why Elastic search? <br>
  * Implements simple/fuzzy <br>
  * implement Analytics. <br>
  * Autocomplete and instant search. <br>

<br>
 
 Basic Concepts <br>
  * Cluster <br>
     -> Collection of one or more nodes that contains your whole data, indexes and provide search capablilties. <br>
  * Node <br>
     -> Single server. Collection of Shards and repicas. Also can be represented by UUID. <br>
  * Shards <br>
     -> Physically divides data that distribute data in multiple shard as per logical divides. <br>
  * Replicas <br>
     -> Keeps copy of shards. <br>
  * Index <br>
     -> Similar to database in RDBMS. <br>
  * Documents from properties <br>
     -> like column and rows.
  * Types <br>
     -> Similar to tables. <br>
  * Mapping <br>

<br>

Elastic Search API <br>
 * Document API <br>
   * Single Doc API <br>
     1. Index API <br>
        -> adds or updates a typed json doc in specific index, making it searchable.
     2. GET API <br>
        -> Searching some data
     3. Delete API <br>
        -> To delete typed JSON obj.
     4. Update API <br>
        -> update based on a script provided.
   * Muti Doc API <br>
     1. Multi GET API <br>
     2. Bulk API <br>
     3. Delete by query API <br>
     4. Update by query API <br>
     5. Reindex API <br>
 * Search API <br>
 * Indices API <br>
 * cat API <br>
 * Cluster API <br>

<br>

References:
https://www.youtube.com/watch?v=eQIWLEENhZU&list=PLGZAAioH7ZlO7AstL9PZrqalK0fZutEXF&index=1
