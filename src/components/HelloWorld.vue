<template>
  <nav class="navbar navbar-expand-lg custom-bg-color">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <a class="navbar-brand text-white" href="#">Lowkey Dev</a>
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="/manage">Manage</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success text-white" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div class="d-flex justify-content-center align-items-center custom-bg-color" style="min-height: 100vh;">
    <h1 class="text-white">THIS IS OUR HOMEPAGE</h1>
  </div>
</template>

<style>
  /* Define a custom background color */
  .custom-bg-color {
    background-color: black; /* Set the navbar background color to black */
  }
</style>
