<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:7c3aed&height=190&section=header&text=HattoriLoL&fontSize=60&fontColor=ffffff&fontAlignY=36&desc=Game%20dev%20%C2%B7%20Tools%20%C2%B7%203D%20pipelines&descAlignY=58&descSize=18" width="100%" alt="HattoriLoL"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=620&lines=Building+the+tools+behind+my+games;Photo+%E2%86%92+tileable+PBR+material;Image+%E2%86%92+rigged+3D+model;Floor+plan+%E2%86%92+game-ready+map;Baked+AO%2C+lightmaps+and+light+probes" alt="Building the tools behind my games"/>

</div>

## 👾 About me

I make games — and, mostly, the tools behind them: a chain of small programs that turns photos, images and floor
plans into game-ready 3D maps for **Godot**.

- 🎮 Game development with Godot 4
- 🧱 Blender automation: headless scripts, Cycles bakes, `.glb` in and out
- 🤖 AI-assisted asset creation, using only commercially licensed models

## 🧰 Tech

<p>
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot"/>
  <img src="https://img.shields.io/badge/GDScript-355570?style=for-the-badge&logo=godotengine&logoColor=white" alt="GDScript"/>
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white" alt="Blender"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/glTF-87C540?style=for-the-badge&logo=khronosgroup&logoColor=white" alt="glTF"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

## 🔗 The asset pipeline

```mermaid
flowchart LR
    A["📷 Photo / AI image"] --> T["🎨 TextureMaker<br/>PBR materials"]
    A --> M["🗿 MonkAI<br/>3D models + rig"]
    M --> N["🕺 Animaker<br/>animations"]
    T --> P["🗺️ MapMaker<br/>map editor"]
    M --> P
    P --> F["✨ FineMapAI<br/>UV2 · AO · lightmaps"]
    F --> G["🎮 Godot game"]
    N --> G
```

## 🛠️ Tools I'm building

| | Tool | What it does | Stack |
|:-:|---|---|---|
| 🎨 | **TextureMaker** | Photo or AI image → tileable PBR material (albedo, normal, roughness); paints 3D models | Python |
| 🗿 | **MonkAI** | Image → game-ready 3D model (`.glb`) with retopology and rig | Python |
| 🕺 | **Animaker** | Text → animations for MonkAI characters | JavaScript |
| 🗺️ | **MapMaker** | Map editor built in Godot: floor plan → `.glb`, map info and navigation grid | Godot · GDScript |
| ✨ | **FineMapAI** | Finishing pass for `.glb`: UV2, baked AO, lightmaps and light probes, headless in Blender | Python · Blender |

<sub>Most of these are private while in development.</sub>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:7c3aed&height=110&section=footer" width="100%" alt=""/>
</div>
