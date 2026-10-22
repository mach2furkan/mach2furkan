<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5FF,50:3B82F6,100:8B5CF6&height=200&section=header&text=Furkan%20A%C5%9Fk%C4%B1n&fontSize=52&fontColor=ffffff&fontAlignY=36&animation=twinkling&desc=C-UAS%20%E2%80%A2%20RF%20%2F%20SIGINT%20%E2%80%A2%20Software&descAlignY=58&descSize=18" width="100%"/>
</p>

<p align="center">
  <img width="1536" height="1024" alt="Furkan Aşkın banner" src="https://github.com/user-attachments/assets/c4692b2d-be1b-426f-852d-7145fc7c7ee3" />
</p>

<p align="center">
  <a href="https://github.com/mach2furkan">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=00F5FF&center=true&vCenter=true&multiline=false&width=760&height=50&lines=%F0%9F%9A%80+C-UAS+Specialist;%F0%9F%93%A1+RF+%2F+SIGINT+Enthusiast;%F0%9F%9B%B0+SDR+%E2%80%A2+Spectrum+%E2%80%A2+Signal+Classification;%F0%9F%9B%A1+Building+safer+%26+smarter+skies;%F0%9F%8E%93+Jr.+Computer+Science+Student" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mach2furkan&label=PROFILE%20VIEWS&color=8B5CF6&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/mach2furkan?label=FOLLOWERS&style=for-the-badge&color=00F5FF&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/STATUS-SCANNING%20THE%20SPECTRUM-3fb950?style=for-the-badge&labelColor=0d1117" />
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## `>_` Live Console

<p align="center">
  <img src="./assets/terminal.svg" alt="Animated SIGINT console: SDR init, band scan, UAS detection, classification and sensor fusion" width="100%"/>
</p>

<p align="center">
I design, analyze and prototype systems that combine <b>RF signal intelligence, spectrum awareness</b> and modern software engineering — especially in the context of <b>Counter-UAS (drone defense)</b>, early-warning architectures, and next-generation situational awareness platforms.
<br/><br/>
<b>🎯 My goal:</b> build technologies that make critical environments safer and smarter.
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛰 Sensor Feed

<table align="center">
  <tr>
    <td align="center"><img src="./assets/radar.svg" alt="Animated C-UAS radar sweep" width="100%"/></td>
    <td align="center"><img src="./assets/spectrum.svg" alt="Animated spectrum analyzer and waterfall" width="100%"/></td>
  </tr>
  <tr>
    <td align="center"><sub><b>PPI DISPLAY</b> · RF + Radar track fusion</sub></td>
    <td align="center"><sub><b>SPECTRUM + WATERFALL</b> · 2.4 GHz ISM band</sub></td>
  </tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📡 RF Signal Intelligence (SIGINT)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=2200&pause=600&color=3FB950&center=true&vCenter=true&width=700&lines=%24+detect+%E2%86%92+classify+%E2%86%92+locate+%E2%86%92+visualize;Crowded+RF+environments%2C+clear+pictures." />
</p>

I actively research how advanced systems detect, classify, and visualize signals across crowded RF environments.

<details open>
<summary><b><code>$ cat focus_areas.txt</code></b> &nbsp;👈 click to toggle</summary>
<br/>

| | Area | Details |
|:-:|---|---|
| 📶 | **Spectrum monitoring** | Noise floor analysis (9 kHz – 153 GHz+) |
| 🛰 | **SDR pipelines** | RTL-SDR · HackRF · USRP · AirSpy |
| 🔍 | **Signal classification** | Modulation recognition, ML-assisted |
| 📡 | **DoA / AoA & geolocation** | TDOA, multilateration concepts |
| 🛡 | **C-UAS sensor fusion** | RF + Radar + EO/IR |
| ⚙ | **Tooling** | GNU Radio · Python · MATLAB · CubicSDR · SDR# |

</details>

<details>
<summary><b><code>$ ./pipeline --explain</code></b> &nbsp;🔽 click to run</summary>
<br/>

```mermaid
flowchart LR
    A[📡 Antenna / SDR] --> B[⚡ IQ Capture]
    B --> C[📊 FFT & Waterfall]
    C --> D[🧠 ML Classifier]
    D --> E[📍 DoA / TDOA]
    E --> F[🛡 Sensor Fusion<br/>RF + Radar + EO/IR]
    F --> G[🖥 C2 Operator UI]
    style A fill:#0d1117,stroke:#00F5FF,color:#fff
    style D fill:#0d1117,stroke:#8B5CF6,color:#fff
    style F fill:#0d1117,stroke:#3fb950,color:#fff
    style G fill:#0d1117,stroke:#ff7b72,color:#fff
```

</details>

> [!NOTE]
> 🧭 All research here is strictly **ethical, legal, and educational** — signal analysis only, not interception or misuse.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛡 Counter-UAS Expertise

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=2400&pause=700&color=FF7B72&center=true&vCenter=true&width=700&lines=DETECT+%E2%86%92+TRACK+%E2%86%92+IDENTIFY+%E2%86%92+DECIDE;Layered+defense+for+low-slow-small+targets" />
</p>

I work on understanding the architecture behind modern **anti-drone systems**:

<details open>
<summary><b><code>$ c-uas --layers</code></b></summary>
<br/>

```diff
+ [LAYER 1]  🎯 RF detection & signal fingerprinting
+ [LAYER 2]  📡 Radar integration for low-slow-small targets
+ [LAYER 3]  👁  EO/IR confirmation workflows
+ [LAYER 4]  🔗 C2 software and operator UI design
+ [LAYER 5]  🧩 System interoperability & layered defense concepts
! STATUS     all layers nominal — airspace monitored
```

</details>

> C-UAS is where **RF engineering, software, and defense-grade design meet** — and that intersection fascinates me.

<p align="center"><b>📬 If you're working on RF monitoring, drone defense or sensor fusion — let's talk.</b></p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,nextjs,tailwind,go,rust,nodejs&perline=7" /><br/>
  <img src="https://skillicons.dev/icons?i=aws,graphql,django,flask,c,cpp&perline=6" /><br/>
  <img src="https://skillicons.dev/icons?i=html,css,js,figma,matlab,linux&perline=6" />
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📊 Signal Strength

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mach2furkan&theme=tokyonight&hide_border=true&background=0d1117&ring=00F5FF&fire=8B5CF6&currStreakLabel=00F5FF" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mach2furkan&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00F5FF" width="40%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3000&pause=1000&color=8B949E&center=true&vCenter=true&width=600&lines=%24+exit+%E2%80%94+session+closed.+Stay+on+frequency.+%F0%9F%93%A1" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:3B82F6,100:00F5FF&height=120&section=footer&animation=twinkling" width="100%"/>
