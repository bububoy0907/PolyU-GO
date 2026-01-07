# PolyU-GO — WebAR Scavenger Hunt (PolyU COMP Info Day 2024)

A Pokémon GO–style **WebAR scavenger hunt** built for **Hong Kong PolyU (COMP Faculty Info Day, Nov 2024)**. Visitors explore the PolyU campus, collect coins at iconic locations and event stations, then redeem prizes at the COMP booth.

> **Important (Transparency):** This repo does **not** include the full application source code. The original project was built on **8th Wall** using a paid scavenger-hunt template, and parts of the implementation and configuration are not shareable due to licensing and event sensitivity.  
> This repository focuses on **portfolio-safe deliverables**, especially the **low-poly PolyU campus 3D model** and public-facing project documentation.

---

## What the Experience Looks Like (Gameplay)

1. Open the WebAR app on a mobile device during the event.
2. View a campus map with multiple coin locations.
3. Navigate to a target location (iconic buildings / COMP event stations).
4. At the location, scan a **QR code** provided by staff to claim the coin.
5. Accumulate enough coins, then return to the COMP booth to redeem prizes/souvenirs.

---

## My Responsibilities

Within ~1 month (team delivery sprint), I contributed to end-to-end development, including:

- **3D Environment / Campus Model**
  - Created a **low-poly PolyU campus model** in Blender (including major campus landmarks and building blocks).
  - Prepared and optimized assets for **mobile WebGL** rendering.

- **Client-Side Implementation (Portfolio-safe summary)**
  - Integrated the campus model into the WebAR scene via **Three.js**.
  - Implemented and refined UI/UX screens and animations based on **Figma** designs.
  - Focused on using 8th Wall primarily for **location-based logic**, while customizing the rest of the experience.

- **Deployment & Data**
  - Hosted the web app on **Firebase**.
  - Implemented a database-backed flow (SQL-backed) for:
    - user state
    - coin counts
    - redemption status

---

## Outcomes (Verified)

- Handled **2,000+ concurrent users**
- Received **~90% positive feedback** from visitors, students, and faculty

---

## Tech Stack

- **WebAR Platform:** 8th Wall (Scavenger Hunt template; licensed / not redistributed)
- **3D / Web Graphics:** AFrame, Three.js, Mobile WebGL
- **Language / UI:** TypeScript + TSX components, UI animations
- **Design:** Figma
- **Hosting:** Firebase
- **Database:** SQL-backed persistence layer (coin count + redemption state)
- **3D Content Creation:** Blender

---

## What’s Not Included

This repository intentionally does **not** include:

- Full 8th Wall project source (template licensing + paid platform constraints)
- Event-specific operational details (to avoid leaking internal configuration)
- Sensitive PolyU operational information (endpoints, keys, admin panels, internal event setup)

This is a **deliberate portfolio decision** to stay compliant and responsible.

---

## How to Preview the 3D Campus Model

### Option A: View in Blender (fastest)
1. Open Blender
2. `File → Import` and select the model format in `models/`
3. Inspect the scene hierarchy and meshes

### Option B: View in a Web 3D Viewer
- Use any local glTF viewer (web or desktop)

---

## Screenshots / Showcase

### App screenshots: </br>
Main screens:</br>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/app_sc1.jpeg?raw=true" width="50%" height="50%"/>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/app_sc2.jpeg?raw=true" width="50%" height="50%"/><img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/app_sc4.jpeg?raw=true" width="40%" height="40%"/>
</br></br>Map view:</br>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/app_sc5.jpeg?raw=true" width="30%" height="30%"/>
</br></br>User Form:</br>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/app_sc6.jpeg?raw=true" width="30%" height="30%"/>

### Development progress screenshots: </br>

Model Implementation: </br>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_7.jpeg?raw=true" width="33%" height="33%"/>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_8.jpeg?raw=true" width="40%" height="40%"/>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_10.jpeg?raw=true" width="40%" height="40%"/><img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_1.jpeg?raw=true" width="40%" height="40%"/>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_9.jpeg?raw=true" width="40%" height="40%"/>
</br></br>UI/UX: </br>
<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_4.jpeg?raw=true" width="30%" height="30%"/><img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_2.jpeg?raw=true" width="29%" height="29%"/>

<img src="https://github.com/bububoy0907/PolyU-GO/blob/main/media/progress_6.jpeg?raw=true" width="35%" height="35%"/>

---

## Notes on Licensing & Usage

- The **campus 3D model** included here is provided for **portfolio viewing**.
- Please **do not reuse or redistribute** these assets without permission.
- Third-party platform/template components (8th Wall) are **not** included and remain under their respective licenses.

---
