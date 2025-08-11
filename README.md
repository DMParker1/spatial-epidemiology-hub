# Spatial Epidemiology Hub — Daniel M. Parker

[![Release](https://img.shields.io/github/v/release/DMParker1/spatial-epidemiology-hub)](../../releases)

This is my personal umbrella repository tying together projects, tools, and collaborations in **GIS** and **spatial epidemiology**.  
It’s both a **map of my career so far** and a **pointer to where my current and future work is headed**.

Most of my active research is now organized under the [**Parker Group organization**](https://github.com/parker-group), where we develop and share open spatial analysis tools and datasets.  
For a complete picture of our group’s work, see the [**Public Overview**](https://github.com/parker-group/public-overview).

---

## 🌍 Career Arc & Project Constellation

### 1. **Foundations** — Field epidemiology & GIS
Early work combining field research, anthropology, and spatial analysis to understand health and disease in complex settings.

### 2. **Expanding Methods** — Remote sensing, spatial modeling & human movement
Incorporating **Earth observation**, **spatiotemporal analysis**, **human movement research**, and tool development to answer new public health questions.

- [SDEtool](https://github.com/parker-group/SDEtool) — Our in-house R package for generating standard deviational ellipses, used in spatial epidemiology and movement analysis.  
- [earth-observation-hub](https://github.com/DMParker1/earth-observation-hub) — Remote sensing methods applied to health and environment.  
- [HumMovPatt](https://github.com/SaiTheinThanTun/HumMovPatt) — Code and analysis for human movement & exposure buffer size selection (Wellcome Open Research study).

### 3. **Interdisciplinary Collaborations**
Working at the intersection of epidemiology, vector-borne disease control, climate, and health systems — often in challenging borderland and displacement contexts.

- [METF-mapping](https://github.com/DMParker1/METF-mapping) — Mapping and community engagement groundwork for malaria post placement.  
- [tMDA-program](https://github.com/DMParker1/tmda-program) — Targeted mass drug administration trials and modeling.  
- [early-dx-tx](https://github.com/DMParker1/early-dx-tx) — Early access to malaria diagnosis and treatment.  
- [tm-border-mch](https://github.com/DMParker1/tm-border-mch) — Maternal and child health research on the Thailand–Myanmar border.

### 4. **Current & Future Directions** — Parker Group
Most of my active and upcoming work happens within the **[Parker Group](https://github.com/parker-group)**, where we build open tools and curate datasets.  
For a complete, living catalog see the **[Public Overview](https://github.com/parker-group/public-overview)**.

---

## 🗺 Visual: Project Constellation

```mermaid
%%{init: {"theme":"base","themeVariables":{
  "background":"#FAFAFA",
  "clusterBkg":"#F3F4F6",
  "clusterBorder":"#E5E7EB",
  "primaryColor":"#E8F5E9",
  "primaryBorderColor":"#2E7D32",
  "primaryTextColor":"#0F172A",
  "lineColor":"#9CA3AF"
}}}%%
flowchart LR
  subgraph A[Foundations]
    METF["METF-mapping"]
    EDT["early-dx-tx"]
    MCH["tm-border-mch"]
    tMDA["tMDA-program"]
  end

  subgraph B[Expanding Methods]
    EO["Earth Observation Hub"]
    SDE["SDEtool"]
    HM["Human Movement (HumMovPatt)"]
  end

  subgraph C[Umbrella]
    GIS["spatial-epidemiology-hub"]
  end

  subgraph D[Current & Future]
    PG["Parker Group (org)"]
  end

  GIS --> METF
  GIS --> tMDA
  GIS --> EDT
  GIS --> MCH
  GIS --> EO
  GIS --> SDE
  GIS --> HM
  GIS --> PG

  METF --- tMDA
  EDT --- tMDA
  METF --- MCH
  EO --- SDE
  EO --- HM

  EO --> PG
  SDE --> PG
  HM --> PG
  METF --> PG
  tMDA --> PG
  EDT --> PG
  MCH --> PG
```

---

## 🔗 Related Repositories

- **Parker Group** — [Organization homepage](https://github.com/parker-group) | [Public Overview](https://github.com/parker-group/public-overview)  
- **Tools & Methods**  
  - [SDEtool](https://github.com/parker-group/SDEtool) — Standard Deviational Ellipse generation in R.  
  - [earth-observation-hub](https://github.com/DMParker1/earth-observation-hub) — EO and remote sensing workflows for health research.  
- **Ongoing Themes & Representative Projects**  
  *(These links highlight key areas that have shaped my work and continue to influence my research. I add new examples over time; for the full scope of current activities, see the [Parker Group Public Overview](https://github.com/parker-group/public-overview).)*  
  - [METF-mapping](https://github.com/DMParker1/METF-mapping) — Mapping malaria post placement & community engagement.  
  - [tMDA-program](https://github.com/DMParker1/tmda-program) — Targeted mass drug administration trials & modeling.  
  - [early-dx-tx](https://github.com/DMParker1/early-dx-tx) — Early access to malaria diagnosis & treatment.  
  - [tm-border-mch](https://github.com/DMParker1/tm-border-mch) — Maternal & child health on the Thailand–Myanmar border.


---

<sub>© Daniel M. Parker — See individual repositories for license details.</sub>
