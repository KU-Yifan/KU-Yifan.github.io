---
layout: page
permalink: /collaborations/
title: collaborations
description: Research collaboration map — groups I actively work with and on what. Drag the nodes around.
nav: true
nav_order: 5
chart:
  echarts: true
---

```echarts
{
  "tooltip": { "show": true, "formatter": "{b}" },
  "series": [
    {
      "type": "graph",
      "layout": "force",
      "roam": true,
      "draggable": true,
      "zoom": 1,
      "force": { "repulsion": 1400, "edgeLength": 170, "gravity": 0.15 },
      "label": { "show": true, "fontSize": 12, "lineHeight": 16 },
      "edgeLabel": { "show": true, "fontSize": 10, "opacity": 0.85 },
      "lineStyle": { "width": 2, "curveness": 0.12, "opacity": 0.45 },
      "emphasis": { "focus": "adjacency", "lineStyle": { "width": 4, "opacity": 0.9 } },
      "data": [
        { "name": "Yifan Sun\nKURNS, Kyoto University", "symbolSize": 95, "itemStyle": { "color": "#1f6feb" }, "label": { "color": "#ffffff", "fontWeight": "bold" } },
        { "name": "Wolverton group\nNorthwestern University", "symbolSize": 62, "itemStyle": { "color": "#4e2a84" }, "label": { "color": "#ffffff" } },
        { "name": "Albert Wu group\nTaiwan", "symbolSize": 62, "itemStyle": { "color": "#0f766e" }, "label": { "color": "#ffffff" } },
        { "name": "Chu group (Yang Liu)\nKyoto University", "symbolSize": 62, "itemStyle": { "color": "#b45309" }, "label": { "color": "#ffffff" } },
        { "name": "Sora-at Tanusilp & collaborators\nThailand", "symbolSize": 62, "itemStyle": { "color": "#be185d" }, "label": { "color": "#ffffff" } },
        { "name": "Ogawa group\nKyoto University", "symbolSize": 62, "itemStyle": { "color": "#0ea5e9" }, "label": { "color": "#ffffff" } },
        { "name": "Benjamin McLellan\nKyoto University", "symbolSize": 62, "itemStyle": { "color": "#16a34a" }, "label": { "color": "#ffffff" } }
      ],
      "links": [
        { "source": 0, "target": 1, "label": { "show": true, "formatter": "thermoelectrics · data-driven MI" } },
        { "source": 0, "target": 2, "label": { "show": true, "formatter": "thin-film characterization" } },
        { "source": 0, "target": 3, "label": { "show": true, "formatter": "AI for Science" } },
        { "source": 0, "target": 4, "label": { "show": true, "formatter": "thermoelectrics" } },
        { "source": 0, "target": 5, "label": { "show": true, "formatter": "hypothesis generation · citation analysis" } },
        { "source": 0, "target": 6, "label": { "show": true, "formatter": "computational social science" } }
      ]
    }
  ]
}
```

- **Wolverton group** (Northwestern University) — thermoelectrics and data-driven materials informatics.
- **Albert Wu group** (Taiwan) — thin-film characterization.
- **Chu group** (Kyoto University; with Yang Liu) — AI for Science.
- **Sora-at Tanusilp and collaborators** (Thailand) — thermoelectric materials.
- **Ogawa group** (Kyoto University) — hypothesis generation and citation analysis.
- **Benjamin McLellan** (Kyoto University) — computational social science.
