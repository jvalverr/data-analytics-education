# Advanced Large Language Models & Visualization Tools for Data Analytics Learning

Welcome to our project on **Advanced Large Language Models & Visualization Tools for Data Analytics Learning**! Our mission is to revolutionize the way non-computational professionals and students learn data analytics. We do this by harnessing the power of cutting-edge AI technologies like [GPT-4](https://openai.com/index/gpt-4-research/) and the advanced visualization capabilities of tools like [LIDA](https://github.com/microsoft/lida). Our research, supported by extensive case studies and published in specialized conferences and journals, shows how these tools can drastically improve both the speed and quality of data-related disciplines education. Join us on this exciting journey to make data analytics and data science more accessible, efficient, and engaging for everyone!


## Project Overview

This project, based on two comprehensive studies, explores the use of advanced Large Language Models (LLMs) and visualization tools to enhance data analytics learning for students and professionals from non-computational backgrounds. The methodologies and outcomes described herein underscore the significant benefits of integrating cutting-edge AI technologies such as based on Generative AI (GenAI) into educational practices to foster a deeper understanding and more efficient execution of data-related projects.

### Project Objectives

- Promote a comprehensive understanding of data-based project pipelines.
- Enhance programming and other computational thinking-related skills through interactive AI assistance.
- Enable wider adoption of GenAI tools in educational contexts.
- Improve the efficiency and effectiveness of data-related project development.


### Methodology
All participants completed the same analytics project within a timed session that emphasized three CRISP-DM phases explicitly taught beforehand: **Business Understanding**, **Data Understanding**, and **Evaluation**. Each person experienced **three approaches** to the same task under guided pacing. Instrumentation captured **time-to-completion** and **perceptions** of each approach along four dimensions: *ease of use*, *speed of result*, *appropriateness* (fit to the analytical objective), and *correctness* of outputs.

The three approaches studied were:
- Traditional Approach: Participants first completed a data analytics project using standard Python packages (e.g., scikit-learn, pandas, seaborn) in Google Colab.
- ChatGPT Approach: Participants then repeated the project with conventional ChatGPT assistance, using the tool mainly for generating code snippets.
- LIDA + GPT Approach: Finally, participants completed the project using LIDA integrated with the GPT-4 API, enabling automated data summarization, exploration, and advanced visualizations in response to any prompt originating from the project’s source code itself.

### Participants and sample composition
The study involved **59 participants** (students and professionals) at Tecnológico de Monterrey from a broad set of non-computing disciplinary backgrounds. 

![Sample composition — role × gender](images/IMAGEN1.jpg)

*Figure 1 — Current role by gender.*

From the cohort, 32 participants identified as female, 27 as male, and 1 preferred not to disclose. Most participants were students, with balanced gender representation inside that group. 

![Sample composition — affiliation](images/IMAGEN2.jpg)

*Figure 2 — Affiliation (major field or sector).*

Specifically, 88% of participants came from fields such as finance, business, social sciences, and others, while the remaining 12% were from engineering disciplines including sustainable engineering, chemical engineering, biomedical engineering, and industrial engineering.

![Sample composition — age range](images/IMAGEN3.jpg)

*Figure 3 — Age distribution.*

The age distribution is skewed toward younger learners, consistent with an academic setting, yet it includes professionals as well. This spread enables contrasts in how prior work experience interacts with each approach.

### Background: Prior Skills and Exposure
In addition to demographics, we documented prior exposure to programming, analytics, and AI tools to contextualize later perceptions:

![Background — programming experience by age × role × gender](images/IMAGEN5.jpg)

*Figure 5 — Distribution displaying participants' programming experience by role, ranging age, and gender.*

The figure shows no significant disparity in programming experience across all roles, genders, and age groups, except for professionals over 50 years, where we found participants identified as female with no prior programming experience. The same task therefore does not imply the same cognitive load, assistance through ChatGPT or a structured path (LIDA + GPT) does not benefit all subgroups equally.


![Background — tools experience (Python/Colab, etc.)](images/IMAGEN7.jpg)

*Figure 7 — Distribution of participants' experience in data analytics-related skills by role, age range, and gender.*

The technical base is moderate but uneven. The gender group that presents the greatest disparity in data analytics-related skills is female across roles and age groups. This is most clearly seen in the younger groups, where half or more of the males have at least some experience in data analytics, while among females, half or fewer possess these skills.

![Background — time required to finish activities (by role and approach)](images/IMAGEN9.jpg)

*Figure 9 — Distribution of participants' experience related to the use of generative AI tools like ChatGPT. (Top left corner) Distribution of participants who had previously used ChatGPT for general purposes. (Top right corner) Distribution of participants who had previously used ChatGPT for programming tasks. (Bottom left corner) Distribution of participants who had previously used ChatGPT for data analytics project development. (Bottom right corner) Distribution of participants who had previously used APIs from any LLM provider, such as OpenAI.

Despite being just over 2 years since the launch of ChatGPT, given the popularity of the platform, one could assume that all participants would have had some prior experience with it. However, our data reveals that 15% of participants have had no prior interaction with this generative AI tool.

### Results
We summarize the main findings of the investigation here.

**1) Time to finish.**  
Approaches supported by GenAI enabled faster completion for many participants. In particular, **ChatGPT** frequently concentrated times in the lower intervals, while **Traditional** clustered toward longer spans. Professionals tended to finish faster, but students benefited markedly from AI support.

