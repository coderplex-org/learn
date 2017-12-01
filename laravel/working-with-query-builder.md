### Working with Query Builder

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
