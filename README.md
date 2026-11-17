<div align="center">

<img src="assets/banner.svg" width="100%" alt="HattoriLoL — game dev · tools · 3D pipelines"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1400&color=FF9F1C&center=true&vCenter=true&width=640&lines=%F0%9F%8E%A7+lo-fi+beats+to+bake+lightmaps+to;photo+%E2%86%92+tileable+PBR+material;image+%E2%86%92+rigged+3D+model;floor+plan+%E2%86%92+game-ready+map;one+big+bake+a+day+%F0%9F%92%A5;it's+3+AM+and+the+build+is+green+%E2%9C%A8" alt="lo-fi beats to bake lightmaps to"/>

</div>

## 🌃 About me

I make games — and, mostly, the tools behind them: a chain of small programs that turns photos, images and floor
plans into game-ready 3D maps for **Godot**. Usually late at night, with lo-fi on.

```console
hattori@night-city:~$ status
  🎧 now playing   lo-fi beats to bake lightmaps to
  ☕ coffee        3rd cup
  🛠️ building      a 3D asset pipeline for Godot games
  🤖 AI rule       commercially licensed models only
```

## ⚡ Tech

<p>
  <img src="https://img.shields.io/badge/Godot-2a0f14?style=for-the-badge&logo=godotengine&logoColor=ff9f1c" alt="Godot"/>
  <img src="https://img.shields.io/badge/GDScript-2a0f14?style=for-the-badge&logo=godotengine&logoColor=e8303f" alt="GDScript"/>
  <img src="https://img.shields.io/badge/Blender-2a0f14?style=for-the-badge&logo=blender&logoColor=ff9e2e" alt="Blender"/>
  <img src="https://img.shields.io/badge/Python-2a0f14?style=for-the-badge&logo=python&logoColor=ffe0a3" alt="Python"/>
  <img src="https://img.shields.io/badge/NumPy-2a0f14?style=for-the-badge&logo=numpy&logoColor=ff9f1c" alt="NumPy"/>
  <img src="https://img.shields.io/badge/JavaScript-2a0f14?style=for-the-badge&logo=javascript&logoColor=ffe0a3" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/glTF-2a0f14?style=for-the-badge&logo=khronosgroup&logoColor=f6c39b" alt="glTF"/>
  <img src="https://img.shields.io/badge/Linux-2a0f14?style=for-the-badge&logo=linux&logoColor=e8303f" alt="Linux"/>
</p>

## 🔗 The asset pipeline

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#2a0f14','primaryTextColor':'#ffffff','primaryBorderColor':'#e8303f','lineColor':'#ff9f1c','fontFamily':'monospace'}}}%%
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
<img src="assets/footer.svg" width="100%" alt="see you at 3 AM"/>
</div>
