# Week 3
## Web Application Fundamentals


### Monday 
### Intro Express

#### Morning

Building up to express

* A little server (10 min)
  * intro `http`
  * dealing with callbacks
* Middleware (5 min)
  * `Connect`
  * `Benefits`
* Intro Express (25min)
  * Routing types of requests
    * `GET`
    * Rendering responses
  * Routing Params
    * `GET` with Url Params
* Calculator Exercise (30min)
  * SETUP routes that take two `params`
    * `/add`
    * `/subtract`
    * `/multiply`
    * `/divide`

#### Afternoon

Views in Express 

* Continue Routing
  * `GET`
    * Create an Array of fake Data
    * **INDEX** method to show all Data
      * Rendering a concatenated string
  * `POST`
    * CREATE method
    * Saving Params to Array
    * `res.redirect` to **INDEX**
  * Show
    * route.params
* Views 
  * Intro Templating `ejs`
    * Creating a form
    * Iterating through list

### Monday Lab

* NEWS FEED LAB

### Tuesday
### Working with API's


#### Morning

Interacting with API

* Usign `http` requests
  * `Get`
    * sending params
    * formating responses
    * Movies API
* Rendering Movie Response Data

#### Afternoon

More controller functionality using a faux DB for CRUD

* Interacting with a Faux DB
  * Review
    * INDEX
    * Create
  * Setup Faux DB using Array
    * Books
  * PUT
    * handling forms
      * browsers and `POST` or `GET`
    * parsing `query` params
    * parsing `body` params
  * DELETE


### Wednesday
Intro SQL DAY

#### Morning

Create tables insert, select

* [https://github.com/wdi-sf-march-2014/notes/blob/master/DatabasesIntro/DatabasesIntro.md](https://github.com/wdi-sf-march-2014/notes/blob/master/DatabasesIntro/DatabasesIntro.md)


#### Afternoon

JOINS and intro Node Postgres

* [https://github.com/wdi-sf-march-2014/notes/blob/master/DatabasesIntro/joins.md](https://github.com/wdi-sf-march-2014/notes/blob/master/DatabasesIntro/joins.md)

### Thursday

Express with SQL

#### Morning

Node Postgres

* Intro to Node Postgres
* Connecting
  * A Basic Query
* Practice `SELECT`
  * Make a `SELECT` together
* Practice `INSERT`
  * Make a `INSERT` together


#### Afternoon

Create A Postgres Module

* Create A DB module
  * Create Methods for SELECT/INSERT
* Utilize inheritance to DRY up Code


#### MINI LAB

* ORM LAB
