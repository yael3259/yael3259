<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,10,25,30&height=220&section=header&text=✨%20Yael%20Ram%20✨&fontSize=52&fontColor=ffffff&animation=twinkling" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&color=F70063&center=true&vcenter=true&width=700&lines=Fullstack+%26+Mobile+Software+Engineer;Turning+caffeine+%26+logic+into+clean+code;Co-Founder+%26+Tech+Lead+%40+Drivoosh;Pixel-perfect+UIs+%20%E2%80%A2+Robust+Architectures" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yaelram" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:yael3259@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/yael3259">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

</br>

## 📍 System Profile

```typescript
type Status = 'Debugging' | 'Architecting' | 'Refactoring' | 'Drinking Coffee';

interface SoftwareEngineer {
  name: string;
  role: string;
  location: string;
  stack: Record<string, string[]>;
  currentStatus: Status;
  isBugsAllowed: boolean;
}

const yael: SoftwareEngineer = {
  name: 'Yael Ram',
  role: 'Fullstack & Mobile Software Engineer',
  location: 'Israel 🇮🇱',
  stack: {
    languages: ['TypeScript', 'JavaScript', 'Python', 'Dart'],
    frontendMobile: ['React Native', 'React', 'Expo', 'Flutter', 'HTML5/CSS3'],
    backendDB: ['Node.js', 'Express.js', 'Flask', 'PostgreSQL', 'MongoDB']
  },
  currentStatus: 'Architecting high-scale platforms',
  isBugsAllowed: false // strictly caught in staging
};