![Outcome — time required to finish activities (by role and approach)](images/IMAGEN10.jpg)

*Figure 10 — Time required by approach and role (stacked categories).*


**2) Perceived ease and speed.**  
Across roles and genders, participants most often identified **ChatGPT** as the **easiest** and **fastest** way to progress once the task was understood.

**3) Perceived appropriateness and correctness.**  
When the criterion shifted to **fit to the analytical objective** and **correctness** of outputs, **LIDA + GPT** was most frequently favored. Its structured flow (summary → goals → visualization spec) helped keep attention on the target once configured.

![Outcome — perceived metrics by role](images/IMAGEN11.jpg)

*Figure 11 — Ease, Speed, Appropriateness, Correctness by role (Students vs. Professionals).*

The same pattern holds across roles: ChatGPT aligns with ease and speed, while LIDA + GPT aligns with appropriateness and correctness, suggesting that perceptions reflect the **nature of the assistance** rather than background alone.

![Outcome — perceived metrics by gender](images/IMAGEN12.jpg)

*Figure 12 — Ease, Speed, Appropriateness, Correctness by gender.*


### Discussion
The higher levels of participant preference indicate the superiority of integrating advanced generative AI tools like GPT with specialized frameworks such as LIDA over traditional development methods. The three approaches display **distinct learning curves**. The **Traditional** path asks novices to integrate many components, which costs time and attention. **ChatGPT** reduces the startup load and accelerates iteration, but it still requires careful human judgment to verify and assemble a coherent solution. **LIDA + GPT** introduces initial overhead (API setup and configuration) followed by a smoother, goal-oriented path that participants perceived as more appropriate and correct.

### Conclusions
This work highlights the potential of employing generative AI-based tools to revolutionize the development of data analytics competencies among students and professionals, regardless of their computational background. Our findings suggest that such integration can significantly enhance the learning of advanced skills, especially those related to data analytics. We aim to establish this study as a foundation for the methodical adoption of generative AI tools in educational settings, paving the way for more effective and comprehensive training in these critical areas

---

## Materials
- Journal article published at Frontiers in Education [open access here](https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2024.1418006/full)
- Data from Case Study used to obtain results for our journal article [available here](https://www.frontiersin.org/api/v3/articles/1418006/file/Data_Sheet_1.csv/1418006_supplementary-materials_datasheets_1_csv/1?isPublishedV2=false)
- Conference extended abstract published at proceedings of IACEE 2024 [free access here](https://www.researchgate.net/publication/382695760_Empowering_Data_Analytics_Learning_Leveraging_Advanced_Large_Language_Models_and_Visualization_Tools)
- Conference presentation [access here](https://github.com/jvalverr/data-analytics-education/blob/main/materials/session7-JorgeValverde-IACEE-24.pdf)

---

## Generate the Images 

### 1) Environment (Python 3.10+)
```bash
pip install -U pandas numpy matplotlib seaborn plotly scipy dython
```

### 2) Data
Download the CSV from the article’s **Supplementary material** and place it where you prefer (recommendation: `materials/`).  
Link: https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2024.1418006/full#supplementary-material


### 3) Run
```bash
jupyter notebook Data_processing.ipynb
```
The notebook will generate or update figures under `images/`.

---

## Citation

When referencing this project, please use the following citation formats:

**Journal Article:**

Valverde-Rebaza, J., González, A., Navarro-Hinojosa, O., & Noguez, J. (2024). *Advanced large language models and visualization tools for data analytics learning*. Front. Educ. 9:1418006. DOI: [10.3389/feduc.2024.1418006](https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2024.1418006/abstract).

```bibtex
@article{valverde:frontiers:24,
  title={Advanced large language models and visualization tools for data analytics learning},
  author={Valverde-Rebaza, J. and González, A. and Navarro-Hinojosa, O. and Noguez, J.},
  journal={Front. Educ.},
  volume={9},
  pages={1418006},
  year={2024},
  doi={10.3389/feduc.2024.1418006}
}
```

**Conference Extended-Abstract:**

Valverde-Rebaza, J., González, A., Navarro-Hinojosa, O., & Noguez, J. (2024). Empowering Data Analytics Learning: Leveraging Advanced Large Language Models and Visualization Tools. Proceedings of the 19th World Conference on Continuing Engineering Education, IACEE 2024, pp. 47-49. ISBN: 978-1-7327114-3-3.

```bibtex
@inproceedings{Valverde:iacee:24b, 
 author = {Valverde-Rebaza, J. and González, A. and Navarro-Hinojosa, O. and Noguez, J.},
 title = {{Empowering Data Analytics Learning: Leveraging Advanced Large Language Models and Visualization Tools}},
 booktitle = {Proceedings of The 19th World Conference on Continuing Engineering Education},
 series = {IACEE 2024},
 pages = {47--49},
 isbn = {978-1-7327114-3-3},
 publisher = {IACEE},
 year = {2024}
}
```
