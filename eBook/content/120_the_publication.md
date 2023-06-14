---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.14.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# 2. THE PUBLICATION

<div style="margin-top:20px;">
<span style="font-size:18pt; color:teal;font-weight:bold;">The Canadian Spring 2023 Wildfire Season - an unprecedented and ongoing disaster</span>
</div>
    
<span style="font-size:12pt; font-weight:bold; color:teal; font-style:italic; font-family:serif;">The Spring of 2023 Canadian wildfire season brings unprecendented levels of bad air quality to the American Northeast.</span> 
    
<div style="font-style:italic;color:teal;font-size:11pt;margin-top:25px;margin-bottom:50px">
    <div style="margin-left:100px">
    Raynier A. van Egmond<br>
    Earth Observation for Citizen Science program<br>
    Number 1 / Volume 1 in the "The See 4 Yourself" - series<br>
    Vashon Island (WA) USA.<br>
    </div>
</div>

Because we want the content of the pages to be dynamically connected with the results from the THE SCIENCE segment we need to build up the "Python environment" for the executable code-cells in the page. While the namespace of the code-cells is the running kernel I prefer to keep the chapter files self-contained. This means that  each page will start with a code-cell that imports the Python libraries that are required for that page. 

```{code-cell}
:tags: [remove-cell]
from myst_nb import glue               # this is used to support references between markdown and code
```

## Summary

The Canadian Spring 2023 Wildfire Season combined a persistent weather pattern over the Northeast of the continent with the worst fire outbreaks in modern history to create a new record for low air quality for the American Northeast. A fire season that started in the province of British Columbia in the months of April - May. The focus shifted to the eastern Canadian province of Quebec in early parts of June. The cyclone weather pattern over the East of the country created a persistent flow of air that forced the smoke of hundreds of major wildfires over the US Eastern seaboard and most notably cities like New York.

The analysis provided in the research section of the publication will show you how to access satellite imagery and atmospheric datasets to see how bad the airquality has been during the start of the month of June. The training will use imagery to locate fire-hotspots in the landscape and imagery to view and animate visual smoke images and air particulates in animations.

## Content

This section will be the main content for the publication

```{admonition} **WRITER'S HINT**
The next chapter outlines the structure of a feature article based on a story narrative. This is the formula we will be using for our publications since it is a solid, proven structure. For the topic of the publication look at the descriptions of the 5-stage story structure and fill it with relevant stuff. Remember that the narrative is story; there are protgonists, antagonists and the like. We want the reader to identify with the protagonists and often times picture themselves as the protagonist. 
```

## WORK TEMPLATE: Elaborate on the catch-components

This section should use the 5-stage feature-writing outline as discussed in the book... This is a writer's guide to formulating a proper narrative journalism-based publication. In the final version this content will be removed/archived and will not be part of the publication itself.  

exposition
: <font color="teal">Setting the scene</font>. The exposition is the initial part of the story in which the stage is set for the main action. Early questions are answered here, including where and when the story is set. The main characters who will be involved in the story may also be introduced, with their basic life being painted. The exposition also introduces the point of view, the position from which the story is being told (often an objective third person).
: the research points include:
<font color="darkorange">**(1)**</font> what is the normal situation before everything went belly-up? 
<font color="darkorange">**(2)**</font> who are the protagonists that we want the reader to identify with? 
<font color="darkorange">**(3)**</font> what is the atagonist and how did it get into the picture?

rising action
: <font color="teal">Building the tension</font>. After the relative calm of the exposition, there is a gradual raising of the tension in the story using danger, hazard, conflict and other devices. The reader is usually deeply involved in this, struggling with other people and their own ability to handle the tension. Rising action is often long and relatively slow, and may occur through several storylines which all act together to create the excitement in the story.
: **the research points include**:
<font color="darkorange">**(1)**</font> how  did the event develop (examples, statistics, graphs)?

climax
: <font color="teal">The exciting or horrible bit</font>. After the long and steady rising action within a story or sub-plot, at last things come to a head in the climax of the story. The climax is often the most exciting part of the story, where a lot of major action happens. This relates to the protagonists; the people sufferering from the event.
: **the research points include**:
<font color="darkorange">**(1)**</font> how does the event practically/explicitely impact the protagonists (examples, statistics, graphs)? 

falling action
: <font color="teal">Tidying up loose ends</font>. After the excitement of the climax, the story may not yet be complete and there can still be unresolved and outstanding tensions that are waiting for closure. These are largely resolved in the falling action stage, as the last few issues are mopped up. This looks at the aftermath as it relates to the protagonists; the sufferers of the event.
: **the research points include**:
<font color="darkorange">**(1)**</font> with the event over where does it leave the protagonists (examples)? 
<font color="darkorange">**(2)**</font> where does it leave the context of the event (examples)? 

denouement
: <font color="teal">Final resolution/summary of a story</font>. At this point all unresolved issues are resolved and mysteries explained. The denoument may also be used as a form of housekeeping to keep the overall flow of the story neat and tidy, and resolving any left-over tensions.
: **uses for a denouement include and research topics**:
<font color="darkorange">**(1)**</font> Explaining reasons why things happened as they did.
<font color="darkorange">**(2)**</font> Wrapping up loose ends.
<font color="darkorange">**(3)**</font> Giving reward, punishment and other closure to characters.
<font color="darkorange">**(4)**</font> Showing how things return to normal after all the excitement.
<font color="darkorange">**(5)**</font> Describing what happens in the future to the main characters.
<font color="darkorange">**(6)**</font> Preparing for a sequel story.


### **the context**: the normal situation of climate and weather
This is the point where the standard situation for the northeast is decribed; large tracks of forests with little habitation and population centers, no fires -- a pristine environment... under threat... ---

### **protagonists**: the people and the health impared

Describe the situation for the general populus and the health impared; those with respiratory problems. 

### **antagonists**: The Air-quality Hazard Levels

* why of relevance to the reader...
* how does it stack up historically...
  * for the region
  * for New York city
* what does this mean in practical terms; packages of sigarettes...
* how does it impact the poor-of health and people with preconditions...


### **antagonists**: Geographical Scale of the Fires:

The scale of the fires in the early Spring was of unprecendented size.

* the number of active fires across the country...
* the surface area scorched...


### **antagonists**: The Atmospheric Circumstances:

The cyclonic weather pattern that established itself over the eastern Canadian provinces funneled all the smoke, sooth and organic carbon particulates towards the US eastern seaboard and cities like New York

* Was this a typical weather pattern? If so then with increased fires this will become a recurring situation in the US northeastern region not unlike people in the pacific Northwest have to deal with
* Illustrate the pattern with animations.

