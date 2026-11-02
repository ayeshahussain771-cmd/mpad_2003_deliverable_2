**Date**<br>
**MPAD 2003A – Introductory Data Storytelling**<br>
**Ayesha Hussain**<br>
**Presented to Jean-Sébastien Marier**<br>

# Deliverable 2: Exploratory Data Analysis (EDA)

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

## Foreword

For this assignment, you must clean and analyze the dataset from Deliverable 1, create exploratory charts/visualizations, and identify a potential story. Your assignment must clearly detail your process. You are expected to write about 1,000-1,200 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.

## 1. Getting Data
For this assignment, I will be analyzing the City of Ottawa's [Street Lights dataset](https://open.ottawa.ca/datasets/street-lights/about) from the Open Ottawa data portal. My story focuses on street lighting in Ottawa, especially in areas where people might be walking alone or taking public transit at night. I wanted to see what kinds of street lights are being used throughout the city and whether or not there are any patterns that are worth looking into.

I found the dataset by searching the term 'Street Lights' on the Open Ottawa data portal. I downloaded the data as a CSV file and imported it into Google Sheets by going to File, Import, Upload, then selecting the file. The link to the spreadsheet can be found [here](https://docs.google.com/spreadsheets/d/12CwZ0jz5Pu-L2EY8kiHbW2zAw3cVcyki4Zd8j9Lw20I/edit?usp=sharing).


![Street Lights dataset](street-lights-import.png)

*Figure 1: The City of Ottawa Street Lights dataset after importing it into Google Sheets.*

The data set has 80,670 data rows and 21 columns, not including the header row. As I was looking through it, I noticed a few things that looked unusual, like empty cells under the REFRACTOR section, some pole heights being listed as zero, and some installation dates saying they were from December 30th, 1899. I'm not sure why they're listed like that, so I'll have to look into them when cleaning the data.

Three columns that stood out to me were LIGHT_SOUR, POLE_HEIGHT, and HEAD_STYLE. LIGHT_SOUR shows the different types of light sources, like LED and HPS, which are nominal categorical variables. POLE_HEIGHT contains the numerical measurements of pole heights, making it a continuous numerical variable. Lastly, HEAD_STYLE shows the different styles of light fixtures, like COBRA HEAD and CLDM, which are also nominal categorical variables.

A question I want to explore is whether LED or HPS lights are more common on certain streets in Ottawa.


## 2. Understanding Data

### 2.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As seen in Bounegru & Gray (2011), a data visualization should be clear...

### 2.2. Cleaning Data

Insert text here.

### 2.3. Analyzing Data

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 3. Delivering Data

Insert text here.

## 4. References

Include a list of your references here. Please follow [APA](https://apastyle.apa.org/style-grammar-guidelines/references) or [MLA](https://www.mla.org/MLA-Style) guidelines for references. Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
