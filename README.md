# Health Insurance Cross Sell

<p align="center">

<img src="img/health_insurance.jpeg" width="600" height="300"/>

</p>

<p align="center">

<em> Photo by <a href="https://unsplash.com/pt-br/@vladdeep?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Vlad Deep</a> on <a href="https://unsplash.com/pt-br/fotografias/mCqi3MljC4E?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></em>

</p>

The scripts for this project can be found on the links below:

-   [Part 01](https://rpubs.com/edneide_ramalho/health_insurance_cross_sell_part01): In this part we collect the data, clean the data, create and test hypothesis, and finish with selecting the features that will be used to train the models.
-   [Part 02](https://rpubs.com/edneide_ramalho/project_health_insurance_part02): In this part we train the first models such as Logistic Regression, Decision Tree, Random Forest, KNN, and XGBoost.

The data for this project can be found on [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)

Below, you can find the **dataset dictionary**.

| **Variable**           | **Meaning**                                                        |
|--------------------|----------------------------------------------------|
| `id`                   | Unique ID for the customer                                         |
| `gender`               | Gender of the customer                                             |
| `age`                  | Age of the customer                                                |
| `driving_license`      | Customer has DL (yes/no)                                           |
| `region_code`          | Unique code for the region of the customer                         |
| `previously_insured`   | Customer already has Vehicle Insurance (yes/no)                    |
| `vehicle_age`          | Age of the Vehicle                                                 |
| `vehicle_damage`       | Customer got his/her vehicle damaged in the past (yes/no)          |
| `health_annual_paid`   | The amount customer needs to pay as premium in the year            |
| `policy_sales_channel` | Anonymized Code for the channel of outreaching to the customer ie. |
| `days_associated`      | Number of Days, Customer has been associated with the company      |
| `response`             | Customer is interested in car insurance (yes/no)                   |

# Business question

TODO

# Business assumptions

TODO

# Solution Planning

1.  Collect the data on Kaggle
2.  Change the data type for appropriate one for some features
3.  Clean data
4.  Rename features
5.  Test the hypothesis
