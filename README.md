## Hi, welcome to Marshall Sun's user page! 👋

```javascript
const MySelf = (function () {
  let instance = null;
  return function () {
    this.personalData = {
      name: "Marshall Sun",
      university: "Northeastern University",
      intern: "Institute of Automation, Chinese Academy of Sciences",
      blog: "https://msun.work",
      github: "https://github.com/Marshall-Sun",
    };
    if (instance) return instance;
    return (instance = this);
  };
})();

MySelf.prototype.introduce = function () {
  console.table(this.personalData);
};
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marshall-sun&hide=html&hide_border=true&title_color=87c438&layout=compact"/>
</p>
