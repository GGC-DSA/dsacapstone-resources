+++
title = "Visualization"
outputs = ["Reveal"]
weight = 04
author = "Anca Doloc-Mihu"
+++

{{% reveal-titlepage figure="/dsacapstone-resources/images/visualization/vizs.png" %}}

---

## What is Visualization? 

{{% fragment %}} **Visualization or visualisation is any technique for creating images, diagrams, or animations to communicate a message.** [Wikipedia](https://en.wikipedia.org/wiki/Visualization_(graphics)) {{% /fragment %}}

{{% fragment %}} <p align='left'> * Visualization through visual imagery has been an effective way to communicate both abstract and concrete ideas since the dawn of humanity.  </p> {{% /fragment %}}
 
{{% fragment %}} <p align='left'> * Examples from history include cave paintings, Egyptian hieroglyphs, Greek geometry, and Leonardo da Vinci's revolutionary methods of technical drawing for engineering and scientific purposes. </p> {{% /fragment %}}

<img src="/dsacapstone-resources/images/visualization/coliboaia-cave.jpg" height=200> <img src="/dsacapstone-resources/images/visualization/egypt-art.jpg" height=200> <img src="/dsacapstone-resources/images/visualization/greekgeom.jpg" height=200> <img src="/dsacapstone-resources/images/visualization/da_vinci.jpg" width=200>

 
---

### What is Visualization? 

**Data visualization (often abbreviated data viz) is an interdisciplinary field that deals with the graphic representation of data.**

{{% fragment %}} It is an **efficient way of communicating when the data is numerous** as for example a Time Series. 
{{% /fragment %}}

{{% fragment %}} It builds a mapping between the original data (usually numerical) and graphic elements (for example, lines or points in a chart) to show visually how the attributes of these elements vary according to the data. 
{{% /fragment %}}

{{% fragment %}} It is generally considered a branch of Descriptive Statistics, and it is argued by some authors that it is both an Art and a Science.{{% /fragment %}}

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/visualization/challenge.png" height=200 >}} {{% /fragment %}}

---

### Why is Visualization so important?

{{% fragment %}} **At their best, graphics are instruments for reasoning about quantitative information. Often the most effective way to describe, explore, and summarize a set of numbers is to look at pictures of those numbers.** [The Visual Display of Quantitative Information](https://www.edwardtufte.com/tufte/books_vdqi) by Edward R. Tufte, Yale University 
{{% /fragment %}}


{{% fragment %}} **A picture is worth a thousand words** is an English language adage meaning that complex and sometimes multiple ideas can be conveyed by a single still image, which conveys its meaning or essence more effectively than a mere verbal description. [Wikipedia](https://en.wikipedia.org/wiki/A_picture_is_worth_a_thousand_words)
{{% /fragment %}}

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/visualization/NASA-CO2comaprison.jpg" height=300 >}} 
[NASA - Comparisons of Observed CO2 and Emission Changes](https://svs.gsfc.nasa.gov/13647#29873){{% /fragment %}}

---

### Why is Visualization so important?

**Good data visualization COMMUNICATES your idea quickly to everyone**
 
{{% fragment %}} Example 1: To depict how waves of immigrants shaped the United States, a team of designers looked to nature as a model.
<div style = "height:250px" > 
 {{< vimeo 276140430 >}}
 </div>
{{% /fragment %}}

---

### Why is Visualization so important?

**Good data visualization COMMUNICATES your idea quickly to everyone**
 
{{% fragment %}} Example 2: To depict an information event in human history from Wikipedia.
[Histography](http://histography.io/)
{{% /fragment %}}

---

### Visualization Best Practices

{{% fragment %}} * As simple as possible {{% /fragment %}} 

{{% fragment %}} * Stands on its own {{% /fragment %}}

{{% fragment %}} * Minimize ink {{% /fragment %}} 

{{% fragment %}} * Label clearly {{% /fragment %}}

{{% fragment %}} * Same font size {{% /fragment %}} 

{{% fragment %}} * Significant figures {{% /fragment %}}

{{% fragment %}} * Substance over splash {{% /fragment %}} 

{{% fragment %}} * Avoid bias {{% /fragment %}}

{{% fragment %}} * Leverage Gestalt Laws of grouping {{% /fragment %}} 

{{% fragment %}} * Highlight key data {{% /fragment %}}

{{% fragment %}} * Use right graph for data {{% /fragment %}}

---

### Emphasis Guidelines for Dashboards

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/visualization/importance-dashboard.png" width=500 >}} 
{{% /fragment %}}
 
{{% fragment %}} Dominance of the neutral quadrants may change based on content. [F-Shaped Pattern of Reading on the Web](http://www.useit.com/alertbox/reading_pattern.html)
{{% /fragment %}}

---

### Types of visualizations 

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/visualization/vizTypes.png" width=500 >}} 
{{% /fragment %}}

---

### Problems with user requirements

*Can you think of any issues?*

{{% fragment %}} <p align='left'> * Lack of clarity - ambiguous language </p> {{% /fragment %}}

{{% fragment %}} <p align='left'> * Confusion - design information are not distinguished between functional and non-functional requirements  </p> {{% /fragment %}}
    
{{% fragment %}} <p align='left'> * Several requirements are defined as a single one </p> {{% /fragment %}}
    
{{% fragment %}} <p align='left'> * Incompleteness – requirements may be missing </p> {{% /fragment %}}

{{% fragment %}} <p align='left'> * Inconsistency – requirements may contradict themselves </p> {{% /fragment %}}
 
---

### How to test non-functional requirements

**It is important to be able to test/verify/check non-functional requirements**

{{% fragment %}} {{< figure src="/dsacapstone-resources/images/requirements/nonfctreqtest.png" width=500 >}} {{% /fragment %}}
    
---

### Requirement engineering

{{< figure src="/dsacapstone-resources/images/requirements/reqengineering.png" width=700 >}}

---

### Use-case Diagram

{{< figure src="/dsacapstone-resources/images/requirements/usecase.png" width=700 >}}

---

### From a “use case” to “user stories”

{{% fragment %}} <p align='left'> * Use case diagram shows <b>all things an actor can do </b> </p> {{% /fragment %}}

{{% fragment %}} <p align='left'> * Can be broken down to individual <b> user stories</b> </p> {{% /fragment %}}
    
   
