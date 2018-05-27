# [My First Application](https://www.github.com/1n3ffbl3/MyFirstApplication)

The goal of the project is to create a demo version of application. Application itself is designed to create easier way of communication between people and organizations who want to help others, but they struggle to do that due to many circumstances. Let's consider following scenario:
"
  Brave people who want to help are trying to find a humanitarian organisation. They call them to know which needs are currently demanding, i.e. products like diapers. As people have heard about that, they have bought diapers and they went to the organisation office location. At the office, a man is saying that already too many people brought diapers, but now the blankets are in demand.
"  
As you can see, there is lack of communication between the people that are willing to help, and the organisations themselfs. 
Here comes our application, as it is designed to fix the missing gap of communication! We will provide a simple tool to make the commucation easier than it ever was. Organisation will be able to organise new events for gathering goods or needs and people will be able to assist and offer their help. Therefore we will reduce the chance or mistakes as we could read in the scenario above.
Moreover private persons will be able to offer their help for the community (i.e. shelter for refugee).


### Index

* [Use cases](#use-cases)
* [Solution Explanation](#solution-explanation)
* [Constraints](#constraints)
* [Resource Estimation](#resource-estimation)
* [Bugs & Challenges](#bugs-challenges) 
* [Language Features](#language-features)
* [Learning Journal](#learning-journal)

---

## Use cases

### Users
* Organization
* Member of organization (aka Org Member)
* Private users

### Organization use cases
As an Organization I can:
* 1 Create my account
* 2 Login into my account
* 3 Update the Organization's information information
* 4 Invite team member
* Accept team members
* Post ways the organization needs help
  * post needs of volunteers
  * post donation needs
  * mention/tag other organizations or usersor skills which might be related to the post (@mention and/or hashtags)
* Update the organization posts
* Delete organization posts
* Search for help posts (offered or needed)
 * See the info or way to contact them
* Indicate misuse of entity's personal information
 * Associated with other "organizations" in the system
 * associated with other users
 * associated with a post

### Org Members use cases
As an Org Member I can:
* Create an account
* Associate myself to an Organization as a team member
* Login into my account
* Update my personal information
* Post ways the organization needs help
  * post needs of volunteers
  * post donation needs
  * mention/tag other organizations or usersor skills which might be related to the post (@mention and/or hashtags)
* Update the organization posts
* Delete organization posts
* Post ways I can help:
 * post ways I can volunteer
 * post things I want to donate
 * mention/tag other organizations or usersor skills which might be related to the post (@mention and/or hashtags)
* Update my personal posts
* Delete my personal posts
* Search for help posts (offered or needed)
 * See the info or way to contact them
* Indicate improper use of my account
* Indicate some impropriety of another account (organization or user)
* Indicate some impropriety of a post


### Private Users use cases
As a private user I can:
* Create an account
* Login into my account
* Update my personal information
* Post ways I can help:
 * post ways I can volunteer
 * post things I want to donate
* Update my posts
* Delete my posts
* Mark a post as completed (aka "not available" for items)
 * Mark a given item as completed /no longer available
* Search for help posts (offered or needed)
 * See the info or way to contact them
* Indicate improper use of my account
* Indicate some impropriety of another account (organization or user)
* Indicate some impropriety of a post


[TOP](#index)

___

## Solution Explanation

Explain your solution in detail, however works for you.  Perhaps by using a specific input to illustrate, by describing your strategy, or by including a diagram [directly from Sketchboard.io](https://sketchboard.io/blog/2014/03/06/github-sketchboard.html).

[TOP](#index)

---

## Constraints

What constraints did you place on yourself, and why?  Did they end up being helpful or not?

Marta: 
1. Firstly sketch website on paper then create it.
2. Write use cases befor implementing logic.
3. Improve technical vocabulary.


In this application, we have to consider three types of users:
* private user
* user as an organisation
* member of an organisation
Each of them have different actions in our application, as you can see it above in our use cases. 

[TOP](#index)

___


## Resource Estimation

Estimate how what resources you will require, and how much of each.  

1. Team resources and availability: 
  * two developers (1 full time and the other part time)
  * one mentor (2 hours per week)
  * one teacher (6 hours per week)

2. Requirements:
* demo of the application - 3 weeks of development
* error analysis - 2 hours per week
* consulting with users (at last 5 people) - 1 week 
* feedback gathering - 2 day
* analysing feedback  - 1 days
* implementing feedback - 1 week
* presentation of first version of the application 

[TOP](#index)

___

## Challenges & Bugs

The biggest challenge for me was to create an application from scratch. 

Challenges which required learning:
- javascript
- html
- css
- debugging
- MVC
- vue js 
- promises
- how to query API / "consume API"
- node js (libraries: express, cors, body-parser)
- endpoints (request type, information transfer)

Bugs:
- array methods (wrong understanding of methods behaviour)
- API (wrong request type, reading request params, sending parameters)
- javascript syntax (sign for comparision vs. sign for assignment)
- inheretance in js 
- arrow functions
- promises


[TOP](#index)

___

## Language Features

1. Promises
2. Arrow functions
3. Test libraries (tinytest, mocha)
4. JS libraries (lodash)
5. Framework (vue js)
6. Scoping  (diffrence between var & let)


[TOP](#index)

---

## Learning Journal

Things I learned doing this project: 
  * team work
  * planning 
  * task and time scheduling 
  * visualization of problems (sketching)
  * problem solving
  * information research
  * error analysis
  * testing
  * debugging

New vocabulary:
  * MVC (Model View Controller)
  * promises
  * arrow function
  * API (Application Public Interface)
  * class
  * service
  * dependency
  * predicate
  * callback

Things I struggled with:
  * debugging
  * time management
  * promises
  * callbacks
  * data storage
  * routing

Lessons to apply for next time:
  * better knowledge of html/javascript syntax
  * debugging
  * more intensive testing
  * looking to more efficient libraries to work with
  * learning about others frameworks (i.e. react js)



[TOP](#index)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

