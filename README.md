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


### 📫 Let's Connect  

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-333333?style=flat&logo=linkedin)](https://https://www.linkedin.com/in/vineet289)  
[![Portfolio](https://img.shields.io/badge/-Portfolio-333333?style=flat&logo=google-chrome)](https://vineetsingh-jet.vercel.app/)  
[![Email](https://img.shields.io/badge/-Email-333333?style=flat&logo=gmail)](mailto:vineetsingh5987@gmail.com)  

---

### 📊 GitHub Stats  


![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vineet829&layout=compact&theme=default)  

---
