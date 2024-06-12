# Using Bootstrap Styles

As a developer tasked with designing a website for the Little Lemon Restaurant, you need to ensure the site adapts to various devices, platforms, and screen sizes. However, you don't have to redesign the website for each device individually. This class introduces Bootstrap's CSS classes, infixes, and modifiers, which save time by leveraging a large CSS library created by Bootstrap developers. Understanding infixes and modifiers is crucial.

Bootstrap uses class infixes for responsive breakpoints, which are specific screen widths that trigger layout changes. The breakpoints include:

- **Extra small** (<576px, default)
- **Small** (≥576px, SM)
- **Medium** (≥768px, MD)
- **Large** (≥992px, LG)
- **Extra large** (≥1200px, XL)
- **Extra extra large** (≥1400px, XXL)

The default breakpoint is for extra small screens, as Bootstrap is mobile-first.

Bootstrap components offer reusable UI styles and elements. Modifiers change the appearance of elements, like alert messages. For example, `alert-primary` uses the primary color (blue), while `alert-danger` changes it to red for error messages. You can modify CSS classes for different screen sizes by adding infixes, such as `col-LG-6` for large screens. This approach helps create responsive designs efficiently.

### Source Code

```

<!DOCTYPE html>
<html>
  <head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="col-lg-6">
          <div class="alert alert-primary" role="alert">
            A message.
          </div>
        </div>
      </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```
