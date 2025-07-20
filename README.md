<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Website</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <nav>
      <h1 class="logo">MyWebsite</h1>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Welcome to My Website</h2>
      <p>Your success starts here.</p>
      <a href="#" class="btn">Get Started</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 MyWebsite. All rights reserved.</p>
  </footer>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem 0;
}

nav {
  max-width: 1100px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

nav .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #f4b400;
}

.hero {
  background: url('https://source.unsplash.com/1600x600/?nature,technology') center/cover no-repeat;
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero-content {
  background: rgba(0,0,0,0.5);
  padding: 30px;
  border-radius: 8px;
  color: #fff;
}

.hero-content h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background: #f4b400;
  color: #333;
  text-decoration: none;
  border-radius: 4px;
  transition: background 0.3s ease;
}

.btn:hover {
  background: #e09c00;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 15px 0;
  margin-top: 30px;
}