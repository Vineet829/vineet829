# 👋 Welcome! I'm Vineet Singh  

```javascript
function Creativity() {}

function Life() {
    Creativity.call(this);
}

Life.prototype = Object.create(Creativity.prototype);
Life.prototype.constructor = Life;

function Story() {
    Life.call(this);
}

Story.prototype = Object.create(Life.prototype);
Story.prototype.constructor = Story;

Story.prototype.journeyGenerator = function* () {
    yield "Stumbled upon the Odin Project, unlocking my passion for software engineering.";
    yield "Secured an internship, applying my knowledge in real-world scenarios.";
    yield "Completed a Master's in Computer Applications.";
    yield "Continuing to develop as a full-stack developer.";
};

Story.prototype.tellJourney = function() {
    const journey = this.journeyGenerator();
    console.log("My Journey in Software Engineering:");

    for (const event of journey) {
        console.log(`- ${event}`);
    }
};

const myStory = new Story();
myStory.tellJourney();
```
# My Tech Stack

## Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

## Libraries
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black) ![Material UI](https://img.shields.io/badge/Material%20UI-007FFF?style=flat-square&logo=mui&logoColor=white)

## Frameworks
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-3C87C9?style=flat-square&logo=django&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-8CC84B?style=flat-square&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

## Development Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white) ![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)

## Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)


### 📫 Let's Connect  

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-333333?style=flat&logo=linkedin)](https://https://www.linkedin.com/in/vineet289)  
[![Portfolio](https://img.shields.io/badge/-Portfolio-333333?style=flat&logo=google-chrome)](https://vineetsingh-jet.vercel.app/)  
[![Email](https://img.shields.io/badge/-Email-333333?style=flat&logo=gmail)](mailto:vineetsingh5987@gmail.com)  

---

### 📊 GitHub Stats  


![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vineet829&layout=compact&theme=default)  

---
