# Text Analysis for Covid-19 Vaccine Hesitancy
This notebook explores and analyses the text dataset of people's intent expressions around COVID-19 vaccine hesitancy and brings insight into people's main concerns about COVID-19 vaccines. The recommendations are given to help public health officials to develop targeted communication and education strategies that address concerns and promote vaccine acceptance.


## 💡 Interesting Findings

### Top 10 Questions

![Top10Qs](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/top10Qs.png)

The top 10 common questions has 90-100 intent expressions/sentences and they are related to several concerns or queries such as
- effectiveness of the vaccine
- cost of the vaccine
- mistrust of vaccines which are from China or Russia
- lack of knowledge in Omicron variant
- safety meatures after getting the vaccine
- safety risks of the vaccine (including booster shot)
- doses of the vaccine


**Note:** Each question could have multiple intent expressions for example the question 'How effective is the vaccine against the Omicron variant?', the intent expressions include 'Is it worth getting the vaccine because it will not help with the new omciron variant of the virus?', 'What if the vaccine doesn't work with new omricon variant of the virus?', and all the other expressions.&nbsp;   &nbsp;   


### Key Words

![Word_Cloud](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/wordcloud.png)

As the word cloud shows, some of the most frequent words include **side, effect, booster, shoot, variant, safe, effective, people, test, long, cause, concern, children, trust, dose, dangerous, omicron** and so on. With further exploration using the technique of bigrams, some keys are discovered to appear together more often such as **side effect, omicron variant and booster shot**. 

By diving deeper into the key words or bigrams identified, it is found that side effect and children/kids have the highest number of expressions/sentences and common questions as displayed in the charts below. According to the chart, around 1000 expressions in total are related to side effect, children/kids or trust

![Sen_Qs](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/sentences_questions.png)
&nbsp;   &nbsp;   


### Most Concerned Topics - Side Effects, Kids, Trust

#### Side Effects
![Side_Effects](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/side_effects.png)

Among the expressions related to side effects,

- **38% mentions the worry about the severe side effects (such as death) or adverse reactions**
- 22% questions the side effects of the second shot or booster shot
- 12% expresses the concern about the side effects in children or women
- 8% doubts the underreporting of side effects
- the remaining reflects the lack of knowledge in the vaccine such as its side effect, the commonality of side effects and the relationship between vaccine effectiveness and its side effects. 
&nbsp;  &nbsp;  


#### Kids
![Kids](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/kids.png)

Based on the pie chart, 11% of expressions shows the unwillingness to get their children vaccinated from the parents' perspective. Some main concerns concentrate on the safety issue of the vaccine, whether the vaccine is compulsory in school, impact of the vaccine on children (such as side effects, missing school), and variances between children and adults in terms of vaccine doses and effectiveness.
&nbsp;  &nbsp;  

#### Trust
![Trust](https://github.com/amy-panda/Text_Analysis_Covid_Vaccine_Hesitancy/blob/main/images/trust.png)

The chart above indicates several factors can cause distrust of the vaccine including:
- **the origin of the vaccine such as China or Russia (33%)**
- the companies producing the vaccines (21%)
- the government (20%)
- other reasons(26%)
&nbsp;   &nbsp;   


## 📝 Recommendations

Based on the findings, a few suggestions are provided to the public health officials or the government as below:

- Be transparent about the side effects of different vaccines (such as third shot, booster shot) and how they impact different groups (such as children, women etc.);
- Provide learning resouces online or in the community to help people gain a better understanding of vaccines and things relevant to vaccines, for example how long the vaccine is effective, what are the safety measures after vaccination, what are the differences between different type of shot and so on;
- Build stronger trust between the public and the government by reporting the side effects of vaccines with integrity, enhancing the regulations and inspection on the quality of vaccines and other effective measures to rebuild the trust and improve the vaccine acceptance.


## 🛠 Techniques and Tools Used
- Data visualisation packages including Matplotlib and Seaborn
- NLP package NLTK
- Word count
- Word cloud
- Bigrams and trigrams
- Text data cleaning including lowercasing, removing punctuations, removing non-alphabatic and non-number, removing and customizing stop words, lemmatization. 



## ℹ️ Data Source
The dataset used in the notebook come from the Vaccination Information Resource Assistant [(VIRA)](https://vaxchat.org/) Coversation Corpus. Reference for the dataset:
Gretz, S., Toledo, A., Friedman, R., Lahav, D., Weeks, R., Sedoc, J., Sangha, P., Katz, Y., & Slonim, N. (2022). Benchmark Data and Evaluation Framework for Intent Discovery Around COVID-19 Vaccine Hesitancy. ArXiv. /abs/2205.11966



