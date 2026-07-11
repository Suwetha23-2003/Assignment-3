---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Assignment 3 Presentation
#### Suwetha A/P S Raman Naidu
#### Universiti Malaysia Perlis
#### [s241042546@studentmail.unimap.edu.my](mailto:s241042546@studentmail.unimap.edu.my)

<!-- __AUDIO_INTRO_DO_NOT_TOUCH__ -->

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Slide one
**Key Concepts:**
- Energy conservation per @carnot1824.
- $\Delta U = Q - W$
:::

::: {.column width="50%"}
![](media/pics/sample.png)
:::
::::

---

<span class="slide-title" data-title="My Hidden Slide Name"></span>

![](media/pics/wide.jpeg)

---

:::: {.columns}
::: {.column width="50%"}
### The Master Equation
The fundamental relation of thermodynamics:

$$\Delta U = Q - W$$

The work done $W$ is positive when the system expands against an external pressure.
:::

::: {.column width="50%"}
<video data-src="media/videos/sample.mp4" data-autoplay loop muted width="100%"></video>
:::

::::

---

:::: {.columns}
::: {.column width="50%"}
### Visualizing the Gas Law
**Interactive Model:**

- P, V, and T relationships.
- Use the slider to adjust pressure.
- Observe the phase boundary.
:::

::: {.column width="50%"}
<iframe 
  data-src="media/plots/sample.html" 
  width="100%" 
  height="500px" 
  style="border:none;" 
  scrolling="no">
</iframe>
:::
::::
---

<div class="columns">
  <div class="column" style="width:48%;">

  # ANOVA: Effects on Part Resistance (Machine 1)

  Statistical analysis using ANOVA was performed on Part Resistance data from Machine 1 to assess the impact of varying Pressure and Temperature, and their interaction.

  - **Pressure Effect:** $P$-value = `0.8476` (Rounded to 4 decimal places, or 0 if too small). The effect of pressure on part resistance is **not significant**.
  - **Temperature Effect:** $P$-value = `0.0000` (Rounded to 4 decimal places, or 0 if too small). The effect of temperature on part resistance is **significant**.
  - **Pressure*Temperature Interaction:** $P$-value = `0.0822` (Rounded to 4 decimal places, or 0 if too small). The interaction effect between pressure and temperature is **not significant**.

  *Conclusion:* Both pressure and temperature independently have a significant effect on the part resistance. The interaction between them is not significant, indicating their effects are independent. Since the USL is 10 and a lower resistance is better, engineers should aim for conditions that minimize resistance.

  </div>
  <div class="column" style="width:48%;">
    <iframe data-src='media/plots/machine1_resistance_boxplot.html' width='100%' height='500px' style='border:none;'></iframe>
  </div>
</div>
