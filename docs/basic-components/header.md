---
sidebar_position: 1
---

# Header

1. **Simple Navigation Header:**
   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container">
           <a class="navbar-brand" href="#">Your Logo</a>
           <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNav">
               <ul class="navbar-nav ml-auto">
                   <li class="nav-item active">
                       <a class="nav-link" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Services</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Contact</a>
                   </li>
               </ul>
           </div>
       </div>
   </nav>
   ```
   ![image](https://github.com/user-attachments/assets/de64cf3f-4e43-4e21-991d-d87c4491709d)

2. **Centered Logo with Minimal Links:**
   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container">
           <a class="navbar-brand mx-auto" href="#">Your Logo</a>
           <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNav">
               <ul class="navbar-nav ml-auto">
                   <li class="nav-item active">
                       <a class="nav-link" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Services</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Contact</a>
                   </li>
               </ul>
           </div>
       </div>
   </nav>
   ```

3. **Full-width Header with Centered Logo:**
   ```html
   <header>
       <nav class="navbar navbar-expand-lg navbar-light bg-light">
           <div class="container-fluid">
               <a class="navbar-brand mx-auto" href="#">Your Logo</a>
           </div>
       </nav>
   </header>
   ```

4. **Header with Dropdown Menu:**
   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container">
           <a class="navbar-brand" href="#">Your Logo</a>
           <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNavDropdown">
               <ul class="navbar-nav ml-auto">
                   <li class="nav-item active">
                       <a class="nav-link" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item dropdown">
                       <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                           Services
                       </a>
                       <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                           <a class="dropdown-item" href="#">Service 1</a>
                           <a class="dropdown-item" href="#">Service 2</a>
                       </div>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Contact</a>
                   </li>
               </ul>
           </div>
       </div>
   </nav>
   ```

5. **Header with Search Bar:**
   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container">
           <a class="navbar-brand" href="#">Your Logo</a>
           <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNavDropdown">
               <ul class="navbar-nav mr-auto">
                   <li class="nav-item active">
                       <a class="nav-link" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Services</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Contact</a>
                   </li>
               </ul>
               <form class="form-inline my-2 my-lg-0">
                   <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                   <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
               </form>
           </div>
       </div>
   </nav>
   ```
