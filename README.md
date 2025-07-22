<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Group 5's Malupitan Website</title>
  <style>
    :root {
      --bg-color: #d4fdd4;
      --text-color: #000;
      --heading-color: #005500;
      --link-color: #0066cc;
      --card-bg: #ffffff;
    }

    body.dark {
      --bg-color: #121212;
      --text-color: #e0e0e0;
      --heading-color: #90ee90;
      --link-color: #77dd77;
      --card-bg: #1e1e1e;
    }

    body {
      margin: 0;
      padding: 20px;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      transition: background-color 0.3s, color 0.3s;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      text-align: center;
    }

    h1, h2 {
      color: var(--heading-color);
    }

    a {
      color: var(--link-color);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    li {
      margin: 5px 0;
    }

    img, video, audio {
      margin: 10px 0;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .toggle-btn {
      position: fixed;
      top: 15px;
      right: 15px;
      padding: 12px 20px;
      background-color: var(--card-bg);
      color: var(--text-color);
      border: 1px solid #ccc;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
      z-index: 1000;
      transition: background-color 0.3s, color 0.3s;
    }

    .section {
      background-color: var(--card-bg);
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 12px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

  <button class="toggle-btn" onclick="toggleMode()"> 🧔🏻‍♂️Light or Dark🧔🏿‍♂️</button>

  <div class="container">
    <div class="section">
      <h1>Group 5's Malupitan Website</h1>
    </div>

    <div class="section">
      <h2>Introduction to HTML: A Guide to Beginners</h2>
      <h3>HTML Tutorial Image</h3>
      <picture>
        <img src="https://henryegloff.com/media/How-to-Code-a-Basic-Webpage-Using-HTML-Tutorial-2.jpg" alt="HTML Tutorial Image" style="width: 45%; height: auto;">
      </picture>
    </div>

    <div class="section">
      <h1>What is HTML?</h1>
      <p>HTML stands for HyperText Markup Language, and it is the standard language used to create webpages. When building websites, learning HTML is the foundational first step. It uses markup to describe the structure and content of web pages.</p>
    </div>

    <div class="section">
      <h1>Purpose of HTML</h1>
      <p>The primary purpose of HTML is to establish the structure and presentation of content on the web. Rather than being a programming language that performs logic or computations, HTML is a markup language that uses specially designated codes called tags to organize and define various elements within a webpage. These elements include headings, paragraphs, tables, hyperlinks, images, multimedia, and more. Each tag serves as an instruction to the web browser, indicating how specific content should appear or behave when the page is displayed. While these tags are not visible to the user when viewing the webpage, they play a crucial behind-the-scenes role in shaping the layout, formatting, and overall user experience. By clearly outlining the role and relationship of each element, HTML provides the structural foundation upon which all websites are built.</p>
    </div>

    <div class="section">
      <h1>Links to HTML Tutorials</h1>
      <ul>
        <li><a href="https://www.youtube.com/watch?v=FQdaUv95mR8">Kevin Strevart - HTML Tutorial for Beginners</a></li>
        <li><a href="https://www.youtube.com/watch?v=vY2xUc4TVmY">The Coding Sloth - HTML Tutorial</a></li>
        <li><a href="https://www.youtube.com/watch?v=HD13eq_Pmp8">Bro Code - HTML for Beginners</a></li>
      </ul>
    </div>

    <div class="section">
      <h2>Websites for Developing HTML Skills</h2>
      <ul>
        <li><a href="https://www.w3schools.com/html/">W3Schools HTML Tutorial</a></li>
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML">MDN Web Docs - HTML</a></li>
        <li><a href="https://www.freecodecamp.org/news/html-tutorial-for-beginners/">FreeCodeCamp HTML Tutorial</a></li>
      </ul>
    </div>

    <div class="section">
      <h1>Test Runs of Images, Audio, and Video</h1>

      <h2>Images of Memes 'cause why not?</h2>
      <img src="https://miro.medium.com/v2/resize:fit:1400/1*GI-td9gs8D5OKZd19mAOqA.png" alt="Meme 1" style="width: 45%;">
      <br>
      <img src="https://preview.redd.it/something-always-has-to-go-wrong-with-it-v0-g1xbe9pwkg3d1.jpeg?auto=webp&s=a7e380424067fe8c2809bb2255c14d0dd4e057be" alt="Meme 2" style="width: 45%;">
      <br>
      <img src="https://i0.wp.com/copyhackers.com/wp-content/uploads/2020/06/91080453_10163333459945083_2233604339354566656_n.jpg?resize=521%2C527&ssl=1" alt="Meme 3" style="width: 45%;">
    </div>

    <div class="section">
      <h2>Sample Audio</h2>
      <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </div>

    <div class="section">
      <h2>Sample Video</h2>
      <video controls width="640" height="360">
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>

  <script>
    function toggleMode() {
      document.body.classList.toggle("dark");
    }
  </script>

</body>
</html>
