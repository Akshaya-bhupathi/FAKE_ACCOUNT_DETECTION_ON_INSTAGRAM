# FAKE_ACCOUNT_DETECTION_ON_INSTAGRAM
Designed and developed a machine learning model to detect fake accounts on Instagram with high accuracy, enhancing platform security and user experience. Collected and preprocessed data from Instagram using web scrapping tools. Performed EDA to identify key patterns and features indicative of fake accounts by using ML Algorithms

# Abstract
In the present generation, online social networks (OSNs) have become increasingly popular, people’s social lives have become more associated with these sites. They use OSNs to keep in touch with each other’s, share news, organize events, and even run their own e-business. The rapid growth of OSNs and the massive amount of personal data of its subscribers have attracted attackers, and imposters to steal personal data, share false news, and spread malicious activities. On the other hand, researchers have started to investigate some efficient techniques to detect abnormal activities and fake accounts relying on accounts features, and classification algorithms. However, some of the account’s exploited features have negative contribution in the final results or have no impact, also using standalone classification algorithms does not always reach satisfied results. In this project, a new algorithm, ADB-CB, is proposed to provide efficient detection for fake Instagram accounts, feature selection and dimension reduction and other techniques were applied. Machine learning classification algorithms were used to decide the target accounts identity real or fake, those algorithms are AdaBoost and CatBoost, and Extra Tree Classifier to get better accuracy.

# OBJECTIVE OF THE STUDY 
The primary objective of this study is to enhance the detection accuracy of fake Instagram accounts by leveraging advanced machine learning techniques, including AdaBoost, Cat Boost, and Extra Tree Classifier algorithms. Through the integration of feature selection and dimension reduction methods, our aim is to develop a robust algorithm, ADB-CB, capable of efficiently distinguishing between genuine and inauthentic profiles, thereby improving the overall integrity of the platform.

# SCOPE OF THE STUDY 
The scope of this study encompasses the development and evaluation of the ADB-CB algorithm for detecting fake Instagram accounts. It includes the exploration of various feature selection and dimension reduction techniques to optimize classification accuracy. The study focuses specifically on the application of machine learning algorithms, namely AdaBoost, Cat Boost, and Extra Tree Classifier, within the context of Instagram account authentication, aiming to provide insights into effective detection strategies.

# PROBLEM STATEMENT
The proliferation of fake profiles on Instagram poses a significant challenge, leading to privacy breaches, misinformation dissemination, and other malicious activities. Existing detection methods often exhibit limitations, such as ineffective feature selection and reliance on standalone classifiers. Addressing these issues, this study aims to develop a robust algorithmic approach, ADB-CB, to accurately identify and mitigate the presence of fake accounts on Instagram.

