# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
behind the scene operation.
functionality, authentication, communications, data processes, 
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model
```

Which layer in the MVC pattern communicates with the model?

```bash
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
we render the view on the front end rather than serve up new html pages
```

What does C.R.U.D stand for?

```bash
CREATE
READ
UPDATE
DELETE
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
model
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
-create new entry
-index or Return a list of all instances of the resource
-read and retrieve existing data
-update existing data-delete exisiting entry
-show single resource
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
router: GET action is sent to the url, router finds the appropriate controller
  calls the appropriate function, in this case 'show'
controller: performs the function 'show', function probably goes to the model
model: searches through database to produce data corresponding to person 1
model returns information to controller who returns back to the browser or client
```

What is the command to generate a new rails-api app?

```bash
install rails-api
```

What is the command to start an instance of a rails server?

```bash
rails-api new instance_name_here
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
db:drop
db:create
db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pets name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
-safer
-easier to use
convention over configuration. much less code to be written, standard and easier to follow along
```
