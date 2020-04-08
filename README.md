# Resource Catalog
**WIKI**

### To-Do List

- http Verbs (per Resource Type)
    - Using Express Router 
        - GET
        - POST
        - PUT
        - PATCH
        - DELETE
- Simple Views with EJS
    - Home/Director
    - List Page per Resource type
        - Articles (Links)
        - Vocabulary
        - Concepts
    - Details Page for various resource types
        - Individual page showing more details
        - With Edit and Delete
    - Create page for resource types
- Create Database in MongoDB Atlas 
- Build Data Access Layer 
    - Connected to Mongo
        - Insert (CREATE)
        - Find (READ)
        - Upsert (UPDATE/PUT)
        - UpdateOne/UpdateMany (UPDATE/PATCH)
        - Remove (DELETE)

### Data Model

ARTICLE 
```
{
    "title": STRING,
    "author": STRING,
    "link": URL as a STRING,
    "description": STRING,
    "topics": ARRAY of STRINGs,
    "dateAdded": DATE
}
```