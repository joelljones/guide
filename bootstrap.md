# Bootstrap

Bootstrap CSS library, a popular resource that enables you to quickly and efficiently design responsive web pages.

## Table of Contents

- [Introduction to Bootstrap](#introduction-to-bootstrap)

### Resources

- [Bootstrap](https://getbootstrap.com)
- [GitHub](https://github.com/twbs/bootstrap)
- [Bootstrap CDN](https://bootstrapcdn.com)
- [W3Schools](https://w3schools.com/bootstrap)

---

# Introduction to Bootstrap

Bootstrap CSS library, a popular resource that enables you to quickly and efficiently design responsive web pages.

In programming, a library is a collection of prewritten code that solves a complicated problem so other engineers don't have to. There are many advantages to using Bootstrap; Bootstrap allows you to easily implement responsive design, style components like navigation bars and buttons, and evenly space content on your web page.

The Bootstrap library serves as a force to unify user experience across the web. By adhering to established standards, the Bootstrap library provides an easy way to create a familiar user experience on your website.

1. The HTML document must be linked to a local or CDN hosted Bootstrap library.

    ```HTML
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
    <!-- linked before the local stylesheet, style.css -->
    ```

2. The Bootstrap `container` and `container-fluid` classes are required for every section of a Bootstrap site.

    ```HTML
    <div class="container"></div>
    <div class="container-fluid"></div>
    ```

    i. `container` - sets a responsive, fixed-width container. For each of four viewport ranges, the container width will remain the same until it is narrowed or widened to the next range.

        -  less than 768px — extra small
        -  768-991px — small
        -  992-1199px — medium
        -  greater than 1199px — large

    ii. `container-fluid` - sets a responsive container that fills the viewport, regardless of the viewport's width.

3. The Bootstrap `navbar` class with `navbar-default` or `navbar-inverse` styles the appearance of the navigation bar.

4. The navigation bar can be fixed to the top or bottom of a webpage with the `navbar-fixed-top` or `navbar-fixed-bottom` class.

5. Elements in the navigation bar can be shifted to the left or right with the `navbar-left` and `navbar-right` classes.

6. The `jumbotron` and `jumbotron-fluid` classes makes the content within its container appear more prominently.

7. The Bootstrap grid system requires a `div` of class `row` for each row in the grid.

8. The Bootstrap grid system requires content elements that take up anywhere from one to twelve columns.

9. The Bootstrap grid system can be used as a responsive layout framework by using a few of the following prefixes for each content element: `xs`, `sm`, `md`, or `lg`.

    ```HTML
    <div class="row">
      <div class="col-xs-12 col-sm-9 col-md-6 col-lg-3">
      </div>
    </div>
    ```

10. Bootstrap provides built-in button and button-sizing classes.

11. Built-in Bootstrap styles can be overwritten by setting property values with the same selectors in a local CSS document.
