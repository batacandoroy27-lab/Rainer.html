<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Profile</title>

  <style>
    body {
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: #333333;
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 40px 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      box-sizing: border-box;
    }

    .profile-card {
      background-color: #ffffff;
      max-width: 500px;
      width: 100%;
      border-radius: 16px;
      padding: 30px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      text-align: center;
    }

    .profile-img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      opacity: 0.85;
      border: 4px solid #2a5298;
      transition: opacity 0.3s ease;
    }

    .profile-img:hover {
      opacity: 1;
    }

    h1 {
      font-size: 28px;
      font-weight: 700;
      text-transform: uppercase;
      color: #1e3c72;
      margin: 15px 0 5px 0;
      letter-spacing: 1px;
    }

    .title {
      font-style: italic;
      color: #666666;
      font-size: 16px;
      margin-bottom: 20px;
    }

    .bio {
      line-height: 1.6;
      color: #444444;
      font-size: 15px;
      margin-bottom: 25px;
    }

    .skills-heading {
      font-size: 18px;
      color: #1e3c72;
      margin-bottom: 12px;
      text-align: left;
    }

    .skills-container {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      justify-content: center;
    }

    .skill-tag {
      background-color: #eef2f7;
      color: #2a5298;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: 600;
    }
  </style>
</head>

<body>

  <main class="profile-card">

    <img
      class="profile-img"
      src="https://drive.google.com/thumbnail?id=1QYpKxe23kdmhOwVnCwdoSJH2uwo5BlaH&sz=w500"
      alt="My Picture"
    >

    <h1>Ryn B. Alcayde</h1>

    <p class="title">ICT Senior High School Student</p>

    <p class="bio">
      Welcome to my web profile! I am an aspiring web designer and developer passionate about creating clean, accessible, and user-friendly digital experiences.
    </p>

    <div class="skills-heading">Skills & Interests</div>

    <div class="skills-container">
      <span class="skill-tag">HTML5</span>
      <span class="skill-tag">CSS3</span>
      <span class="skill-tag">Drawing</span>
      <span class="skill-tag">Web Development</span>
    </div>

  </main>

</body>
</html>
