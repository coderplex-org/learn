---
title: Basic Routing and Views
---
# Basic Routing and Views

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites
:-- | :--: | :--: | :--: | :--:
Basic Routing | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/routing#basic-routing) | 1 hour | Introduction to MVC architecture
Named Routes | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/routing#named-routes) | 0.5 hour | Basic Routing
Creating Views | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/2) | [Documentation](https://laravel.com/docs/5.4/views#creating-views) | 1 hour | Basic Routing

## Tasks

- Create a route `/admin` and redirect to view `admin.blade.php` when that route is hit.
- Name that route as `admin`
- Whenever you create a route in the future, name that route.
- Use [this](https://gist.github.com/pbteja1998/011df2c0209e3b63fd3dce281451d328) sidebar template for `admin.blade.php`
- Create routes `/users` , `/posts` , `/comments` and link `All Users` , `All Posts` and `All Comments` that are present in sidebar to those routes.
- When you go to `/users` url or when you click `All Users` tab on the sidebar, you should be redirected to `users/index.blade.php`. Posts and Comments should have similar behaviour.
