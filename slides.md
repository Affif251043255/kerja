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

## Sample slides
#### Affif251043255
#### Universiti Malaysia Perlis
#### [your_email@example.com](mailto:your_email@example.com)

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

:::: {.columns}
::: {.column width="50%"}
### Machine 1: Part Resistance Analysis

Machine 1 operating at 303 K and 100 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m1.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2: Part Resistance Analysis

Machine 2 operating at 338 K and 200 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m2.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 3: Part Resistance Analysis

Machine 3 operating at 373 K and 300 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m3.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---


## Conclusion & Thank You

Based on the analysis of Part Resistance across different machine operating conditions, we can draw insights into process stability and adherence to specifications. It's evident how changes in temperature and pressure affect the output quality. 

Thank you for your attention!

---

:::: {.columns}
::: {.column width="50%"}
### Statistical Significance of Factors on Part Resistance

To understand how different factors affect Part Resistance, an Analysis of Variance (ANOVA) was performed with `PartResistance` as the dependent variable and `Machine`, `Temperature`, `Pressure`, and their interactions as independent variables. The goal is to identify which factors or interactions have a statistically significant impact on the resistance.

Key values to observe from the ANOVA table (from the previous R cell output) are:
- **Resistance, Pr(>F) for Pressure**
- **Resistance, Pr(>F) for Temperature**
- **Resistance, Pr(>F) for Pressure:Temperature (Interaction)**

_A smaller Pr(>F) value (typically < 0.05) indicates a statistically significant effect. Remember, for Part Resistance, lower values are generally better, and there is no Lower Specification Limit (LSL) defined beyond this preference._
:::

::: {.column width="50%"}
<!-- Placeholder for ANOVA output if it can be dynamically injected, otherwise user refers to console -->

_Please refer to the output of the preceding R cell for the full ANOVA table and specific Pr(>F) values._
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 1: Part Resistance Analysis

Machine 1 operating at 303 K and 100 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m1.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 2: Part Resistance Analysis

Machine 2 operating at 338 K and 200 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m2.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Machine 3: Part Resistance Analysis

Machine 3 operating at 373 K and 300 kPa. The Upper Specification Limit (USL) for Part Resistance is 10 Ohms. The lower the resistance, the better. This box plot visualizes the distribution of part resistance under these conditions.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_m3.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

## Conclusion & Thank You

Based on the analysis of Part Resistance across different machine operating conditions, we can draw insights into process stability and adherence to specifications. It's evident how changes in temperature and pressure affect the output quality. 

Thank you for your attention!

---

:::: {.columns}
::: {.column width="50%"}
### Part Resistance Across All Machines

This box plot illustrates the distribution of Part Resistance for Machine 1, Machine 2, and Machine 3, allowing for a direct visual comparison against the Upper Specification Limit (USL) of 10 Ohms. It highlights differences in resistance levels and variability under their respective operating conditions. The lower the resistance, the better.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_all_machines_resistance.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

## Conclusion & Thank You

Based on the analysis of Part Resistance across different machine operating conditions, we can draw insights into process stability and adherence to specifications. It's evident how changes in temperature and pressure affect the output quality. 

Thank you for your attention!

---

:::: {.columns}
::: {.column width="50%"}
### Part Resistance Across All Machines

This box plot illustrates the distribution of Part Resistance for Machine 1, Machine 2, and Machine 3, allowing for a direct visual comparison against the Upper Specification Limit (USL) of 10 Ohms. It highlights differences in resistance levels and variability under their respective operating conditions. The lower the resistance, the better.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/plot_all_machines_resistance.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Comparative Analysis & Data Limitations

We aimed to compare Part Resistance across Machine 1, Machine 2, and Machine 3 to understand their responses to changes in Pressure and Temperature, and to identify significant factors via ANOVA. 

**Current Data Limitation:** The loaded dataset (`X002..3.`) primarily contains data only for **Machine 1** (at 303 K and 100 kPa). This means that:

1.  **Comparative Box Plots:** The 'Comparative Part Resistance Across Machines' plot currently visualizes data only from Machine 1, as data for Machines 2 and 3 are not present in the dataset.
2.  **ANOVA for Interactions:** A meaningful Analysis of Variance (ANOVA) to assess the impact of `Machine`, `Temperature`, `Pressure`, and their interactions cannot be fully performed without data from all machines operating under their specified conditions. The ANOVA performed previously would predominantly reflect variation within Machine 1's data or indicate an inability to calculate for other levels.

To conduct a comprehensive comparative analysis and a robust ANOVA, the full dataset including `PartResistance` measurements for Machine 2 (338 K, 200 kPa) and Machine 3 (373 K, 300 kPa) would be required. 
:::

::: {.column width="50%"}
<!-- A visual placeholder or a summary of findings specific to Machine 1 could go here -->

_Please ensure the `data/` folder contains CSV files with data for Machine 2 and Machine 3 operating under their respective conditions (as described in the prompt) to enable a full comparative analysis._
:::
::::
