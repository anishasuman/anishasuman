# 💫 Hi, I'm Anisha Kumari!  

🎓 3rd Year BTech Student | 🌥️ Cloud Computing Enthusiast  
💡 Passionate about solving problems and exploring new technologies  
🚀 Currently learning programming and diving into cloud use cases  

---

## 🔧 Tech Stack I'm Working With:
- 💻 Java, C++, Python, HTML-CSS  
- ☁️ Cloud Basics (AWS – learning phase)  
- 🛠️ Git & GitHub  

---

## 📌 Current Focus
- 📚 Daily Java & DSA Practice  
- 🌐 Building strong problem-solving skills  
- ☁️ Exploring real-world cloud applications  

---

## 📊 GitHub Stats  

<h2 align="center">🌟✨ <i>Anisha Kumari's GitHub Stats</i> ✨🌟</h2>  

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Georgia&size=24&duration=3500&pause=1000&color=F49AC2&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B+I'm+Anisha+Kumari!;B.Tech+CS+Student+%7C+Cloud+Explorer+%E2%98%81%EF%B8%8F;Java+Lover+%7C+Code+%26+Coffee+%E2%98%95%EF%B8%8F;Building+Projects+with+Purpose+%F0%9F%92%BC" alt="Typing SVG" />
</p>  

<h2 align="center">👩‍💻 Focus Mode On</h2>  
<p align="center">
  <img src="https://media.giphy.com/media/RbDKaczqWovIugyJmW/giphy.gif" width="450" alt="Anime Girl Coding">
</p>  

---


import { useState } from "react";
import { motion } from "framer-motion";
import { Flame, Calendar, Star } from "lucide-react";

export default function StreakTracker() {
  const [streak, setStreak] = useState(7); // current streak
  const [bestStreak, setBestStreak] = useState(15); // best streak

  return (
    <div className="flex justify-center items-center min-h-screen bg-gradient-to-br from-orange-100 to-yellow-200">
      <motion.div
        initial={{ scale: 0.8, opacity: 0 }}
        animate={{ scale: 1, opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="bg-white rounded-2xl shadow-xl p-6 w-80 text-center"
      >
        {/* Streak Icon */}
        <motion.div
          animate={{ rotate: [0, -5, 5, 0] }}
          transition={{ repeat: Infinity, duration: 2 }}
          className="flex justify-center"
        >
          <Flame className="text-orange-500 w-14 h-14" />
        </motion.div>

        {/* Current Streak */}
        <h1 className="text-4xl font-bold mt-4 text-gray-800">{streak} 🔥</h1>
        <p className="text-gray-500 text-sm">Current Streak</p>

        {/* Best Streak */}
        <div className="flex justify-between mt-6 text-gray-700">
          <div className="flex items-center space-x-2">
            <Calendar className="w-5 h-5 text-blue-500" />
            <span className="text-sm">7 Days Active</span>
          </div>
          <div className="flex items-center space-x-2">
            <Star className="w-5 h-5 text-yellow-500" />
            <span className="text-sm">Best: {bestStreak} Days</span>
          </div>
        </div>

        {/* Button */}
        <motion.button
          whileTap={{ scale: 0.9 }}
          className="mt-6 w-full py-2 bg-orange-500 text-white font-semibold rounded-xl shadow-md hover:bg-orange-600 transition"
          onClick={() => setStreak(streak + 1)}
        >
          + Add Day
        </motion.button>
      </motion.div>
    </div>
  );
}



### 🔤 Top Languages Used
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=anishasuman&layout=compact&theme=light&langs_count=8&bg_color=ffffff&title_color=000000&text_color=333333&icon_color=4CAF50&border_radius=10" alt="Top Languages Used" />

### 📊 My GitHub Stats
<img src="https://github-readme-stats.vercel.app/api?username=anishasuman&show_icons=true&count_private=true&theme=light&bg_color=ffffff&title_color=000000&text_color=333333&icon_color=F9A826&border_radius=10" alt="GitHub Stats" />

### 🗂️ Most Used Languages by Repositories
<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
 </p>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=anishasuman&theme=github&background=ffffff&title_color=000000&text_color=333333" alt="Repos per Language" />

---

## 🌐 Connect with Me:  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/anisha-kumari-68522426a/)  
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white)](https://www.hackerrank.com/profile/anisha77suman191)  
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=CodeChef&logoColor=white)](https://www.codechef.com/users/anisha_23)  
