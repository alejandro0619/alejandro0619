<h1 align="center">Hi 👋, I'm Alejandro Lopez</h1>
<h3 align="center"> 💫 About me 💫 </h3>

```typescript
  class AboutMe {
    private age: number;
    private likes: string;

    constructor(params:{age: number, likes: string}){
      const {age, likes } =  params;
      this.age = age;
      this.likes = likes;
    }
    get info(): string {
      return `I'm ${this.age} Backend developer from venezuela ${this.likes}`
    }
}
const Me = new AboutMe({
  age: 16,
  likes: `
  who loves learning new technologies. I've been learning programming for 2 years
  and I feel very comfy trying new things outta' my comfort zone`
});
console.log(Me.info);
```

----
- 💻 Some of my projects: 
  -  🌑 [Tsukiapp](https://github.com/orgs/Tsukiapp/) Searching and tracking your favorite animes was never so easy! 🌌
       - 🎇[MAL-Scrapper](https://github.com/orgs/Tsukiapp/MAL-Scrapper) It's [MyAnimeList.net](https://myanimelist.net/) scrapper created for Tsukiapp.
       - 💻 [Tsuki API](https://github.com/Tsukiapp/Tsuki-API) It's an API to retrieve information about anime, mangas and new about these topics.
  -  🧨 [Kanzen](https://github.com/alejandro0619/Kanzen-CLI) A minimalist CLI application to download books direct from libgen created in Typescript.
  -  💸 [Fixer-Wrapper](https://github.com/alejandro0619/Fixer-wrapper) Useful [fixer](https://fixer.io) Javascript / Typescript wrapper.
  -  🍣 [Maki](https://github.com/alejandro0619/Maki) A password generator and manager CLI application created in Typescript.
  
- 🌱 I’m currently learning: Chinese simplified, Math and algorithms
- 👨‍💻 All of my projects are available at [https://github.com/alejandro0619](https://github.com/alejandro0619)
- 📝 I regularly write articles on [https://dev.to/spaghetti_rs](https://dev.to/spaghetti_rs)
- 💬 Ask me about Typescript, Javascript, Nodejs, Deno, mongoDB, heroku.
- 📫 How to reach me alejandrolpz0619@gmail.com
----
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=alejandro0619&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)


