- In MongoDB there is a schema flexibility nothing is forced , unlike the SQL approach (Where we should define first the schema of each entity , In MongoDB nothing force you to choose a schema).
- With Schema Validation In MongoDB , we can make a contract between the User and our application , to make the errors of the Schema changing predictable.
- When applying a validation rule to an existing collection  , only new collections are validated.![[Schema rules definition.png]]


  ![[$jsonSchema.png]]
 - We can neither use Query Operators , Or JSONSchema to validate the schema of our documents inside a collection.($jsonSchema)
 - ![[the Methods of applying Schmea.png]]