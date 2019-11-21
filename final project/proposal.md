
### DAV 5400 Final Project Proposal
#### Team member: Zhihong Zhang
## Introduction 
Social media plays a crucial role in our daily life.  Along with this fact, there is also an enlarging need for advertisement and commercial marketing on social media. In addition, according to an online survey, 88% of social marketers said that it is important for their brands to provide customer service through social media. 

Based on one of the recent statistics, 79% of American internet users are utilizing  Facebook, and it suggested that the Facebook is one of the most influential social media platform. As a result,  this research will focus on the product advertisement on Facebook. Ideally, this research can create a suitable model via patterns found in the customer advertisement data and the model can be generalized into other social medial platforms.

## Research Questions
The main question I have for this research will be the correlation between different variables within a Facebook product page. For example, how the interaction between users and their posts may impact the builds of the product brand . Other questions raised will also be based on this main question, and the focus is to find the main factors affecting marketing efficiency.

After finding the pattern of the data set, I would like to validate the the model by using other data derived by my later texting mining process .

I believe the model can be used to increase the efficiency of social media advertising. It not only may reduce the unnecessary costs on advertisement and  may help different brands to effectively communicate with customers. In other words, the model will serve as an optimization process for advertising.

## Data to be Used
The initial data set that will be used for this research comes from the  UCI repository http://archive.ics.uci.edu/ml/datasets/Facebook+metrics# . The data set is a csv format file which can be easily loaded into Python by utilizing the pandas package.  This data set addresses a popular cosmetic brand product on a Facebook page, and it will be used to generate the observable pattern and visualizations.

The second source of the data will be used to confirm the correction of the model created by the previous data set visualization. Based on this needs, I plan to either web clip the information on the Facebook or use the open api.

The potential third source of data can also be introduced, and may be a slight different social media platform such as YouTube or Twitter. The data will be treated in the similar manner using text mining or api.

## Approach
The first data set can be stored in a data frame by using built-in read csv function. For this data set, I plan to generate descriptive statistics for the exploratory data analysis. For example, I will generate bar charts to compare the difference between paid advertisements page and free product page. Also, multi-correlation will be checked between data attributes. After a series of procedures, I will use the regression method to create a generalized model. During this part of visualization, I plan to use ggplot package, a plotting tool which is not covered in the class, to make the visualizations. 

After analyzing the pattern of the initial data set, there will be a check to determine whether or not it is a general pattern of the social media advertisement. Specifically, I plan to observe how the Like button impact on the interaction between advertising and buying trend. The other data that can be directly derived from the web using API or texting processing through Python. To collect text messages, NLTK package will collaborate with with the SpaCy package, another common tool of  for natural language processing. To employ this new SpaCy package is also one of the goals for this project.

During the validation process of the second or third data source,  if the 80% more of new testing product data falls within the prediction line, the model derived from the first data set is considered to be valid. 



## Reference
1 link: https://sproutsocial.com/insights/social-media-statistics/

2 link: https://www.lyfemarketing.com/blog/social-media-marketing-statistics/


