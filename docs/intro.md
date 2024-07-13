---
sidebar_position: 1
---

### Getting Started

#### 1. Include Bootstrap CDN
To use all the components mentioned below, make sure you include Bootstrap CDN in your web page. This is the first step to ensure all Bootstrap components can be used effectively.

```html
<!-- Include Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Include Bootstrap JavaScript (Optional, depending on component needs) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

#### 2. Using Bootstrap Components

Once you've included Bootstrap CDN, you can directly use the Bootstrap components listed earlier. Here are examples of how to use some components:

```html
<!-- Example of using Button -->
<button class="btn btn-primary">Primary Button</button>

<!-- Example of using Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">Brand Name</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About Us</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Example of using Form -->
<form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

### Notes:
- Make sure to adjust the above code to fit your web page structure and design.
- Bootstrap version 5.3.0 is used in the examples above. You can update the Bootstrap version as per your needs or preferences.
- Additional Bootstrap JavaScript (like `bootstrap.bundle.min.js`) is only necessary if you're using components that require JavaScript, such as menu toggler or modal.
- Customize the use of components according to specific needs and desired visual design.

Bahrul Rozak
