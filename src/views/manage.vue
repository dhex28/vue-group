<template>
  <div>
    <!-- Your existing navigation bar code -->
    <nav class="navbar navbar-dark bg-black fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Dev</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
          <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Menu</h5>
            <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
          </div>
          <div class="offcanvas-body">
            <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="/">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li>
                    <hr class="dropdown-divider">
                  </li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
            </ul>
            
            <form class="d-flex mt-3" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </div>
    </nav>

    <!-- Your manage page content -->
    <div class="d-flex flex-column justify-content-center align-items-center custom-bg-color" style="min-height: calc(100vh - 56px);">
      <h2 class="text-white mb-4">THIS IS OUR MANAGE PAGE</h2> <!-- Add margin-bottom class to create space -->
      
      <!-- Add the buttons here -->
      <div class="d-flex justify-content-center">
        <button type="button" class="btn btn-outline-primary mx-2">Primary</button> <!-- Add margin around each button -->
        <button type="button" class="btn btn-outline-secondary mx-2">Secondary</button>
        <a type="button" href="/" class="btn btn-outline-success mx-2">Success</a>
        <button type="button" class="btn btn-outline-danger mx-2">Danger</button>
        <button type="button" class="btn btn-outline-warning mx-2">Warning</button>
        <button type="button" class="btn btn-outline-info mx-2">Info</button>
        <button type="button" class="btn btn-outline-light mx-2">Light</button>
        <button type="button" class="btn btn-outline-dark mx-2">Dark</button>
      </div>
    </div>
  </div>
</template>

<style>
  /* Define a custom background color */
  .custom-bg-color {
    background-color: #262727; /* Replace with your desired background color */
  }

  /* Add any additional custom styling as needed */
</style>
