---
layout: page
title: Protein Cost & Density Visualization
permalink: /protein-viz/
---

| [home page](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Visualizing Government Debt](/Aspdelus-dataviz-portfolio/dataviz-examples) | [Critique and redesign (MakeoverMonday)](/Aspdelus-dataviz-portfolio/protein-viz) | [final project I](/Aspdelus-dataviz-portfolio/final-project-part-one) | [final project II](/Aspdelus-dataviz-portfolio/final-project-part-two) | [final project III](/Aspdelus-dataviz-portfolio/final-project-part-three) |

# Makeover Monday — Protein Cost & Density

This page documents my critique-by-design process and the final redesigns comparing **cost per 30g protein** and **protein density (% of weight)**, with a focus on **Vegetarian vs. Non-Vegetarian** options.

---

## 1) Original Visualization


![Original visualization](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/makeovermonday_original.png)

**Why I chose it**  
The original chart mixed different comparison bases (e.g., cost per package vs. per serving) and used heavy imagery. This made it hard to answer a simple question (“Which sources are cheapest per equal amount of protein?”) at a glance. I wanted to standardize the metric, reduce clutter, and emphasize vegetarian vs. non-vegetarian comparisons.

---

## 2) Critique Highlights (Stephen Few’s DVEP)

- **Purpose & Message:** The takeaway wasn’t directly visible because units weren’t standardized.  
- **Appropriate Encodings:** Bars are appropriate for *one number per category*, but the original mixed icons and pictures that distracted from the quantitative task.  
- **Scale & Units:** Lack of a clear, shared unit (e.g., cost per *equal* protein) reduced comparability.  
- **Audience Fit:** For cost-conscious readers (e.g., students, fitness hobbyists), the most useful view is *normalized cost per equal protein amount* and optionally *protein density* for diet planning.  

*(I used the DVEP heuristics per assignment instructions.)* :contentReference[oaicite:0]{index=0}

---

## 3) Redesign Goals

1. **Standardize the metric** → Cost **per 30g protein** across all items.  
2. **Add a complementary lens** → **Protein density (% of food weight)** to reflect how “protein-packed” each option is.  
3. **Clarify categories** → Color and filter for **Vegetarian vs. Non-Vegetarian**.  
4. **Keep it clean** → Remove distracting imagery; use ranked horizontal bars.



---

## 4) Final Visualizations (Interactive)

### A) Cost (USD) per 30g Protein by Food Source (Vegetarian vs. Non-Vegetarian)

<!-- Interactive embed -->
<div class='tableauPlaceholder' id='viz1758140126855' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Cost(USD) per 30g Protein by Food Source (Vegetarian vs Non-Vegetarian) '
           src='https://public.tableau.com/static/images/Pr/ProteinbyFoodSource/Costper30gProtein/1.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='ProteinbyFoodSource/Costper30gProtein' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/Pr/ProteinbyFoodSource/Costper30gProtein/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1758140126855');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

**How to read it:** Lower bars = cheaper **per equal protein (30g)**. Use the **Diet Choice** dropdown to isolate Vegetarian or Non-Vegetarian foods.

---

### B) Protein Density by Food Source (Protein % of Weight)

<!-- Interactive embed -->
<div class='tableauPlaceholder' id='viz1758140132083' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='Protein Density by Food Source (Ranked by Protein % of Weight) '
           src='https://public.tableau.com/static/images/Pr/ProteinDensitybyFoodSource/On-DietRanking/1.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='ProteinDensitybyFoodSource/On-DietRanking' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/Pr/ProteinDensitybyFoodSource/On-DietRanking/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='zh-CN' />
    <param name='filter' value='publish=yes' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1758140132083');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

**How to read it:** Higher bars = foods with a greater share of protein by weight (useful for high-protein, lower-calorie planning).

---

## 5) What Changed vs. the Original

- Standardized **unit of comparison** (cost per **30g** protein).  
- Added **Diet Group** color and **Diet Choice** control for quick filtering.  
- Clear **ranking** and labels to make the takeaway immediate.  
- A separate view for **protein density**, complementing the cost view.

## Data, Tools & Reproducibility

**Data Source:** Makeover Monday – "The Cheapest Ways to Get Your Protein" (2023 W8) via Data.world  
**URL:** <https://data.world/makeovermonday/2023w8>

**Tools Used:**
- Tableau Public for interactive visualizations
- Data.world for data sourcing
- Stephen Few's Data Visualization Effectiveness Profile (DVEP) for critique framework

**Skills Demonstrated:**
- Visualization critique using established frameworks
- Data standardization and metric design
- Audience-focused redesign
- Interactive dashboard creation

---

## Reflection

This assignment taught me the importance of:
1. **Standardized metrics** — Ensuring fair comparisons by normalizing data
2. **Audience awareness** — Designing for specific user needs (cost-conscious consumers)
3. **Visual clarity** — Removing unnecessary elements to focus on key messages
4. **Iterative design** — Using critique frameworks to systematically improve visualizations

---

**Navigation:**  
[← Previous: Government Debt](/Aspdelus-dataviz-portfolio/dataviz-examples) | [Back to Home](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Next: Final Project →](/Aspdelus-dataviz-portfolio/final-project-part-one)

