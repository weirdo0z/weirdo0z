## Hi there 👋, I'm weirdo0z!

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=weirdo0z&layout=compact&theme=dark&hide_border=true)](https://github.com/weirdo0z/)

## About Me

* Passionate about software development
* Currently working on the satellite operating system team
* Learning Rust, UI/UX, AI, and more
* Interested in contributing to open-source projects related to everything, especially frontend
* Honestly, I can't be headhunted because I'm just a high schooler

## 🛠️ Tech Stack

* **Languages:** TypeScript, JavaScript, Rust, Python, Brainf*ck (jk), and some "completely understood" languages
* **Frameworks:** React, Preact, Tauri, Actix, and some

## 🤝 Let's Connect

* Discord: weirdo_oz
* Instagram: [weird0.oz](https://www.instagram.com/weird0.oz/)
* Email: [7h3w3irdo0z@proton.me](<mailto:7h3w3irdo0z@proton.me>)

## ⚡️ Fun Facts

* I like Science, Math, and Linguistics so I can speak English and Japanese, learning Spanish and Chinese
* I like joking very much

## 🤣 Daily Joke (using JokeAPI)

<p align="center">Loading a funny joke...</p>
<p align="center"><a href="https://jokeapi.dev" target="_blank">Powered by JokeAPI</a></p>
<script>
fetch('https://v2.jokeapi.dev/joke/Any?blacklistFlags=nsfw,religious,political,racist,sexist&type=single')
.then(response => response.json())
.then(data => {
  if (data.type === 'single') {
    document.querySelector('p:nth-of-type(1)').innerHTML = data.joke;
  } else {
    document.querySelector('p:nth-of-type(1)').innerHTML = data.setup + '<br><br>' + data.delivery;
  }
})
.catch(error => {
  console.error('Error fetching joke:', error);
  document.querySelector('p:nth-of-type(1)').innerHTML = "Failed to load a joke. Please try again later.";
});
</script>

---

Feel free to contribute to my repositories or reach out to me!

<!--
**weirdo0z/weirdo0z** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
