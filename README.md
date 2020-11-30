# Home-Credit-Default-Risk

This project discusses the business use case and need for a machine learning algorithm to assess the Home credit default risk of a borrower.

# Data Source

The data for this project was taken from Kaggle competition titled "Home Credit Default Risk". The link to the data is as below:
https://www.kaggle.com/c/home-credit-default-risk/overview

# Need for a Solution & Our Approach:

For a very long time, banks and other investment institutions have hired many analysts in order to detect credit risk. With the big data revolution and the advent of data science, a more quantitative approach can be taken to the issue. That is what inspired our team to tackle this issue. The issue of Home credit default risk has a historic and well-documented business case with implications involving the general public, lenders, borrowers, employees as well as government institutions who may be responsible for backing deposits that are loaned out.

# Lucidchart of the data schema

![Lucidchart](https://user-images.githubusercontent.com/26451635/100534961-98bfab00-31e2-11eb-9518-16899d0ed633.png)

# Feature Engineering Snippet

![Feature_engg](https://user-images.githubusercontent.com/26451635/100534971-bee54b00-31e2-11eb-8919-fccdeeddca90.png)

# Model Selection Snippet

![Model_selection](https://user-images.githubusercontent.com/26451635/100534980-d7edfc00-31e2-11eb-8ad5-97ecd42a859f.png)

# Key Insights and Findings

Our analysis of this data has led us to several findings. The dataset we used was highly biased. 92% of the data was of non-defaulter’s applications. Defaulted transactions are rare given a large pool of transactions. Something interesting that we found in the data was that the source of the transaction had a lot of predictive power to determine whether or not the borrower was likely to default or not. This information can be used to predict defaults and therefore reduce the amount of defaults in an organization. Reducing the amount of defaults in an organization can benefit the employees, customers, constituents and every other stakeholder. Our results would be interesting to company executives who are interested in reducing the amount of defaults within their organization and to those who work within the government. It is essential that the government be able to maintain financial solvency. Preventing defaults is an important step in doing that. That holds especially true for the housing and financial services industry.

# Conclusion

In conclusion, default on home credit loans is a devastating problem that can wreak havoc on an organization’s customers, employees, profits, shareholders and stakeholders, as well as the general public. Our team has created an advanced analytics solution to assist organizations in detecting Home credit default risk so that they can respond appropriately to it. This solution was created in Python with the goal of using machine learning to detect potential defaulters. This can result in organizations having more engaged employees, more financially healthy customers and higher profits. This will improve the lives of lenders, borrowers, shareholders and stakeholders

# Next Steps

As a scope for further research I believe in continuous improvement of our model to meet varying business requirements. For instance, the current COVID-19 pandemic may well lead to home owners defaulting on their mortgages. They may be furloughed or simply be unable to reach their workplace for work. This could also lead to a slide in home prices. So, an Ideal Model should account and adapt to such extreme situations in a short span of time. Given the limited data availability at this time, it could teach itself to learn from this sudden change in borrower pattern and make post pandemic predictions in the housing market.

# Libraries used

Python: TensorFlow, scikit-learn, NumPy, pandas, Matplotlib, Seaborn, NLTK

# License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
