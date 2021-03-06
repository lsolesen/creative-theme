# [beyondcare.dk](http://beyondcare.dk)

Based on a Jekyll implementation of the [Creative Theme](http://startbootstrap.com/template-overviews/creative/) template by [Start Bootstrap](http://startbootstrap.com).

Creative is a one page Bootstrap theme for creatives, small businesses, and other multipurpose uses.
The theme includes a number of rich features and plugins that you can use as a great boilerplate for your next Jekyll project! 

See it live in action at <https://volny.github.io/creative-theme-jekyll/>

## To use the Creative Theme template in your project

- Start by adding your info in `_config.yml`
- In `_layouts/front.html` reorder or remove section as you prefer.

# Development

Clone the project and then go to the directory. Then do

    vagrant up

Access the box by

    vagrant ssh

Go to the symlinked directory `/var/www`.

    jekyll server --watch -P 8123 --host=0.0.0.0

Now you can access your site from the host machine at `http://localhost:8123`. All changes should be applied automatically.
