### Resources

Concept | Best Video Resource | Best Text Resource | Duration | Prerequisites
:-- | :--: | :--: | :--: | :--:
Layouts and Structures | [Laracasts](https://laracasts.com/series/laravel-from-scratch-2017/episodes/10) | [Layouts](https://laravel.com/docs/5.4/blade#template-inheritance) | 1 hour | Models, Views, Controllers and Routes

### Tasks :
- Add two folders `partials` and `layouts` in `resources/views` directory.
- Create a layout file `layouts/master.blade.php` in `layouts` folder and include all markup required like stylesheets, scripts, etc in that file and extend this layout file .
- Create the folllowing partials and include these partials in `admin` template.
    - `partials/sidebar.blade.php`
    - `partials/header.blade.php`
    - `partials/footer.blade.php`
- Grab the markup of those header and footer from some [bootstrap](https://getbootstrap.com/examples/blog/) template.  
- You can add any other layouts or partials as per your requirement.
