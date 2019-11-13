---
title: (BONUS) Deploy the Model
date: 1970-01-09
---
Now that your model is built, lets use Watson Machine Learning to make the model usable in an application. 

##  Setup Watson Machine Learning
Navigate to [cloud.ibm.com](https://cloud.ibm.com/) and click **Create Resource**
![](assets/create-resource-cloud.png)
In the search bar, search for `watson machine learning` and click the icon
![](assets/select-wml.png)
Select the **Lite** plan and click **Create**
![](assets/create-wml.png)
Once the service has been created, click **Service Credentials**
![](assets/wml-service-cred.png)
Click the button for **New Credential**
![](assets/wml-new-cred.png)
Click **Add**
![](assets/wml-add-cred.png)
Click **View credentials** and copy the pieces needed in the notbook
![](assets/wml-view-cred.png)

Once you have added the credentials, you can run the whole notebook again, this time deploying and testing the model. 

In the project, you will now see a deployed model listed as an asset. You did it!