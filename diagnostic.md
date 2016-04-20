# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
To store data and lighten a clients workload
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
bc we are building our own front end and we are using Router
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Model
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index
Create
show
Update
destroy
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
Router request Controller
controller request Model
Model gets person 1 from DB
model give person 1 to controller
controller gives person 1 to Router
router gives person 1 to user
```

What is the command to generate a new rails-api app?

```bash
rails-api g scaffold
```

What is the command to start an instance of a rails server?

```bash
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rake db:drop
rake db:create
rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold user name:string age:string
```

List two advantages of using serializers? (2 bullet points)

```bash
Hides sensitive information
Makes it a little harder to hack
```
