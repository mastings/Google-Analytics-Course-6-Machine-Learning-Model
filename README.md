# Google-Analytics-Course-6-Machine-Learning-Model
Google Advanced Data Analytics Professional Certificate course 6 machine learning model project

**Background on the TikTok scenario**

At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company, and grow your career.

TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

**Data Understanding**

The dataset contains 19382 entries of data on videos from the platform. The data contains 12 variables, most importantly whether a video is a claim or an opinion. The other variables are other features of the video such as comment count or like count. 

**Modeling and Evaluation**

Two models were evaluated - one random forest and one XGBoost. Both models performed incredibly well with 0.99+ recall scores and high precision. Ultimately the random forest model was selected as the final model due to its slightly higher scores. As shown in the image below, the final model only misclassified 19 samples, for a total of 0.5% misclassified.

![course 6 project cm](https://github.com/mastings/Google-Analytics-Course-6-Machine-Learning-Model/assets/22780966/400c8fba-b8d0-47a2-9d95-5a6f947ded51)

**Conclusion**

It was found that the model is fairly accurate at predicting whether a video is a claim or an opinion. We also saw in this analysis that the most important predictors of claim status were related to engagement. Video view, like, share, and download count all had predictive signals. 
