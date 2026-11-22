<!-- ====== HEADER ====== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3460,100:00b4d8&height=230&section=header&text=Shshank&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Physical%20AI%20%E2%80%A2%20Robotics%20%E2%80%A2%20Agentic%20Systems&descAlignY=58&descSize=18" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/shnkdev404">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=00B4D8&center=true&vCenter=true&width=700&lines=Building+machines+that+perceive%2C+reason+%26+act;Physical+AI+%E2%80%A2+Embodied+Agents+%E2%80%A2+Robotics;From+bare-metal+firmware+to+agentic+planners;Java+%E2%80%A2+C%2B%2B+%E2%80%A2+Python+%E2%80%A2+STM32+%E2%80%A2+ESP32;Shared+Perception+%26+3D+World+Mapping" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/shshank-kumar-a639b1373"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kumarshshank75@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/shnkdev404/Portfolio_Shshank"><img src="https://img.shields.io/badge/Portfolio-0f3460?style=for-the-badge&logo=nextdotjs&logoColor=white"/></a>
  <a href="https://instagram.com/_mobile.pixels_"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

<h3 align="center">
  <i>"Intelligence isn't real until it can move something."</i>
</h3>

---

### ⚡ `whoami`

```java
public final class Shshank implements PhysicalAI, AgenticSystem, HardwareEngineer {

    private final String mission =
        "Close the loop between AI and the physical world: sense → reason → act.";

    private final List<String> buildingNow = List.of(
        "Autonomous micromouse (ToF + IMU fusion, Flood Fill)",
        "Shared perception across multiple wearables & cameras",
        "Agents that plan with LLMs and execute on real hardware"
    );

    private final Map<String, String> layers = Map.of(
        "silicon",    "STM32 · ESP32 · Teensy · Raspberry Pi",
        "perception", "ToF · IMU · monocular vision · 3D mapping",
        "reasoning",  "agentic AI · planning · tool use",
        "software",   "Java · C/C++ · Python · TypeScript"
    );

    @Override
    public Action act(Observation world) {
        return plan(perceive(world)).verifyOnHardware();
    }
}
```

---

### 🧠 How I Think About Physical AI

Every project I build is a piece of one loop. Software agents are getting smart; **I'm interested in giving them a body.**

```mermaid
flowchart LR
    A["🔌 Sensors<br/>ToF · IMU · Cameras · Wearables"] --> B["👁️ Perception<br/>Fusion · Mapping · Shared World Model"]
    B --> C["🧠 Agentic Reasoning<br/>LLM Planner · Tools · Memory"]
    C --> D["⚙️ Control<br/>PID · Path Planning · Firmware"]
    D --> E["🤖 Actuators<br/>Motors · Drones · Robots"]
    E -- "the world changes" --> A

    classDef node fill:#0d1117,stroke:#00b4d8,stroke-width:2px,color:#ffffff;
    class A,B,C,D,E node;
```

