![[Many-to-Many-EMbedding.png]]
![[attachements/Referencing-Many-to-Many.png]]
- in MongoDB we can have data duplication , this gives us more data flexibility.

- We can Embed the child in the one sub-document in the parent.![[Embedding-Many-to-Many.png]]
- referencing in Many-to-Many![[Referencing-Many-to-Many 1.png]]
we can have a data duplication but that is fine in MongoDB. we use an array in order to reference multiple Documents.
- When trying to work with Many-to-Many relationships:
   - Array of references to the Child documents in the parent documents.
   - Array of references in child documents .