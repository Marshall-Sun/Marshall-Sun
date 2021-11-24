## Hi, welcome to Marshall Sun's user page! 👋

```javascript
class MySelf {
  constructor() {
    if (!MySelf.instance) {
      const data = Symbol();
      this[data] = {
        name: "Marshall Sun",
        university: "Northeastern University",
        company: "Bytedance",
        github: "https://github.com/Marshall-Sun",
        blog: "https://msun.site",
      };
      this.introduce = () => console.table(this[data]);
      MySelf.instance = this;
    }
    return MySelf.instance;
  }
}
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marshall-sun&hide=html&hide_border=true&title_color=87c438&layout=compact"/>
</p>
