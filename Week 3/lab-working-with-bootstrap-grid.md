# Lab: Working with Bootstrap Grid

In this exercise, you will practice building a webpage using the Bootstrap Grid.

## Goal

Create a two-column food menu for Little Lemon.

## Objectives

- Set up the Bootstrap container.
- Display the Little Lemon logo in the top center of the webpage using Bootstrap.
- Display the food menu in two columns using Bootstrap Grid.

### Source Code

```
<!DOCTYPE html>
<html>
<head>
    <title>Little Lemon</title>
    <link href="bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <script src="bootstrap.bundle.min.js"></script>
    <div class="container">
        <div class="row">
          <div class="col-12">
              <div class="text-center">
                <img src="logo.png" class="img-fluid">
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
                <h2>Falafel</h2>
                 <p>Chickpea, herbs, spices.</p>
                 <h2>Fried Calamari</h2>
                 <p>Squid, buttermilk.</p>
            </div>
            <div class="col-12 col-lg-6">
                <h2>Pasta Salad</h2>
                 <p>Lettuce, vegetables, mozzarella.</p>
                 <h2>Greek Salad</h2>
                 <p>Cucumbers, onion, feta cheese.</p>
            </div>
        </div>
    </div>
</body>
</html>
```
