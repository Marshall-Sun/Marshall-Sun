## Hi, welcome to Marshall Sun's user center! 👋

<div style="display: flex">
<div style="width: 50%">

```javascript
const MySelf = (function () {
  let instance = null;
  return function () {
    this.personalData = {
      name: "Marshall Sun",
      university: "Northeastern University",
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

</div>

<div style="width: 50%">
<a href="#"><img src="https://github-readme-stats.vercel.app/api?username=marshall-sun&hide_border=true&show_icons=true&theme=buefy&icon_color=87c438&title_color=87c438&line_height=33&include_all_commits=true&count_private=true"/></a>
<a href="#"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marshall-sun&hide=html&hide_border=true&icon_color=87c438&title_color=87c438&layout=compact"/></a>
</div>

</div>
