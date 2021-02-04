# Overview
  This study utilizes a new and robust method to assess well-being in a real-world setting, with a large sample size (Sample = 821; Prompts = 7357). Its method and insight could be generalized to assess subjective experience of any sort, with careful investment into the questions asked.


## 1) Challenge
- Lack of research on micro-level or momentary human experience
- Past result of intervention on momentary well-being might be containminated by momentary valence-of-thought (e.g. the participants might be happy just because she's thinking about pleasant things that the moment, which is not due to the factor or intervention of interest)
- A mind-wandering mind is an unhappy mind?
  

## 2) Aim
- Use experience sampling method to study how momentary well-being is influenced by other subjective factors. 
- Include a valence-of-thought question and later take it into control. Do a more robust assessment on the effect of attention state on momentary well-being by taking valence-of-thought into consideration.
- Explore the effect of activity and other subjective experience on momentary well-being.



## 3) Approach
![](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/ESM_flowchart.png)
## 4) Method

### Generalized linear mixed effect modeling 
- Attention State (and Controllability, and their interaction) as the fixed effect(s)
- Participant ID and their Current Activity are crossed random effects

### Approach of reporting
- Significance test of model comparison (a full model vs. a lesion model without the effect of interest)
- Partial eta-square

## 5) Results

#### Descriptive findings: 

##### 5.1) How often do we pay attention to the here-and-now, not attending to the here-and-now, versus no thoughts at all during waking time? - More than half of our waking time are at-present, phew!
![](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/AttentionDistribution.png)

##### 5.2) If we are interested in the modalities of thought, we can further distribute the prompts based on attention state and modality. We can zoom in to focus on one modality (in this case, verbal thoughts) if that would deepen our understanding of something more specific. 
![](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/ActivityWellbeing.png)
###### 5.3.2) Visualize the range of well-being as a function of attention state 
![](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/AttentionWellbeing.png)
###### 5.3.3) Does attention state contribute to well-being over-and-beyond the pleasantness of thought? - Yes!  Further, there is no meaningful interaction between attention state and valence when predicting well-being
![](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/AttentionValenceInteract.png)


# A more detailed and formal report of the project. Can be found in the second half of the PDF report [here](https://github.com/EvieXinqiGuo/EvieXinqiGuo_Portfolio/blob/main/Experience%20Sampling%20Project/Experience%20Sampling%20Project%20Walk%20Through.pdf)  
