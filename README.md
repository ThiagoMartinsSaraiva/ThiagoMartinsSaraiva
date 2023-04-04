### Hi there!
#### My name is Thiago, and I'm a Frontend Engineer <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjdhMTkwNTVkNGE0NmE5ZTliNmE1OTlhNTg5ZWY3YTY3YjFiMTU3MyZjdD1z/5Lmn42BCOy99RaGRP7/giphy.gif" width="30" />

```js
import { experience } from 'ThiagoMartinsSaraiva'

export const ThiagoMartinsSaraiva = () => {
  const { ReactJS, ReactNative, TypeScript, NodeJS, NestJS } = experience

  const currentWork = {
    company: 'Datum TI',
    role: 'Frontend Engineer',
    techs: [ReactJS, ReactNative, TypeScript, NodeJS, NestJS],
  }
  
  const currentStudyProject = {
    name: 'lol-data',
    repoUrl: 'https://github.com/ThiagoMartinsSaraiva/lol-data',
    url: 'https://thiaguera-lol-data.netlify.app/',
    techs: [ReactJS, TypeScript],
  }

  return { currentWork, currentStudyProject }
}
```