# LITERATURE SURVEY
This literature survey aims to provide a concise overview of existing research and methodologies related to the detection of fake accounts on Instagram. By examining recent studies and advancements in this domain, we aim to identify key approaches, challenges, and trends that inform the development of effective detection techniques.
The survey begins by outlining the motivations behind fake account creation on Instagram, including the dissemination of spam, phishing attempts, misinformation campaigns, and social engineering tactics. Understanding these motivations is essential for designing detection systems capable of identifying various types of fake accounts and their associated behaviors.
Next, we delve into the methodologies and techniques employed for fake account detection, which encompass a wide range of approaches spanning from rule-based heuristics to machine learning algorithms. These methods leverage various features such as user profile information, posting behavior, network structure, and content analysis to differentiate between genuine and fake accounts.
Furthermore, we explore the challenges and limitations inherent in fake account detection, including the adaptability of malicious actors, the emergence of sophisticated evasion techniques, and the ethical considerations surrounding user privacy and data usage.
Throughout the survey, we highlight notable studies, frameworks, and tools developed by researchers and practitioners to combat the proliferation of fake accounts on Instagram. By synthesizing this body of knowledge, we aim to provide insights that can inform the design of more robust and resilient detection systems, ultimately contributing to a safer and more trustworthy online environment for users.
1.	In the 2018 journal article titled "The Political Economy of Facebook Advertising: Election Spending, Regulation, and Targeting," Katharine Dommett and Sam Power delve into the realm of Facebook advertising during elections. Through an analysis of existing data from the UK Electoral Commission, the authors aim to shed light on various facets of Facebook advertising, including expenditure, regulatory frameworks, and targeting strategies employed during electoral campaigns. This research provides valuable insights into the evolving landscape of political advertising on digital platforms like Facebook, highlighting the complexities and implications for electoral processes and democratic governance.
2.	In John R. Douceur's 2002 journal article titled "The Sybil Attack," the author delves into the vulnerability posed by Sybil attacks in decentralized systems. The study highlights that without a logically centralized authority, Sybil attacks remain a persistent threat, barring extreme and often unrealistic assumptions of resource parity and coordination among entities. These attacks involve adversaries creating multiple fake identities to gain disproportionate influence or disrupt the functioning of the system. Douceur's analysis underscores the challenges inherent in mitigating Sybil attacks and emphasizes the importance of robust security measures in decentralized environments.
3.	In the 2016 journal article titled "A Survey of Data Mining and Social Network Analysis Based Anomaly Detection Techniques," R. Kaur and S. Singh provide a comprehensive overview of various data mining approaches employed for anomaly detection. The paper particularly focuses on techniques rooted in social network analysis, categorizing them into behavior-based, structure-based, and spectral-based methods. By reviewing a multitude of methodologies, the authors contribute to the understanding of anomaly detection in complex network environments, offering insights into the diverse strategies utilized for identifying irregular patterns and potential threats within social networks.
4.	In the 2017 journal article titled "Factors Explaining User Loyalty in a Social Media-Based Brand Community," L. M. Potgieter and R. Naidoo investigate the mediating role of online brand communities (OBBC) facilitated by social media platforms (SMP) in shaping consumers' purchasing attitudes within virtual spaces. The study aims to understand how engagement within social media-based brand communities’ influences consumer loyalty and purchasing behavior. By examining this interplay, the authors contribute valuable insights into the dynamics of online brand communities and their impact on consumer-brand relationships in the digital age.
5.	In the 2011 conference paper titled "The Socialbot Network: When Bots Socialize for Fame and Money," Y. Boshmaf, I. Muslukhov, K. Beznosov, and M. Ripeanu investigate the vulnerability of Online Social Networks (OSNs) to large-scale infiltration by social bots. These bots are computer programs designed to control OSN accounts and mimic the behaviors of real users. Through their evaluation, the authors assess the extent to which OSNs are susceptible to manipulation by social bots, shedding light on the potential risks posed by automated accounts in influencing online interactions and perceptions.
6.	In the 2011 conference paper titled "Truthy: Mapping the Spread of Astroturf in Microblog Streams," J. Ratkiewicz, M. Conover, M. Meiss, B. Gonçalves, S. Patil, A. Flammini, and F. Menczer explore the phenomenon of astroturfing in microblog streams. Astroturfing refers to the practice of creating artificial grassroots movements or manipulating public opinion through coordinated campaigns. Through their investigation, the authors provide insights into the spread and impact of astroturfing on online platforms, highlighting its potential to distort reality and manipulate public discourse.


# PROPOSED SYSTEM
We are proposing a new application that can be really helpful because it can overcome the limitations of current methods. The goal of our study is to create a method that can quickly and accurately tell if an account is fake or not. We did this by using a strong algorithm in a Python environment. 
1. Data Collection: Gather diverse data from various sources, including user activity (like posting frequency, time of engagement, content types), account metadata (creation date, profile completeness), and network structure (follower-following relationships). 
2. Feature Engineering: Extract meaningful features from the collected data. These might include account age, posting habits, frequency of interactions, ratio of followers to following, engagement rates, etc.
3. Model Training: Employ supervised machine learning techniques such as logistic regression, decision trees, random forests, or neural networks. Train the model using labeled datasets, where accounts are categorized as fake or genuine based on known criteria
4. Model Evaluation: Assess the model's performance using metrics like accuracy, precision, recall, and F1-score. Tweak the model parameters, feature selection, or try different algorithms to enhance performance. 
5. Deployment: Integrate the trained model into Instagram's backend systems. As new accounts are created or flagged for suspicion, the system uses the ML model to predict the likelihood of an account being fake. 
6. Feedback Loop: Continuously update the model using feedback from identified fake accounts and newly emerging patterns. This iterative process improves the model's accuracy and adaptability


# ALGORITHMS IMPLEMENTATION
1.	AdaBoost Classifier Implementation:
Step 1: Gather and preprocess the data. This involves cleaning the data, removing missing values, and normalizing the data if required.
Step 2: Choose a weak model. This can be any simple model that performs slightly better than random guessing.
Step 3: Train the weak model on the dataset.
Step 4: Adjust the weights of the data points based on the misclassification rate of the weak model.
Step 5: Train another weak model on the adjusted dataset.
Step 6: Repeat the process for the desired number of iterations.
Step 7: Combine the weak models to make the final strong model. 

