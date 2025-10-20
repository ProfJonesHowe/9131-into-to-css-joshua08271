<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My Bio Page</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <!-- 2) Link the stylesheet -->
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
<header>
  <h1>Joshua Lee</h1>
  <nav aria-label="Primary">
    <a href="#about">About</a> |
    <a href="#video">Video</a> |
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Me</h2>
    <p>Joshua Lee is an avid reader, who like to read sci-fi, fantasy, and historical fiction.
       Joshua Lee also likes to play badminton and other sports.</p>

    <figure>
      <img
        src="https://i0.wp.com/wearerestless.org/wp-content/uploads/2021/02/Reading-scaled.jpg?resize=1155%2C770&amp;ssl=1"
        alt="Person reading a book while sitting by a window"
        width="1155"
        height="770"
        loading="lazy"
        decoding="async"
      >
      <figcaption>Semantic code improves readability</figcaption>
    </figure>
  </section>

  <section id="video" aria-labelledby="video-heading">
    <h2 id="video-heading">My Favorite Video</h2>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/dQw4w9WgXcQ"
      title="Rick Astley — Never Gonna Give You Up (YouTube)"
      style="border:0"
      loading="lazy"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share; fullscreen"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen
    ></iframe>
  </section>

  <aside>
    <h3>Quick Facts</h3>
    <ul>
      <li>Favorite Food: Beef wellington</li>
      <li>Hobby: Reading</li>
      <li>Fun Fact: I can play the violin!</li>
    </ul>
  </aside>

  <section id="contact">
    <h2>Contact Form</h2>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="discordname">Discord Name:</label>
      <input type="text" id="discordname" name="discordname" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <button type="submit">Destroy</button>
    </form>
  </section>
</main>

<footer>
  <p>&copy; 2025 Joshua Lee. All rights reserved.</p>
</footer>
</body>
</html>
