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