| Layer | Where you'll find it in my work |
|:--|:--|
| 🔌 **Sensing** | ToF + IMU array on the [Maze Runner](https://github.com/shnkdev404/tof_wala_maze_runner) |
| 👁️ **Perception** | Monocular 3D mapping in [sentinel-net](https://github.com/shnkdev404/sentinel-net), multi-device fusion in [Reycon](https://github.com/shnkdev404/Reycon-Meta-Glasses) |
| 🧠 **Reasoning** | Agentic AI experiments, plus AI-assisted care in [Aidra](https://github.com/shnkdev404/Aidra) |
| ⚙️ **Control** | Flood Fill navigation, PID tuning, bare-metal firmware |
| 🌍 **World scale** | Hydrological flood prediction in [flood-mapping](https://github.com/shnkdev404/flood-mapping) |

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🐭 <a href="https://github.com/shnkdev404/tof_wala_maze_runner">Maze Runner</a></h3>
      <p>Autonomous micromouse with 3 ToF sensors, optional IMU/magnetometer fusion, and Flood Fill navigation. Sensing, mapping, and control on a single microcontroller.</p>
      <p><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/Sensor_Fusion-0f3460?style=flat-square"/> <img src="https://img.shields.io/badge/Layer-Control-00b4d8?style=flat-square"/></p>
    </td>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/shnkdev404/sentinel-net">sentinel-net</a></h3>
      <p>LiDAR-style 3D mapping from a single monocular camera. Turns ordinary cameras into depth-aware sensors that build a shared map.</p>
      <p><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/Computer_Vision-0f3460?style=flat-square"/> <img src="https://img.shields.io/badge/Layer-Perception-00b4d8?style=flat-square"/></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🕶️ <a href="https://github.com/shnkdev404/Reycon-Meta-Glasses">Reycon Meta Glasses</a></h3>
      <p>Shared perception that fuses live feeds from multiple Ray-Ban Meta glasses into one view of the world, powering real-time safety features.</p>
      <p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Wearables-0f3460?style=flat-square"/> <img src="https://img.shields.io/badge/Layer-Perception-00b4d8?style=flat-square"/></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌊 <a href="https://github.com/shnkdev404/flood-mapping">flood-mapping</a></h3>
      <p>Predicts likely river paths and flood-affected regions with hydrological modeling and GIS analysis. Physical AI at the scale of a landscape.</p>
      <p><img src="https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white"/> <img src="https://img.shields.io/badge/Hydrology-0f3460?style=flat-square"/> <img src="https://img.shields.io/badge/Layer-World_Model-00b4d8?style=flat-square"/></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 <a href="https://github.com/shnkdev404/Aidra">Aidra</a></h3>
      <p>Health management platform pairing AI assistance with real doctor support, keeping a human in the loop where it matters.</p>
      <p><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/AI-0f3460?style=flat-square"/> <img src="https://img.shields.io/badge/Layer-Reasoning-00b4d8?style=flat-square"/></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 <a href="https://github.com/shnkdev404/Portfolio_Shshank">Portfolio</a></h3>
      <p>My personal site, built with Next.js and Tailwind CSS. The long-form story behind these projects.</p>
      <p><img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Layer-Interface-00b4d8?style=flat-square"/></p>
    </td>
  </tr>
</table>

---

### 🧭 Now · Next · Learning

| 🔨 Now | 🔭 Next | 📚 Learning |
|:--|:--|:--|
| Tuning the micromouse: faster Flood Fill, smoother PID | An LLM agent that plans missions and hands them to a real robot | Advanced sensor fusion (EKF and beyond) |
| Multi-device shared perception | One shared world model across robots, wearables & drones | Agentic AI patterns: tool use, memory, multi-agent coordination |
| Monocular 3D mapping | Swarm coordination driven by shared maps | Java for robust backends that talk to hardware |

---

### 🛠️ Toolbox

**Languages & Software**
<p>
  <img src="https://skillicons.dev/icons?i=java,c,cpp,py,js,ts,nextjs,react,tailwind,nodejs,firebase,vercel&perline=12" />
</p>

**Hardware & Systems**
<p>
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,git,github&perline=12" />
</p>
<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/Teensy-0f3460?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LiDAR_%26_ToF-0f3460?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IMU_Fusion-0f3460?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white"/>
</p>

---

### 📐 Principles I Build By

> **1. Reality is the benchmark.** A model that works in simulation but not on the bench isn't finished.
>
> **2. Know every layer.** I want to understand the register, the algorithm, *and* the agent's prompt.
>
> **3. Perception is a team sport.** Machines see better together than alone.
>
> **4. Ship, then measure.** Hackathon speed, engineering discipline.

---

### 🏆 Ask Me About

`micromouse & competitive robotics` · `embedded C/C++ on STM32/ESP32` · `sensor fusion` · `monocular 3D mapping` · `agentic AI for robots` · `GIS & flood modeling` · `surviving hackathons`

---

<details>
<summary><b>📊 GitHub Stats</b> (click to expand)</summary>
<br/>

<p align="center">
  <img height="165" src="https://github-readme-stats.shion.dev/api?username=shnkdev404&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=00b4d8&include_all_commits=true&count_private=true"/>
  <img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=shnkdev404&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00b4d8"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=shnkdev404&theme=tokyonight&hide_border=true&background=0d1117&ring=00b4d8&fire=00b4d8&currStreakLabel=00b4d8" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shnkdev404&bg_color=0d1117&color=00b4d8&line=00b4d8&point=ffffff&area=true&hide_border=true" width="100%"/>
</p>

</details>

---

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shnkdev404/shnkdev404/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shnkdev404/shnkdev404/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/shnkdev404/shnkdev404/output/github-snake-dark.svg" />
  </picture>
</p>

<p align="center">
  <b>Building something that moves, sees, or thinks? Let's talk.</b><br/>
  <a href="mailto:kumarshshank75@gmail.com">kumarshshank75@gmail.com</a>
</p>

<!-- ====== FOOTER ====== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0f3460,100:0d1117&height=120&section=footer" width="100%"/>
</p>
