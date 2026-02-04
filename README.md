<h1 align="center">Hi 👋, I'm Yassine Bourazza</h1>
<h3 align="center">A passionate developer in the making | Talented student at Zone01 Oujda</h3>

<hr/>



🌟 I’m currently focused on mastering the fundamentals of <strong>Go (Golang)</strong> at <a href="https://zone01oujda.ma/">Zone01 Oujda</a><br/>

💡 Fascinated by low-level programming, performance optimization, and problem-solving<br/>

🎯 On my roadmap:<br/>
→ JavaScript (Frontend & Backend)<br/>
→ Rust (Systems programming)<br/>
→ Java (OOP & Enterprise development)<br/>

📈 Always seeking new challenges, learning opportunities, and collaborative growth.


<hr/>

<div align="center">

<div id="github-stats"></div>

<script>
async function fetchGitHubStats(username) {
    const res = await fetch(`https://api.github.com/users/${username}/repos`);
    const repos = await res.json();

    let languages = {};
    repos.forEach(repo => {
        if (repo.language) {
            languages[repo.language] = (languages[repo.language] || 0) + 1;
        }
    });

    let html = `<h2>${username}'s Top Languages</h2><ul>`;
    for (let lang in languages) {
        html += `<li>${lang}: ${languages[lang]}</li>`;
    }
    html += '</ul>';

    document.getElementById('github-stats').innerHTML = html;
}

fetchGitHubStats('yassinebourazza');
</script>

</div>

<hr/>

<div align="center">

<h2>📊 GitHub Stats</h2>

<iframe 
    src="https://github-readme-stats.vercel.app/api?username=yassinebourazza&show_icons=true&theme=github_dark"
    style="width: 400px; height: 140px; border:0;">
</iframe>

<iframe 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=yassinebourazza&layout=compact&theme=github_dark"
    style="width: 400px; height: 140px; border:0;">
</iframe>

</div>

<hr/>

<div align="center">

<h2>📬 Contact Me</h2>

<a href="https://discordapp.com/users/1362166451401920702">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</a>
<a href="mailto:your.email@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/yassine-bourazza-49aa8235a">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</div>

<hr/>

<blockquote align="center">
  <p><em>"If you want to go fast, go alone. If you want to go far, go together."</em></p>
  <p>— <strong>Yassine Bourazza</strong></p>
</blockquote>


