<img src="./images/Margarita_Kravtsova_small.jpg" width=270px align=left />

# Margarita Kravtsova

### :link: Contact me:
      
[![Discord](https://img.shields.io/badge/-Rita%20(@yakravtsova)-141130?style=flat-square&logo=Discord)](https://discordapp.com/users/1075836895738728448)
[![Telegram](https://img.shields.io/badge/-@yakravtsova-141130?style=flat-square&logo=Telegram)](https://t.me/yakravtsova)
[![Gmail](https://img.shields.io/badge/-margaritaselez@gmail.com-141130?style=flat-square&logo=Gmail)](mailto:margaritaselez@gmail.com)
[![WhatsApp](https://img.shields.io/badge/-+79119758200-141130?style=flat-square&logo=WhatsApp)](https://wa.me/79119758200)

### About me:

I like to find solutions to complex problems and learn new things. I like web development because you can write code and immediately see the result of its execution in the browser. And you immerse in the fascinating process of debugging code and finding a solution if the result is not yet visible.

I graduated from a web development course at Yandex Practicum. Apparently my skill level is not enough for getting a job. That's why I keep learning and developing my skills.

### My priorities:

+ :woman_juggling: I study new technologies
+ :computer: I try to write clean code
+ :weight_lifting_woman: I practice a lot

### Languages and tools:

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-plain.svg" width=40px alt="Javascript" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-plain.svg" width=40px  alt="Typescript" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" width=40px alt="React" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" width=40px alt="Redux" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" width=40px alt="NodeJS" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" width=40px alt="express" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/vuejs/vuejs-original.svg" width=40px  alt="Vue" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" width=40px alt="Github" />
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original.svg" width=40px alt="Bootstrap" />
</div>

### Code example:

```typescript
const bfs = (graph: object): string[] => {
  if (typeof graph !== 'object' || Array.isArray(graph) || graph === null) {
    throw new Error('INVALID_ARGUMENT');
  }
  let res: string[] = [];
  let nodeList: string[] = [];
  let keys: string[] = Object.keys(graph);
  nodeList.push(keys[0]);
  res.push(keys[0]);
  if (graph[keys[0]].length !== 0) {
    keys = keys.filter((key) => key !== keys[0]);
    let arr: string[] = [];
    while (keys.length > 0) {
      arr = [];
      nodeList.forEach((el) => {
        arr = arr.concat(graph[el]);
      });
      res = res.concat(arr);
      nodeList = [...arr];
      keys = keys.filter((key) => !arr.includes(key));
    }
  }
  return res;
};
```

### Work experience:

* :clipboard: [Jira todo list](https://github.com/yakravtsova/todo-list-jira). An application that generates a list of tasks in jira projects.
  Stack: Node.js, Atlassian connect express, React, Atlaskit.
* :partly_sunny: [Weather widget](https://github.com/yakravtsova/weather-widget). Weather widget for website. Stack: Vue.js, Vuex.
* :money_with_wings: [The landing page for saleing of company's services](https://github.com/yakravtsova/nda-landing-page). Stack: HTML, SCSS, Javascript.
* :robot: :film_projector: [The backend of the service where you can find movies on demand and save them in your personal account](https://github.com/yakravtsova/movies-explorer-api). Stack: Node.js, express, MongoDB.
* :computer: :film_projector: [The frontend of the service where you can find movies on demand and save them in your personal account](https://github.com/yakravtsova/movies-explorer-frontend). Stack: React.

