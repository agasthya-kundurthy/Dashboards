# Decpetive Visulaization Project 

Motivation:
In the modern world, there is are a lot of reasons for the demise of human beings. Various charities operate either in helping research for cures for these common causes or to help people suffering from these causes to get the appropriate treatment and hence we look at the most common causes of death in the US and the donations made to charities towards battling these causes.

Objective:
The objective of this visualization is to show how a visualization based on the data that has been chosen can be misleading. An initial claim is developed from the data that has been gathered to deceive the reader of the visualization and then a counter argument is then developed by using the data gathered and by creating a visualization from it. This is done to understand the major implications that can be caused by visualizations that convey wrong information to the reader. 

Making the Visualization:

There have been several steps in making the visualization, they include

Development Process
The development process includes several steps from forming the initial claim and a visualization to support the claim and my counter argument and developing a visualization to support my argument, that includes the following
-	Framing the initial claim.
-	Gathering Data for supporting the claim
-	Gathering data from the previous visualization.
-	Gathering data from other sources to further support my claim.
-	Using Jupyter to clean the data and combine new data to form a new dataset.
-	Developing several iterations of visualizations using Tableau.

Data Wrangling Steps
Initially, the data was collected from the previous visualization to understand the purpose of the previous visualization. The data collected had columns which specified the area of the bubbles used in that visualization and these columns were not useful as I did not wish to visualize the data as a bubble chart. I felt that a bar chart would do more justice to the data and make it much easier to compare the number of death due to the common causes of death and donations that these common causes received. This helped me in doing my first Iteration.

I had gathered new data to further understand if there is any impact on the donations made, by the cost of treatment per annum for the common causes of death. This data had been included in the Dataset used for my second Iteration.

But, these iterations only tell one side of the story, we don’t know why the donations are different for heart diseases and cancers as such. So, I researched for data that would help me understand more about this and then I included data about the likelihood of contracting these diseases. This data showed that heart diseases which cause more number of deaths in the US are also a lot more common than Cancers. The likelihood of people having a heart disease is more than any form of Cancer, this helped me developing my counter argument for my visualization and for visualizing it.

My final visualization is in two dashboards which would give a clear picture of how my initial argument does not tell the whole story and how a user can be misled by a visualization. 

Reasoning and Detours
Heart diseases cause the most number of deaths in the US but when compared to the number of deaths they cause, the donations they receive is lower than what types of cancers such as breast cancer and prostate cancer receive, although they cause lesser number of deaths. This could have been due to several reasons, when I consider the causes, some factors might be the severity of the cause of death itself or even severity of the treatment for the cause of death, Cancer patients undergo a more severe treatment than other causes, a person affected by cancer would exhibit several symptoms which are visible to the naked eye, like hair fall and other physical changes such as severe loss of weight or constant nausea etc. A person suffering from heart disease might pain of a similar magnitude but might not exhibit symptoms visible to the naked eye. Keeping these in mind, the likeliness of contracting one of the common causes of deaths were considered. This I feel gives a clear picture on which common cause of death has a sense of more common among the population and which is less common and probably causes more burden.





Initial Claim:
My initial claim was based on the number of deaths that are caused by the more common cause of deaths and the donations that are collected towards battling these causes. From visualizing the data for the above mentioned, I developed the initial claim to be – ‘Heart diseases cause more deaths but Cancers receive more donations’. The number of deaths and the donations act as warrants for my claim.

Counter Argument:
Based on further research for the possible causes of the variation in donations and changing the metrics to other data points gathered such as the likelihood of common causes of death and the cost of treatment that is associated with the causes, I developed my counter argument to be ‘Cancers are less likely and more expensive, so they get more donations’.


Iterations (Intermediate Prototypes):
In the first Iteration of my visualization, I had considered the data of the number of deaths due to the common causes and what were the donations from charity for the same. This has been represented as a Bar Chart, now it is easier to understand which diseases are getting more money from charity. But this still doesn’t clearly tell me why people donate more to these diseases. This graph is only useful in letting people understand a comparison on number of deaths caused by common causes and money donated from charity to these deaths. 

In the second Iteration of my Visualization, I had added the data of treatment costs per annum for the common causes of death. This gives me an idea about how effective the donations might be. But this also doesn’t explain about why there is a difference in the donation amounts.

Final Visualization:
Two visualization have been created to create the impact that a deceptive visualization would have on the reader.

Initial Claim
‘Heart diseases cause more deaths but Cancers receive more donations’
The first dashboard reflects my initial claim that is based on the data that I had chosen; a scatter plot is used in the visualization as a bar graph was not good because of the huge variations between two elements.



Counter Argument
‘Cancers are less likely and more expensive, so they get more donations’.
For the counter argument of my visualization of my visualization, I have included the likeliness of contracting(Risk) each of the most common causes of death. This along with the cost of treatment(Cost) lets me know that the highest donations are to diseases that are less likely to occur and at the same time have higher costs of treatment. I have represented this as a scatter plot because, the treatment costs of the disease and the risk of contracting those diseases are two separate entities, there are huge gaps in the costs of treatment and combining these could be effectively shown in a scatter plot. 
In addition to this, I have combined the bar charts of my previous visualizations and changed the representation to a scatter plot which shows the number of deaths caused and donations received by the common causes of death. This gives a clearer picture to the reader as to the reason of why there is a huge difference in the donations received by heart diseases and cancers.

Roadmap to the Future:

Now we understand the reason behind donations made by public, why cancers typically get more donations than heart diseases which account for the most number of deaths in the US. A future enhancement for this would be to look at how effective these donations are. Do these donations make a huge difference for the patients suffering from these diseases as whole or they are concentrated only on a set of patients that are lucky enough to receive these donations and if they are sufficient to ensure a long-term solution if possible.

