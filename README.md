<div id="github-profile">
  <!-- Kartu profil GitHub tema gelap -->
  <div class="github-card" data-theme="github_dark">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=wildy8283&theme=github_dark">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=wildy8283&theme=github_dark">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=wildy8283&theme=github_dark">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=wildy8283&theme=github_dark">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=wildy8283&theme=github_dark&utcOffset=7">
  </div>

  <!-- Kartu profil GitHub tema terang -->
  <div class="github-card" data-theme="github">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=wildy8283&theme=github">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=wildy8283&theme=github">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=wildy8283&theme=github">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=wildy8283&theme=github">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=wildy8283&theme=github&utcOffset=7">
  </div>
</div>

<script>
  // Mendeteksi mode tema
  const prefersDarkMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  // Memilih tema kartu profil GitHub
  const githubCards = document.querySelectorAll('.github-card');
  githubCards.forEach(card => {
    const theme = card.getAttribute('data-theme');
    if (prefersDarkMode && theme === 'github') {
      card.style.display = 'none';
    } else if (!prefersDarkMode && theme === 'github_dark') {
      card.style.display = 'none';
    }
  });
</script>

## Hi, I'm Wildy! 👋
I am a software developer who specializes in web and mobile application development, server development, and network engineering. I enjoy creating technology solutions that can help solve real-world problems.

## 🔭 Technologies and Programming Languages I'm Proficient In
* PHP
* JavaScript
* Python
* Golang
* Bash/Shell
* Perl

## 🌱 I'm Currently Learning
* c++
* Java

## 📫 How to Reach Me?
You can reach me via email at admin@wildy.my.id

## ⚡ Fun Facts About Me
* I am a coffee lover and enjoy trying coffee from different places.
* I am always eager to learn and explore new technologies.
* I am from Indonesia and proud of my heritage.
