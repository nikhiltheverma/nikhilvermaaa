<h1 align="center">Konnichiwa! I'm Nikhil Verma</h1>
<h3 align="center">Versatile In Web Development, Ethical Hacking & Cyber Security | Engaged in multiple endeavors still diving into various interests & exploring myriad obsessions</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=nikhilvermaaa&label=Profile%20views&color=0e75b6&style=flat" alt="nikhilvermaaa" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=nikhilvermaaa" alt="nikhilvermaaa" /></a> </p>

<p align="left"> <a href="https://twitter.com/youtubenostrayt" target="blank"><img src="https://img.shields.io/twitter/follow/youtubenostrayt?logo=twitter&style=for-the-badge" alt="youtubenostrayt" /></a> </p>

<img align="right" height="150" src="https://cdn.jsdelivr.net/gh/nikhilvermaaa/sololeveling@5c50b308385a3946ae8bda3b42956de50bd7bfe2/https%20__youtu_be_aLxToedAgN4.gif"  />

name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

- 🔭 I’m currently working on **Javascript & Backend**

- 🌱 I’m currently learning **Javascript**

- 👯 I’m looking to collaborate on **any type of activities**

- 🤝 I’m looking for help with **Ethical Hacking & Cybersecurity**

- 👨‍💻 All of my projects are available at [https://github.com/nikhilvermaaa](https://github.com/nikhilvermaaa)

- 📝 I regularly write articles on [anikatana.blogspot.com](anikatana.blogspot.com)

- 📫 How to reach me **nikhilvermaultimate@gmail.com**

- 📄 More About Me [bit.ly/nikhilvermaaa](bit.ly/nikhilvermaaa)

- ⚡ Fun fact **Imma Multitasker**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://codepen.io/nikhilvermaaa" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="nikhilvermaaa" height="30" width="40" /></a>
<a href="https://twitter.com/youtubenostrayt" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="youtubenostrayt" height="30" width="40" /></a>
<a href="https://linkedin.com/in/nikhilvermaaa" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nikhilvermaaa" height="30" width="40" /></a>
<a href="https://fb.com/nikhilvermaaaa" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="nikhilvermaaaa" height="30" width="40" /></a>
<a href="https://instagram.com/officialnostrayt" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="officialnostrayt" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/nostra yt" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="nostra yt" height="30" width="40" /></a>
<a href="https://www.codechef.com/users/nikhilvermaaa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" alt="nikhilvermaaa" height="30" width="40" /></a>
<a href="https://www.hackerrank.com/nikhilvermaulti1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="nikhilvermaulti1" height="30" width="40" /></a>
<a href="https://www.leetcode.com/nikhilvermaaa" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="nikhilvermaaa" height="30" width="40" /></a>
<a href="https://www.hackerearth.com/@nikhilvermaultimate" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerearth.svg" alt="@nikhilvermaultimate" height="30" width="40" /></a>
<a href="https://discord.gg/6MePEjThMU" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="6MePEjThMU" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/nikhilvermaaa"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="nikhilvermaaa" /></a></p><br><br>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=nikhilvermaaa&show_icons=true&locale=en&layout=compact" alt="nikhilvermaaa" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=nikhilvermaaa&show_icons=true&locale=en" alt="nikhilvermaaa" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=nikhilvermaaa&" alt="nikhilvermaaa" /></p>

