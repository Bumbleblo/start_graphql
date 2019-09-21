# start_graphql
Example and content to figure out Graphql features and how to use them with django.


### Concepts 

You must learn some graphql concepts. The official documentation is a good start and have some pratical code.

Some concepts are:

* Django (for that tutorial)
* Scalars and Interfaces
* Fields
* Types
* Query
* Mutation
* Schema


### Resumes

#### Scalars 

All graphql objects inherits from ObjectType, a object type is just a way that Graphql saves information. Seen it that, objects must have a data structure and that is a Scalar. Scalars in just a minimal data in graphql, something like int and string in a usual language. 

#### Fields

Graphql objects are not only created with Scalars, some data maybe can be a objects of a collection of objects. In that context graphql use a abstract layer called fields. Fields is just the representation of your data, maybe a field is just a scalar but in some case you need to save a object o a relation in that.

#### Types

Graphql types looks like a django model or a object. A type have a set of fields and that types can inheret from others types called interfaces.


#### Query

Query is a way that you can show your types, maybe you only care about the name of you user in a menu bar for example, in others cases (in a user CRUD) you need to use all information about your use, or list all users in your base. Query is apropriated for that.


#### Mutation

Want to change your data ? Want to put a business logic when you are creating a user ? Mutation is for that! A mutation is a way that you change or create you data.

#### Schema


Schema joins all concepts above together. A schema have mutations and query.

Schema is just a way that graphql relate fields (data) with query and mutations. In a short phrase: "Schema merge all that others concepts together"

