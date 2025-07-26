<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">MyWebsite</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome to My Website</h1>
    <p>We design beautiful and responsive websites</p>
    <a href="#" class="btn">Learn More</a>
  </section>

  <!-- About Section -->
  <section class="about">
    <h2>About Us</h2>
    <p>We are a team of creative designers and developers passionate about building great websites.</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 MyWebsite. All rights reserved.</p>
  </footer>
</body>
</html><!DOCTYPE html>
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
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f4f4f4;
}

/* Header */
header {
  background-color: #333;
  color: #fff;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo {
  font-size: 24px;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}

nav ul li a:hover {
  text-decoration: underline;
}

/* Hero Section */
.hero {
  background: linear-gradient(to right, #0077ff, #00c6ff);
  color: white;
  padding: 100px 20px;
  text-align: center;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 20px;
  margin-bottom: 30px;
}

.btn {
  display: inline-block;
  padding: 12px 25px;
  background-color: #fff;
  color: #0077ff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.btn:hover {
  background-color: #e6e6e6;
}

/* About Section */
.about {
  padding: 60px 20px;
  text-align: center;
  background-color: #fff;
}

.about h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}