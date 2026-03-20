---
title: MHS-CBAU (Magic Harvest Scripting - Canadian Business As Usual)
summary: MHS-CBAU is a an approach to simulate a Business-As-Usual forest management in Canadian lanscapes that are simulated with the LANDIS-II model and its Magic Harvest extension. 
tags:
- ecology
- forest management
date: "2020-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/Klemet/MHS-CBAU"

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Star
  url: https://github.com/Klemet/MHS-CBAU
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## 📑 Description

MHS-CBAU is a an approach to simulate a Business-As-Usual forest management in Canadian lanscapes that are simulated with the [LANDIS-II](https://www.landis-ii.org/) model and its [Magic Harvest](https://github.com/Klemet/LANDIS-II-Magic-Harvest) extension. **In essence, it is made to simulate harvesting in LANDIS-II simulations in Canadian landscapes**.

MHS-CBAU works through a specific Python script (available in this repository) that is called by Magic Harvest during a LANDIS-II simulation. The Python script will make all forest management decisions, and then pass them to the [Biomass Harvest](https://github.com/LANDIS-II-Foundation/Extension-Biomass-Harvest/) extension of LANDIS-II which will execute the harvesting. To learn more about this method of using Magic Harvest and Biomass Harvest in tandem, please see [this workshop](https://klemet.github.io/Workshop-MagicHarvest/).

**[Learn more on the GitHub page of the project](https://github.com/Klemet/MHS-CBAU)**