<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0099ff,6a00ff&height=120&section=header&text=👋%20Hi,%20I'm%20Omar%20Mostafa!&fontSize=38&fontColor=fff"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=AI+%26+Data+Science+Student;Full+Stack+Developer;Machine+Learning+Enthusiast;Welcome+to+my+profile!&font=Fira+Code&center=true&width=500&height=45&color=00AEEF&vCenter=true&pause=1000&size=28"/>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/3ohzdIuqJoo8QdKlnW/giphy.gif" width="140" />
  <img src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" width="140" />
  <img src="https://media.giphy.com/media/hpXdHPfFI5wTABdDx9/giphy.gif" width="100" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-AI%20%26%20Data%20Science-3c096c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Full%20Stack%20Developer-0077b6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Machine%20Learning%20Enthusiast-38b000?style=for-the-badge" />
</p>

---

## 💡 About Me

- 🎓 **AI & Data Science student** at **Helwan National University**  
- 🚀 Building intelligent systems to solve real-world problems  
- 💼 Intern @ NTG | ML @ NTI  
- 🌱 Always learning, always open for new opportunities

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,cpp,cs,html,css,react,django,git,postgres,mysql,tensorflow,pandas" />
</p>

---
## ✨ Animated Tech Icons

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaDg3dXZyemtsN2pmM3Y3bXNoeDZoN2Vtb2F0M3Vyb3hycmh1cHpoOSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/YaOxRsmrv9IeA/giphy.gif" width="320" alt="Animated Tech Icons"/>
</div>

<p align="center">
  <b>Animated icons related to my tech stack - keep watching! 🚀</b>
</p>

---

### 🛠️ Why Animated Icons?

> I love interactive and lively UIs!  
> These tech icons represent my core skills:  
> <b>AI, Machine Learning, Data Science, Cloud, Backend, Full Stack, and more!</b>

---

### 🔥 Want the effect for your own portfolio?

<details>
  <summary>Click here for React code (Framer Motion + Lucide)</summary>

```jsx
// npm install framer-motion lucide-react
import { useEffect, useState } from "react";
import { motion, AnimatePresence } from "framer-motion";
import { Cpu, Database, Brain, Code2, Server, Cloud, Code, BarChart3 } from "lucide-react";

const techIcons = [
  { icon: <Cpu size={60} />, label: "AI" },
  { icon: <Brain size={60} />, label: "Machine Learning" },
  { icon: <BarChart3 size={60} />, label: "Data Science" },
  { icon: <Database size={60} />, label: "Database" },
  { icon: <Cloud size={60} />, label: "Cloud" },
  { icon: <Server size={60} />, label: "Backend" },
  { icon: <Code2 size={60} />, label: "Full Stack" },
  { icon: <Code size={60} />, label: "Programming" },
];

export default function AnimatedTechIcons() {
  const [visible, setVisible] = useState(0);

  useEffect(() => {
    const timer = setInterval(() => {
      setVisible((v) => (v + 1) % techIcons.length);
    }, 1800);
    return () => clearInterval(timer);
  }, []);

  return (
    <div className="flex items-center justify-center h-40">
      <AnimatePresence>
        <motion.div
          key={visible}
          className="flex flex-col items-center"
          initial={{ opacity: 0, scale: 0.5, y: 30 }}
          animate={{ opacity: 1, scale: 1, y: 0 }}
          exit={{ opacity: 0, scale: 0.5, y: -30 }}
          transition={{ duration: 0.6 }}
        >
          <div className="text-primary">{techIcons[visible].icon}</div>
          <span className="text-base mt-2">{techIcons[visible].label}</span>
        </motion.div>
      </AnimatePresence>
    </div>
  );
}

## 🏆 Certifications

- 🤖 [AI & ML with Quantum Computing Foundations](https://drive.google.com/file/d/1wT5n4JIN58snlKwWsLvZMbFCG5rBtNAI/view?usp=drive_link)
- 💻 [Intro to Software Engineering Diploma](https://drive.google.com/file/d/1CWnQAeGmT3TbHIesjp0KoXJ7GpVv-Nm3/view?usp=drive_link)
- 🐍 [Full Stack Web Dev Using Python (120 hrs)](https://drive.google.com/file/d/1h4PGPLSiXgvbroENKEhczXhfnBNc2O1C/view?usp=drive_link)
- 🏅 [2024 ICPC ECPC Qualifications - Honorable Mention](https://drive.google.com/file/d/1m_prA51PPFql9Z4kCMPpZgFXFge1IEQI/view?usp=drive_link)
- 🤖 [AI Ambassadors Program](https://drive.google.com/file/d/1cS3UP2uONPTEdIL3YmwSjV_Upny4-4eM/view?usp=drive_link)

---

## 🎯 My Goals

- 🚀 Join a high-impact AI or Software Engineering internship  
- 📚 Master Deep Learning & MLOps  
- 🌍 Contribute to open-source projects  
- 🎤 Share technical knowledge via blogs or talks  

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/omar-mostafa-abdsttar-b2b72134b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:omarmostafaabdsttar@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=OmarMostafa7&color=brightgreen" alt="Profile Views">
</p>

