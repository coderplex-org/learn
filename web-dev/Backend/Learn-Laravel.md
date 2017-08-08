# <p align="center">RoadMap for Laravel</p>

# <p align="center">Preface</p>

**Laravel** is a free, open-source PHP web framework, created by **Taylor Otwell** and intended for the development of web applications following the **Model–View–Controller (MVC)** architectural pattern.

#### Why choose Laravel when there are tons of other PHP frameworks ? Here are a few reasons.
- **Security**: Its truth that no application is 100% secure and things will depend on how you are using and writing code and its structure. But in comparison to other frameworks Laravel has some good signs of security. Laravel takes care of security with CSRF tokens. These checks on each POST request, so make sure you use them, essentially this protects you from someone changing the nature of the request, i.e. from POST to GET.
- **Emerging star**: Lots of web development companies are adopting Laravel very quickly due to its dynamic capabilities and they are getting good response. You can see the popularity in [Google trends](https://trends.google.com/trends/explore?q=yii,CodeIgniter,Zend%20Framework,Cakephp,Laravel&hl=en-US). In Google trends you will see the difference clearly as how this Laravel framework is gaining popularity and its growing exponentially.
- **Template**: One of the best features of the framework is Blade templating engine. It’s so intuitive and working with the typical PHP/HTML so much better and easy. In Laravel, templates are very light weighted from which you can create amazing and decent layouts. You can use different type of widgets of JS and CSS with solid structure. So this also improves your websites load time which helps in websites search engine performance.
- **Integration**: Easy integration with many popular FrontEnd Javascript frameworks like **VueJS**, **Angular JS** and **React** makes it even more better choice.
- **Laracast**: Laracasts is the excellent tool for learning Laravel. Here you will get both free and paid video tutorials. And from the information you can learn about Laravel. The contents are all made by experts and experienced instructors who offers clear and concise instructions. So if you want to learn Laravel and want to build your carrier around it then Laracast is worth looking at.
- **Artisan**: In Laravel, developer needs to interact using a command line that handles the Laravel project environment. Laravel is providing a built-in tool called Artisan, which allows user to perform lengthy programming tasks really quickly which can be easily done by Laravel developers. It is used to create a structured code, and database structure to make it easier to manage the database system.
- **Ready Made apps**: With the growing popularity of Laravel and increasing demand of customer asking for similar features now there are various readymade apps available which can be used to add on any feature in Laravel website. This actually reduced effort and in that way reduced cost of development.
- **MVC Support**: This is one of the important reasons which make Laravel the best PHP framework that it supports MVC Architecture. Due to this it helps in improving the performance, better documentation, and has multiple built-in functionalities.

Besides this there are other various key factors available in Laravel like Routing system, Application logic, Better code foundation, Suitable for all type of projects, Different API for caching system and many more.

# <p align="center">Contents</p>
- [Preface](#preface)
- [Community](#community)
  - [Team](#team)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Introduction to MVC architecture](#introduction-to-mvc-architecture-in-php)
  - [Core Laravel](#core-laravel)
  - [Advanced Laravel](#advanced-laravel)

- [Additional Resources](#additional-resources)
- [OpenSource Projects](#open-source-projects)

## <p align="center">Community</p>

- You can also interact through [GitHub issues](https://github.com/fcc-hyd/issues).
- We also have a chat room! [Join the chat at [Discord](https://discordapp.com/channels/331374249921216514/335713856427130882)]

> **PS**: A forum is an ideal way to interact with other students as we do not lose important discussions, which usually occur in communication via chat apps.
**Please use our discord group for important discussions**.

### Team

* **Curriculum Founder**: [Bhanu Teja](https://github.com/pbteja1998)
* **Curriculum Maintainer**: [Bhanu Teja](https://github.com/pbteja1998)
* **Contributors**: [contributors](#)


# <p align="center">Curriculum</p>

**Curriculum version**: `1.0.0` (see [CHANGELOG](https://gist.github.com/pbteja1998/6e26c16ecc2eb9291cfea2447f0b9956/revisions))

- [Prerequisites](#prerequisites)
- [Introduction to MVC architecture](#introduction-to-mvc-architecture-in-php)
- [Core Laravel](#core-laravel)
  - [Installation](#installation)
  - [Models, Views, Controllers and Routes](#models-views-controllers-and-routes)
      - [Basic Routing and Views](#basic-routing-and-views)
      - [Pass Data to Views](#pass-data-to-views)
      - [Database Setup](#database-setup)
      - [Working with Query Builder](#working-with-query-builder)
      - [Eloquent](#eloquent)
      - [Controllers](#controllers)
      - [Route Model Binding](#route-model-binding)
  - [FrontEnd](#frontend)
      - [Layouts and Structures](#layouts-and-structures)
      - [Form Requests and CSRF](#form-requests-and-csrf)
      - [Form Validation](#form-validation)
      - [Rendering](#rendering)
      - [Laravel Mix](#laravel-mix)
      - [Flash Messaging](#flash-messaging)
  -  [Relationships](#relationships)
       - [Eloquent Relationships](#eloquent-relationships)
       - [One-to-Many Relationship](#one-to-many-relationship)
       - [Pivot Tables](#pivot-tables)
  - [Authentication](#authentication)
       - [Scaffold Authentication](#scaffold-authentication)
       - [Manual Authentication](#manual-authentication)
   - [Archives](#archives)
       - [Add Archives](#archives)
       - [View Composers](#view-composers)
- [Advanced Laravel](#advanced-laravel)
  - [Testing and Seeding](#testing-and-seeding)
       - [Basic Testing](#testing-and-seeding)
       - [Seeding with Test Dummy](#testing-and-seeding)
       - [Seeding with Laracasts Generators](#testing-and-seeding)
   - [DI, Auto-Resolution, and Repositories](#)
   - [The Service Container](#)
   - [Service Providers](#)
   - [Pusher API](#)
   - [Web Sockets](#)
- [Final project](#final-project)


## <p align="center">Prerequisites</p>

- This course assumes the student has already taken [Frontend](#front-end) domain  or have a basic knowledge of front-end.
- This course also assumes that the student has already taken [PHP](#php) programming language or reasonably familiar with PHP and its Object Oriented Programming Concepts.


## <p align="center">Introduction to MVC architecture in PHP</p>

This course will introduce you to the MVC Pattern using PHP. This course is required, but feel free to skip to the next section if you already know what MVC pattern mean.

**Topics covered**:
`models`
`views`
`controllers`
`routes`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Introduction to MVC Architecture](https://r.je/mvc-in-php.html) ([alt](https://www.sitepoint.com/the-mvc-pattern-and-php-1/)) | 1 week | 4-7 hours/week | PHP

## <p align="center">Core Laravel</p>

All coursework under Core Laravel is **required**, unless otherwise indicated.

### <p align="center">Installation</p>
**Topics covered**:
`composer installation in Ubuntu`
`laravel installation in Ubuntu`

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites
:-- | :--: | :--: | :--: | :--:
Installation of Laravel in Debian based systems | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/1) | [Installation](https://gist.github.com/pbteja1998/a735fad5d843a952c937f7b3ba8f058e) | 1 hour | none

#### Tasks :
- Create a fresh laravel project called blog and view the welcome page.

### <p align="center">Models Views Controllers and Routes</p>

**Topics covered**:
`basic routing`
`basic views`
`passing data to views`
`setting up database`
`query builder`
`eloquent`
`tinker`
`controllers`
`route model binding`
`and more`


#### Basic Routing and Views

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Basic Routing | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/routing#basic-routing) | 1 hour | Introduction to MVC architecture
Named Routes | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/routing#named-routes) | 0.5 hour | Basic Routing
Creating Views | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/views#creating-views) | 1 hour | Basic Routing

#### Tasks :
- Create a route `/admin` and redirect to view `admin.blade.php` when that route is hit.
- Name that route as `admin`
- Whenever you create a route in the future, name that route.
- Use [this](https://gist.github.com/pbteja1998/011df2c0209e3b63fd3dce281451d328) sidebar template for `admin.blade.php`
- Create routes `/users` , `/posts` , `/comments` and link `All Users` , `All Posts` and `All Comments` that are present in sidebar to those routes.
- When you go to `/users` url or when you click `All Users` tab on the sidebar, you should be redirected to `users/index.blade.php`. Posts and Comments should have similar behaviour.
 
<br>

#### Pass Data to Views

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Pass Data to Views | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/5) | [Documentation](https://laravel.com/docs/5.4/views#passing-data-to-views) | 0.5 hr | Creating Views

#### Tasks :
- Send the following data as `posts` to `All Posts` view page and display them.
    - **"I am going to Create and Edit Users"**
    - **"I am going to Create and Edit Posts"**
    - **"I am going to Create and Edit Comments"**
    - **"I am going to like and Unlike Posts"**
 
<br>

#### Database Setup

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Database Setup | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/4) | [Documentation](https://laravel.com/docs/5.4/database) | 0.5 hr | none

#### Tasks :
- Setup a database with name `blog` using `mysql` or `sqlite`

<br> 

#### Working with Query Builder

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Working with Query Builder | [Migrations and Query Builder](https://laracasts.com/series/laravel-from-scratch-2017/episodes/6) | [Migrations](https://laravel.com/docs/5.4/migrations)| 1 hr | Database Setup
Working with Query Builder | [Migrations and Query Builder](https://laracasts.com/series/laravel-from-scratch-2017/episodes/6) | [Query Builder](https://laravel.com/docs/5.4/queries) | 1 hr | Database Setup

#### Tasks :
- Create two tables `posts` and `comments` and `tasks`.
- `posts` table should contain `title` and `body`. `title` should be a unique field.
- `comments` table should contain a `comment_body`
- Empty the `All Posts` page.
- Install something which is equivalent to `Sequel Pro` for your operating System.
- Using that add some posts to the database and display them on `All Posts` page.
- When a user clicks on a individual post, it should redirect to a `posts/{id}` and `show` individual post. Later we will associate a comment with a post.
- Similarly implement for `All comments` and `show` individual comment.
 
<br>

#### Eloquent

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Eloquent | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/7) | [Eloquent](https://laravel.com/docs/5.4/eloquent) | 1 hr | Query Builder

#### Tasks :
- Change the code such that you are using Eloquent instead of Query Builder.
- Get Hands On Practice with Eloquent using Tinker.

<br> 

#### Controllers

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Basic Controllers | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/8) | [Basic Controllers](https://laravel.com/docs/5.4/controllers#basic-controllers) | 1 hr | Eloquent

#### Tasks :
- Change `web.php` to use `Controllers` instead of inline functions.
 
<br>

#### Route Model Binding

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Route Model Binding | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/9) | [Route Model Binding](https://laravel.com/docs/5.4/routing#route-model-binding) | 0.5 hr | Controllers

#### Tasks :
- Make use of Route Model Binding to show a comment or a post. But instead of binding `id` , you should bind the `title` of a post to show a post. So, your route should look something like this `post/{title}`
 

### <p align="center">FrontEnd</p>

**Topics covered**:
`layouts and structures`
`csrf protection`
`form requests`
`form validation`
`laravel mix`
`flash messaging`
`and more`


#### Layouts and Structures

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Layouts and Structures | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/10) | [Layouts](https://laravel.com/docs/5.4/blade#template-inheritance) | 1 hour | Models, Views, Controllers and Routes

#### Tasks :
- Add two folders `partials` and `layouts` in `resources/views` directory.
- Create a layout file `layouts/master.blade.php` in `layouts` folder and include all markup required like stylesheets, scripts, etc in that file and extend this layout file .
- Create the folllowing partials and include these partials in `admin` template.
    - `partials/sidebar.blade.php`
    - `partials/header.blade.php`
    - `partials/footer.blade.php`
- Grab the markup of those header and footer from some [bootstrap](https://getbootstrap.com/examples/blog/) template.  
- You can add any other layouts or partials as per your requirement.
 
<br>

#### Form Requests and CSRF

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Form Requests and CSRF | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/11) | [CSRF Protection](https://laravel.com/docs/5.4/csrf)| 0.5 hour | Layouts and Structures
Form Requests and CSRF | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/11) | [Requests](https://laravel.com/docs/5.4/requests)| 0.5 hour | Layouts and Structures
Form Requests and CSRF | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/11) | [Inserting and Updating Models](https://laravel.com/docs/5.4/eloquent#inserting-and-updating-models) | 0.5 hour | Layouts and Structures

#### Tasks :
- Create forms to add a `post` and a `comment` to the database.

<br> 

#### Form Validation

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Form Validation | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/12) | [Validation](https://laravel.com/docs/5.4/validation) | 0.5 hour | Form Request Data and CSRF

#### Tasks :
- Add both client side and server side validations and show appropriate errors when validation fails.
- Create a partial `partials/errors.blade.php` so that it can be reused in all types of forms.
 
<br>

#### Rendering

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Rendering | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/13) | [Blade Control Structures](https://laravel.com/docs/5.4/blade#control-structures) | 1 hour | Form Validation
Rendering | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/13) | [Carbon](http://carbon.nesbot.com/docs/#api-formatting) | 1 hour | Form Validation

#### Tasks :
- Use `Eloquent Builder` functions and `Carbon` library to display posts such that latest post is at the top. Also display the time stamps of the posts.

<br> 

#### Laravel Mix

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Laravel Mix | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/14) | [Laravel Mix](https://laravel.com/docs/5.4/mix) | 1.5 hour | Rendering

#### Tasks :
- Install NodeJs and npm in Debian based linux distributions, run
```sh
$ sudo apt-get update
$ sudo apt-get install nodejs
$ sudo apt-get install npm
```
- Move your css and js files to assets directory and compile them using Laravel Mix.
 
<br>

#### Flash Messaging

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Flash Messaging | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/29) | [Flash Message](https://laravel.com/docs/5.4/redirects#redirecting-with-flashed-session-data) | 1 hour | Models, Views, Controllers and Routes

#### Tasks :
- Show a flash message whenever a user signs up or posts or comments on a post.


### <p align="center">Relationships</p>

**Topics covered**:
`relationships`
`form method spoofing`
`and more`


#### Eloquent Relationships

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Eloquent Relationships | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/15) | [Relationships](https://laravel.com/docs/5.4/eloquent-relationships) | 1 hour | Models, Views, Controllers and Routes

<br>

#### One-to-Many Relationship

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
One-to-Many Relationship | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/16) | [Form Method Spoofing](https://laravel.com/docs/5.4/routing#form-method-spoofing) | 1 hour | Eloquent Relationships

#### Tasks :
- Add a relationship between posts and comments table. (you have to add `post_id` field in the `comments` table )
- Create partials to add a comment and to show comments of a post.
- Include those partials in the `All Posts` page and `Show Post` page.
- Add `Edit Post` and `Edit Comment` functionalities.
 
<br>

#### Pivot Tables

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Many-to-Many Relationship | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/30) | [Pivot Table / Many to Many Relatonship](https://laravel.com/docs/5.4/eloquent-relationships#many-to-many) | 1 hour | Eloquent Relationships

#### Tasks :
- Add `Like` functionality.
- Any user can `like/unlike` any post.
- Add necessary Controller methods and views.
 

### <p align="center">Authentication</p>

**Topics covered**:
`scaffolding authentication`
`manual authentication`


#### Scaffold Authentication

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Scaffold Authentication | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/17) | [Authentication Quickstart](https://laravel.com/docs/5.4/authentication#authentication-quickstart) | 0.5 hour | Database Setup
Scaffold Authentication | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/17) | [Middleware](https://laravel.com/docs/5.4/middleware) | 1 hour | Database Setup
Scaffold Authentication | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/17) |  [Mail to Log](https://laravel.com/docs/5.4/mail#mail-and-local-development) | 0.5 hour | Database Setup

#### Tasks :
- Experiment with Scaffolded Authentication. (Do not run `php artisan make:auth`to the existing `blog` project. Create a new project and just experiment with it. We will be creating our own Authentication workflow instead of using Scaffolded Authentication)
- Look into the `Middlewares` section, we are going to use it in the subsequent sections.

<br>

#### Manual Authentication

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Manual Authentication - 1 | [Manual Authentication - 1](https://laracasts.com/series/laravel-from-scratch-2017/episodes/18)| [Manual Authentication](https://laravel.com/docs/5.4/authentication#authenticating-users)| 1 hour | Database Setup
Manual Authentication - 2| [Manual Authentication - 2](https://laracasts.com/series/laravel-from-scratch-2017/episodes/19) | [Manual Authentication](https://laravel.com/docs/5.4/authentication#authenticating-users) | 1 hour | Database Setup
Manual Authentication - 2 | [Manual Authentication - 2](https://laracasts.com/series/laravel-from-scratch-2017/episodes/19) | [Named Routes](https://laravel.com/docs/5.4/routing#named-routes)| 0.5 hours | Database Setup
Manual Authentication - 2 | [Manual Authentication - 2](https://laracasts.com/series/laravel-from-scratch-2017/episodes/19) | [Dependency Injection](https://laravel.com/docs/5.4/controllers#dependency-injection-and-controllers) | 1 hours | Database Setup
#### Tasks :
- Setup `Custom Authentication`.
- Add relationships between `users and posts` as well as `users and comments`. Add all necessary views and Controller methods.


### <p align="center"> View Composers and Archives </p>

**Topics covered**:
`view composers`


#### Archives

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Archives | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/20) | [Raw SQL Queries](https://laravel.com/docs/5.4/database#running-queries) | 0.5 hour | Authentication
Archives | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/20) | [Eloquent Collections](https://laravel.com/docs/5.4/eloquent-collections) | 1 hour | Authentication

#### Tasks :
- Add `Archives` as shown in the video.

<br>

#### View Composers

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
View Composers | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/21) | [View Composers](https://laravel.com/docs/5.4/views#view-composers) | 1 hour | Archives

#### Tasks :
- Add `View Composer` for showing archives on all pages.


## <p align="center">Advanced Laravel</p>

After completing **every required course** in Core Laravel, students should choose a subset of courses from Advanced Laravel based on interest.
Not every course from a subcategory needs to be taken.


### <p align="center">Testing and Seeding</p>

**Topics covered**:
`basic testing`
`seeding with Laracasts TestDummy`
`seeding with Laracasts Generators`
`and more`

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites 
:-- | :--: | :--: | :--: | :--: 
Basic Testing | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/22) | [Testing - Getting Started](https://laravel.com/docs/5.4/testing), [HTTP Tests](https://laravel.com/docs/5.4/http-tests), [Database Testing](https://laravel.com/docs/5.4/database-testing), [Writing Factories](https://laravel.com/docs/5.4/database-testing#writing-factories), [Using Factories](https://laravel.com/docs/5.4/database-testing#using-factories), [Database Transactions](https://laravel.com/docs/5.4/database#database-transactions) | 2 hour | Ready Laravel Project
Seeding with TestDummy | [Seeding with TestDummy](https://laracasts.com/series/advanced-eloquent/episodes/1) | [Test Dummy](https://gist.github.com/pbteja1998/fe30fd96e26a2868b5925c83df041808) - for database seeding | 1 hour | Ready Laravel Project
Seeding with Laracasts Generators | [Seeding with Laracasts Generators](https://laracasts.com/series/incremental-api-development/episodes/1) | [Laracasts Generators]() - for database seeding | 1 hour | Ready Laravel Project

#### Tasks :
- Write your own tests to test some features of the project.
- Learn how to seed Fake Data using TestDummy and Laracasts Generators.


## <p align="center">Final project</p>

You are encouraged to do the assignments and exams for each course, but what really matters is whether you can *use* your knowledge to solve a real world problem.

After you've gotten through all of Core Laravel and the parts of Advanced Laravel relevant to you, you should think about a problem that you can solve using the knowledge you've acquired.
Not only does real project work look great on a resume, the project will *validate* and *consolidate* your knowledge.

### Projects :
- [Social Networking Site](https://gist.github.com/pbteja1998/7651d611e8b22b5228713f12400ce624) (50 hrs)
- [OAuth Authentication with Social Networking Sites](https://gist.github.com/pbteja1998/6a3649b65763681f14d1b98a3603515b) (1 hr)
- [E-Commerce Application]() (100 hrs)
- [Chat Application]() (100 hrs)

## <p align="center">Evaluation</p>

Upon completing your final project, submit your project's information to [PROJECTS](PROJECTS.md)
via a pull request and use our [community](#community) channels to announce it to your fellow students.

Your peers and mentors from the community will then informally evaluate your project.
You will not be "graded" in the traditional sense — everyone has their own measurements for what they consider a success.
The purpose of the evaluation is to act as your first announcement to the world that you are a developer, and to get experience listening to feedback — both positive and negative — and taking it in stride.

The final project evaluation has a second purpose: to evaluate whether CoderPlex,
through its community and curriculum, is successful in its mission to guide independent learners in obtaining knowledge.

## <p align="center">Cooperative work</p>

You can create this project alone or with other students!
**We love cooperative work**!
Use our [channels](#community) to communicate with other fellows to combine and create new projects!


## <p align="center">Additional Resources</p>
- [Awesome Laravel](https://github.com/chiraggude/awesome-laravel/blob/master/README.md)


## <p align="center">Open Source Projects</p>
There are many open source Laravel Projects to which you can contribute to. Some of them can be found [here](http://openlaravel.com/)