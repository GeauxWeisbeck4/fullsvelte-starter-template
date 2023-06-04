<nav>
  <a class="navlink" href="/">Home</a>
  <a class="navlink" href="/about">About</a>
  <a class="navlink" href="/blog">Blog</a>
  <a class="navlink" href="/contact">Contact</a>
</nav>

<h1>Welcome to FullStackSvelte.dev</h1>
<p class="hero-text">All of the best from <a class="text-link" href="https://kit.svelte.dev">Full Stack Svelte</a>. See all the best apps, watch all the best tutorials, and read all the best blog posts - from the ultimate Full Stack Svelte Website around, Full Stack Svelte is the premier source when it comes to Full Stack Svelte applications.</p>


<div class="card-section">
  <h2>We bring you your favorite Svelte websites!</h2>
  <p> Who can forget the best sites on Svelte? Not us!</p>
<div class="cards">

<div class="card-one">
  <div class="card-img" style="background-image:url('https://res.cloudinary.com/tar-heel-dev-studio/image/upload/v1685514617/maxresdefault_gevol4.jpg')"></div>
  <div>
  <h3 class="card-text">I'm a card</h3>
  <p class="card-text">This is a card on the Svelte App!</p>
  
  <button class="card-button" method="@on-click">Click me</button>
  </div>
</div>

<div class="card-one">
  <div class="card-img" style="background-image:url('https://res.cloudinary.com/tar-heel-dev-studio/image/upload/v1685514617/maxresdefault_gevol4.jpg')"></div>
    <div>
      <h3 class="card-text">I'm a card</h3>
      <p class="card-text">This is a card on the Svelte App!</p>
  
      <button class="card-button" method="@on-click">Click me</button>
    </div>
  </div>

  <div class="card-one">
    <div class="card-img" style="background-image:url('https://res.cloudinary.com/tar-heel-dev-studio/image/upload/v1685514617/maxresdefault_gevol4.jpg')"></div>
      <div>
        <h3 class="card-text">I'm a card</h3>
        <p class="card-text">This is a card on the Svelte App!</p>
  
        <button class="card-button" method="@on-click">Click me</button>
      </div>
    </div>
  </div>
</div>

<footer>
  <ul class="navlist">
    <li>Home</li>
    <li>About</li>
    <li>Blog</li>
  </ul>
  <p class="footer-text">Hello I'm Andrew, Goodbye!</p>
</footer>

<style>
  nav {
    display: flex;
    background-color: #38c;
    color: white;
    text-decoration: none;
    font-size: 1.5em;
    border-radius: 10px;
    justify-content: space-evenly;
    gap: 10px;
  }
  .navlink {
    color: white;
    text-decoration:none;
  }
  .navlink:hover {
    color: #38c;
    background-color: white;
  }
  h1 {
    color: #37b;
    padding: 10px;
  }
  .hero-text {
    color: #37b;
    padding: 10px;
    font-size: 1.25em;
  }
  .text-link {
    color: orange;
    font-weight: bold;
  }
  .text-link:hover {
    color: blue;
    font-weight: bold;
  }
  .card-section {
    color: #37b;
  }
  .card-one {
    border: 1px solid black;
    border-radius: 10px;
    width: 350px;
  }
  .card-text {
    padding-left: 10px;
  }
  .card-button {
    background-color: green;
    color: white;
    padding: 5px 10px;
    border-radius: 10px;
    margin: 1em;
  }
  .card-img {
   background-size: cover;
   background-repeat: no-repeat;
   background-position: center center;
   height: 200px;
   border-radius: 10px;
}
  .cards {
    display: flex;
    gap: 10px;
    margin-left: 1rem;
  }
  .navlist {
    list-style: none;
  }
  footer {
    margin-top: 2rem;
    border-top: 3px solid black;
    display: flex;
    color: orange;
  }
  .footer-text {
    margin-left: 30px;
    color: #37b;
    font-weight: bold;
    font-size: 2rem;
  }
</style>
