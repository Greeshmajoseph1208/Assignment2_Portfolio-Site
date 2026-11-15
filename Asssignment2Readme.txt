Font Awesome

Home icon - <i class="fa-solid fa-house"></i>
Project- <i class="fa-solid fa-book"></i>
Contact - <i class="fa-solid fa-phone"></i>
Business icon in project page - <i class="fa-solid fa-business-time" style="color: rgb(175, 19, 0);"></i>
Python icon in project page - <i class="fa-brands fa-python" style="color: rgb(175, 19, 0);"></i>
Internet icon in project page - <i class="fa-solid fa-house-signal" style="color: rgb(175, 19, 0);"></i>
Portfolio Icon in project page - <i class="fa-solid fa-briefcase" style="color: rgb(175, 19, 0);"></i>
Home user icon in home page - <i class="fa-solid fa-house-user" style="color: rgb(175, 19, 0);"></i>
Linked in footer icon - <i class="fa-brands fa-linkedin" style="color: rgb(113, 165, 243);"></i>
GitHub footer icon - <i class="fa-brands fa-square-github" style="color: rgb(113, 165, 243);"></i>

Bootstrap

1. Bootstrap code adapted for header & footer from bootstrap Navbar: (https://getbootstrap.com/docs/6.0/components/navbar/)

<nav class="navbar md:navbar-expand bg-1">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="btn-icon navbar-toggler" type="button" data-bs-toggle="drawer" data-bs-target="#navbarDrawer" aria-controls="navbarDrawer" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon" aria-hidden="true"></span>
    </button>
    <dialog class="drawer drawer-end" tabindex="-1" id="navbarDrawer" aria-labelledby="navbarDrawerLabel">
      <div class="drawer-header">
        <h5 class="drawer-title" id="navbarDrawerLabel">Menu</h5>
        <button type="button" class="btn-close" data-bs-dismiss="drawer" aria-label="Close"></button>
      </div>
      <div class="drawer-body mb-2 md:mb-0">
        <ul class="nav navbar-nav me-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <button class="nav-link" type="button" data-bs-toggle="menu" aria-expanded="false">
              Menu
            </button>
            <div class="menu">
              <a class="menu-item" href="#">Action</a>
              <a class="menu-item" href="#">Another action</a>
              <hr class="menu-divider">
              <a class="menu-item" href="#">Something else here</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="hstack gap-2" role="search">
          <input class="form-control" type="search" placeholder="Search" aria-label="Search"/>
          <button class="btn-solid btn-icon theme-secondary" type="submit">
            <svg class="bi" width="16" height="16"><use href="#search" /></svg>
          </button>
        </form>
      </div>
    </dialog>
  </div>
</nav>


2. Button styling using bootstrap: <button type="button" class="btn btn-dark">Dark</button> 	(https://getbootstrap.com/docs/5.3/components/buttons/)

3. Bootstrap Image styling - <img src="..." class="img-fluid" alt="..."> (https://getbootstrap.com/docs/5.3/content/images/)
4. Bootstrap card style used to create projects page : <div class="card">
  <div class="card-header">
    Quote
  </div>
  <div class="card-body">
    <figure>
      <blockquote class="blockquote">
        <p>A well-known quote, contained in a blockquote element.</p>
      </blockquote>
      <figcaption class="blockquote-footer">
        Someone famous in <cite title="Source Title">Source Title</cite>
      </figcaption>
    </figure>
  </div>
</div>
(https://getbootstrap.com/docs/6.0/components/card/)

5. Bootstrap for video - https://getbootstrap.com/docs/6.0/utilities/object-fit/#video
