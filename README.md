<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Joy's Adventures</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Welcome to Joy's Adventures</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="faq.html">FAQ</a>
  </nav>
  <main>
    <h2>Snapshots of My Life</h2>
    <p>Hi, I'm Joy! This site is a scrapbook of my favorite memories, travels, and milestones.</p>
    <img src=![alt text](2128.jpeg) alt="Camping in Arizona">
    <img src=![alt text](6489.jpeg) alt="Hitchhiking in Thailand">
    <img src=![alt text](IMG_1108.jpeg) alt="Impromptu hike in Norway">
  </main>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About - Joy's Adventures</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>About Me</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="faq.html">FAQ</a>
  </nav>
  <main>
    <h2>Hi, I'm Joy!</h2>
    <p>I enjoy wandering around and sometimes I even remember (or other people remember) to take pictures.</p>
    <p>GitHub: <a href="https://github.com/joyexplores">joyexplores</a></p>
    <p>This site is my way of sharing my wanderings and remembering the random adventure i've had.</p>
  </main>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact - Joy's Adventures</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Contact Joy</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="faq.html">FAQ</a>
  </nav>
  <main>
    <form>
      <div>
        <label for="fname">First Name</label>
        <input type="text" id="fname" name="fname" required>
      </div>
      <div>
        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lname" required>
      </div>
      <div>
        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div>
        <label for="street">Street Address</label>
        <input type="text" id="street" name="street">
      </div>
      <div>
        <label for="city">City</label>
        <input type="text" id="city" name="city">
      </div>
      <div>
        <label for="state">State</label>
       <input type="text" id="state" name="state">
      </div>
      <div>
        <label for="zip">Zip Code</label>
        <input type="text" id="zip" name="zip" pattern="\d{5}" required>
      </div>
      <div>
        <label for="password">Password</label>
        <input type="password" id="password" name="password" required>
      </div>
      <div>
        <label for="favorite-trip">Favorite Trip</label>
        <input type="text" id="favorite-trip" name="favorite-trip">
      </div>
      <div>
        <label for="bucket-list">Bucket List Item</label>
        <input type="text" id="bucket-list" name="bucket-list">
      </div>
      <div>
        <label for="newsletter">Subscribe to Newsletter</label>
        <input type="checkbox" id="newsletter" name="newsletter">
      </div>
      <div class="full-width">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4"></textarea>
      </div>
      <div class="full-width">
        <button type="submit">Submit</button>
      </div>
    </form>
  </main>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>FAQ - Joy's Adventures</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header><h1>Frequently Asked Questions</h1></header>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="faq.html">FAQ</a>
  </nav>
  <main>
    <h2>Curious about Joy?</h2>
    <p><strong>Q: What inspired you to start this site?</strong><br>A: I needed to do this for an assignment and the photos I had on my phone were either screenshots of recipes or my wanderings.</p>
    <p><strong>Q: What's your favorite adventure?</strong><br>A: My most recent one: Surprise trip to explore Norway. Gorgeous country and can't wait to go back and explore more. </p>
    <p><strong>Q: Can I share my own story?</strong><br>A: Yes! Use the contact form to reach out.</p>
  </main>
</body>
</html>

