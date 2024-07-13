1. **Minimalist Navbar with Logo and Dropdown Menu**
   
   ![image](https://github.com/user-attachments/assets/16771330-e3ac-45a9-b7d2-ba7fd6b2fc5b)

   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container-fluid">
           <a class="navbar-brand" href="#">Your Logo</a>
           <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNav">
               <ul class="navbar-nav ms-auto">
                   <li class="nav-item">
                       <a class="nav-link active" aria-current="page" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item dropdown">
                       <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                           Services
                       </a>
                       <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                           <li><a class="dropdown-item" href="#">Service 1</a></li>
                           <li><a class="dropdown-item" href="#">Service 2</a></li>
                           <li><hr class="dropdown-divider"></li>
                           <li><a class="dropdown-item" href="#">All Services</a></li>
                       </ul>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">Contact</a>
                   </li>
               </ul>
           </div>
       </div>
   </nav>
   ```

2. **Centered Logo with Search Box**
   ![image](https://github.com/user-attachments/assets/4fe7d28b-8103-4a08-beae-79942c43d729)

   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container-fluid">
           <a class="navbar-brand mx-auto" href="#">Your Logo</a>
           <div class="d-flex">
               <form class="d-flex">
                   <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                   <button class="btn btn-outline-success" type="submit">Search</button>
               </form>
           </div>
       </div>
   </nav>
   ```

3. **Header with Hero Image and Call to Action Button**
   ![image](https://github.com/user-attachments/assets/8227b2f1-915e-48f0-91d9-fcec8ea197b8)

   ```html
   <header class="bg-dark text-white py-5">
       <div class="container">
           <div class="row align-items-center">
               <div class="col-md-6">
                   <h1>Your Site Name</h1>
                   <p class="lead">A brief description of your site.</p>
                   <a class="btn btn-primary btn-lg" href="#" role="button">Get Started</a>
               </div>
               <div class="col-md-6">
                   <img src="hero-image.jpg" class="img-fluid" alt="Hero Image">
               </div>
           </div>
       </div>
   </header>
   ```

4. **Transparent Navbar with Brand Name and Icons**
   ![image](https://github.com/user-attachments/assets/458b8e29-b8d0-4d0c-968f-e834ef7ff2b2)

   ```html
   <nav class="navbar navbar-expand-lg navbar-light fixed-top" style="background-color: rgba(255,255,255,0.8);">
       <div class="container-fluid">
           <a class="navbar-brand" href="#">Your Brand</a>
           <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
               <div class="navbar-nav">
                   <a class="nav-link active" aria-current="page" href="#"><i class="bi bi-house-door"></i> Home</a>
                   <a class="nav-link" href="#"><i class="bi bi-info-circle"></i> About</a>
                   <a class="nav-link" href="#"><i class="bi bi-envelope"></i> Contact</a>
               </div>
           </div>
       </div>
   </nav>
   ```

5. **Navbar with Brand Name and Dropdown User Menu**
   ![image](https://github.com/user-attachments/assets/1ef3e317-f259-4083-94a5-76635f7d1d41)

   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <div class="container-fluid">
           <a class="navbar-brand" href="#">Your Brand</a>
           <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
               <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarSupportedContent">
               <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                   <li class="nav-item">
                       <a class="nav-link active" aria-current="page" href="#">Home</a>
                   </li>
                   <li class="nav-item">
                       <a class="nav-link" href="#">About</a>
                   </li>
                   <li class="nav-item dropdown">
                       <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                           User
                       </a>
                       <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                           <li><a class="dropdown-item" href="#">Profile</a></li>
                           <li><a class="dropdown-item" href="#">Settings</a></li>
                           <li><hr class="dropdown-divider"></li>
                           <li><a class="dropdown-item" href="#">Logout</a></li>
                       </ul>
                   </li>
               </ul>
           </div>
       </div>
   </nav>
   ```