2.	CatBoost Classifier Implementation:
Step 1: Importing the required libraries 
Step 2: Loading and Cleaning the Data 
Step 3: Split data into train and test data.
Step 4: Train your CatBoost model on the imported training data.
Step 5: Evaluate the model using the appropriate metrics for your task.
Step 6: Interpret the metric values to assess the model’s performance.

3.	Extra Tree Classifier Implementation:
Step 1: Importing the required Libraries
Step 2: Loading and Cleaning the Data
Step 3: Building the Extra Trees Forest and computing the individual feature importance
    n_estimators: It decides the number of trees in the forest.
    criterion: The function to measure the quality of a split. Supported criteria are “gini” for the Gini impurity and “entropy” for the information gain.
  	max_features: It decides the number of features to consider when looking for the best split.
Step 4: Visualizing and Comparing the results

# BIBLIOGRAPHY
[1] (2018) Political advertising spending on Facebook between 2014 and 2018. Internet draft. [Online]. Available: https://www.statista.com/statistics/891327/political-advertisingspending-face book-by-sponsor-category/
[2] J. R. Douceur, “The Sybil attack,” in International workshop on peer-to-peer systems. Springer, 2002, pp. 251–260. 
[3] (2012) Cbc.facebook shares drop on news of fake accounts. Internet draft. [Online]. Available: http://www.cbc.ca/news/technology/facebook-shares-drop-on news-of-fake-accounts-1.1177067 
[4] R. Kaur and S. Singh, “A survey of data mining and social network analysis based anomaly detection techniques,” Egyptian informatics journal, vol. 17, no. 2, pp. 199–216, 2016. 
[5] L. M. Potgieter and R. Naidoo, “Factors explaining user loyalty in a social media-based brand community,” South African Journal of Information Management, vol. 19, no. 1, pp. 1–9, 2017. 
[6] (2018) Quarterly earning reports. Internet draft. [Online]. Available: https://investor.fb.com/home/default.aspx 
[7] (2018) Statista.twitter: number of monthly active users 2010-2018. Internet draft. [Online]. Available: https://www.statista.com/statistics/282087/number-of-monthly active-twitter-users/ 
[8] Y. Boshmaf, M. Ripeanu, K. Beznosov, and E. Santos-Neto, “Thwarting fake accounts by predicting their victims,” in Proceedings of the 8th ACM Workshop on Artificial Intelligence and Security. ACM, 2015, pp. 81–89. 
[9] (2018) Facebook publishes enforcement numbers for the first time. Internet draft. [Online]. Available: https://newsroom.fb.com/news/2018/05/enforcement-numbers/
 [10] (2013) Banque populaire dis-moi combien damis tu as sur facebook, je te dirai si ta banque va taccorder un prłt. Internet draft. [Online]. Available: http://bigbrowser.blog.lemonde.fr/2013/09/19/popularitedis-moi-combien-damis-tu-as-sur-facebook-je-te-dirai-si-ta-banqueva-taccorder-un-pret/ 

[11] S.-T. Sun, Y. Boshmaf, K. Hawkey, and K. Beznosov, “A billion keys, but few locks: the crisis of web single sign-on,” in Proceedings of the 2010 New Security Paradigms Workshop. ACM, 2010, pp. 61–72. 
[12] S. Fong, Y. Zhuang, and J. He, “Not every friend on a social network can be trusted: Classifying imposters using decision trees,” in Future Generation Communication Technology (FGCT), 2012 International Conference on. IEEE, 2012, pp. 58–63. 
[13] K. Thomas, C. Grier, D. Song, and V. Paxson, “Suspended accounts in retrospect: an analysis of twitter spam,” in Proceedings of the 2011 ACM SIGCOMM conference on Internet measurement conference. ACM, 2011, pp. 243–258. 
[14] Y. Boshmaf, I. Muslukhov, K. Beznosov, and M. Ripeanu, “The socialbot network: when bots socialize for fame and money,” in Proceedings of the 27th annual computer security applications conference. ACM, 2011, pp. 93–102. 
[15] J. Ratkiewicz, M. Conover, M. Meiss, B. Gonc¸alves, S. Patil, A. Flammini, and F. Menczer, “Truthy: mapping the spread of astroturf in microblog streams,” in Proceedings of the 20th international conference companiossn on World wide web. ACM, 2011, pp. 249–252.
