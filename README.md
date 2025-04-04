<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
  :root {
    --primary-color: #3498db;
    --secondary-color: #2ecc71;
    --dark-color: #2c3e50;
    --light-color: #ecf0f1;
    --accent-color: #e74c3c;
  }
  
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f9f9f9;
  }
  
  header {
    text-align: center;
    margin-bottom: 30px;
    padding: 20px;
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  h1 {
    margin: 0;
    font-size: 2.5rem;
    animation: fadeIn 1s ease-in;
  }
  
  h3 {
    margin: 10px 0 0;
    font-weight: 400;
    opacity: 0.9;
  }
  
  .section {
    background: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s ease;
  }
  
  .section:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
  }
  
  .social-links, .languages-icons {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
  }
  
  .social-links a, .languages-icons a {
    transition: transform 0.3s ease;
  }
  
  .social-links a:hover, .languages-icons a:hover {
    transform: scale(1.2);
  }
  
  .stats-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    gap: 20px;
  }
  
  .stats-container img {
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    flex: 1;
    min-width: 300px;
  }
  
  .footer {
    text-align: center;
    margin-top: 30px;
    padding: 15px;
    color: #7f8c8d;
    font-size: 0.9rem;
  }
  
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  
  /* Pulse animation for profile views */
  .pulse {
    animation: pulse 2s infinite;
    display: inline-block;
  }
  
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
  }
  
  /* Responsive adjustments */
  @media (max-width: 600px) {
    h1 {
      font-size: 2rem;
    }
    
    .stats-container img {
      min-width: 100%;
    }
  }
</style>
    <title>Senithu Thisas | GitHub Profile</title>
</head>
<body>

<header>
    <h1>Hi 👋, I'm Senithu Thisas</h1>
    <h3>🎓 First-year Software Engineering student passionate about building creative and impactful software.</h3>
</header>

<div class="section">
    <p align="center"> 
        <span class="pulse">
            <img src="https://komarev.com/ghpvc/?username=senithuthisas&label=Profile%20views&color=0e75b6&style=flat" alt="senithuthisas" />
        </span>
    </p>
</div>

<div class="section">
    <h3>🌐 Connect with me:</h3>
    <p class="social-links">
        <a href="https://twitter.com/senithuthisas" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="40" width="40" /></a>
        <a href="https://linkedin.com/in/senithu-ekenayake" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="40" /></a>
        <a href="https://fb.com/senithu.ekenayake" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="40" width="40" /></a>
        <a href="https://www.youtube.com/c/senithu-thisas" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="40" width="40" /></a>
        <a href="https://github.com/senithuthisas" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="GitHub" height="40" width="40" /></a>
    </p>
</div>

<div class="section">
    <h3>🛠️ Languages and Tools:</h3>
    <p class="languages-icons">
        <a href="https://developer.android.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="50" height="50" /></a>
        <a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="50" height="50" /></a>
        <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="50" height="50" /></a>
        <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="50" height="50" /></a>
        <a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="50" height="50" /></a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="50" height="50" /></a>
        <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="50" height="50" /></a>
        <a href="https://www.php.net" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="50" height="50" /></a>
        <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="50" height="50" /></a>
    </p>
</div>

<div class="section">
    <h3>📊 GitHub Stats:</h3>
    <div class="stats-container">
        <img src="https://github-readme-stats.vercel.app/api?username=senithuthisas&show_icons=true&theme=default&hide_border=true&count_private=true" alt="senithuthisas" />
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=senithuthisas&layout=compact&theme=default&hide_border=true" alt="senithuthisas" />
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=senithuthisas&theme=default&hide_border=true" alt="senithuthisas" />
    </div>
</div>

<div class="section">
    <h3>🌟 Featured Projects</h3>
    <p>Coming soon! I'm currently working on some exciting projects that I'll be sharing here.</p>
    <p>Stay tuned for updates!</p>
</div>

<footer class="footer">
    <p>✨ Created with ❤️ by Senithu Thisas ✨</p>
    <p>📧 Reach me at: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
</footer>

</body>
</html>
