# API intro
# RESTful services
# HTTP calls

## What is an API

``` 
API stands for - Application programming Interface
```
## What is RESTful Services
```html
RESTfull stands for Representational State Transfer-
which is an architechtural style for applications
```
- It is primarily used to build web services that are lightweight, maintainable and scalable

- Why do we need API
``` bash

The key pupose of creating API is to give access and represent those resources

```

- These services, ideally need to be easy to implement, maintainable, extensible, and scalable.
The RESTful design promises that and more

### The RESTful services should have following properties:
``` bash
Representation and data flow
Messages
URIs/Nameing resources
Statelessness
Caching
```

### So what is Representation and data flow

- First tep is to define our data resource 
- Let's take an example of basic block of customer data:
``` JSON
{
 
 "ID : "1",
 "firstname" : "Shah"
 "surname" : "Khan"
 "email" : "abc@gmail.com"

}
```
- The data could be in xml or any other form but your data reprenstation should have some basic qualities:
- 1 Both client and server needs to be able to read the format
- 2 A representation needs to completely deliver the resource
```markdown
if you customer resource contained transaction history these should be broken down into separate representations/services

```
- 3 Document your resource contract - if your client does not know what will be received they may not be able to consume it.


# HTTP Messages and Verbs
## What is HTTP?

```markdown
HTTP is the protocol of internet communication, it is important to understand together with API communication

HTTP works on simple methodology of a REQUEST /  RESPONSE system

any request made, you expect to receive something back.. what ever it may be
```
- Let's have look at HTTP request structure

```markdown
                HTTP Request Structure
VERB            URL     Version
-------------------------------------------------
            Header
            Key value Pairs
            ----------------
            key:value
            key:value
            key:value
------------------------------------------------
            Body

            Text
            JSON 
            XML
-------------------------------------------------
```
- To be continued