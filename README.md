<body>
    <h1> Customer Retention Insights for a Telecom Company </h1>
    <h3> Analyzed by Kimberly Humphrey </h3>
    <h4> Data Set Link <a href="https://www.kaggle.com/becksddf/churn-in-telecoms-dataset">https://www.kaggle.com/becksddf/churn-in-telecoms-dataset</a></h4>
    
    
    <h2> Purpose </h2>
    
    <p> The main focus is to use the dataset provided to assist the company in increasing their customer retention rates. This will be achieved by analyzing and modeling the data, targeting customer 'churn' rate, to potentially predict the current likelihood of a customer terminating their contract. This will allow the company a chance to intervene before the loss of a client. As well as to gain insights into specific features that have higher churn rates, so that the company may implement policy changes to lower the future likelihood of loss. </p>
    
    <h2> Insights </h2>
    
    <h3> Current overall churn of 14% </h3>
    
    <h3> Do the Total Number of Service Calls Affect Customer Retention? And, is there an Indicator that We Should Initiate an Intervention to Help Retain that Customer?</h3>
    <br/>
    <img src="./ServiceCalls.png" alt="Chart representing the hurn of Customers per Service Call">
    <br/>
    
    <p> The total number of service calls do affect churn rate. It is clear that after 4 calls the churn rate jumps up to almost half of the customers and continues to increase</p>
    
    <h3>Does having an International Plan Affect Retention?</h3>
    <br/>
    <img src="int_plan.png" alt="Chart representing the Retention of Customers with an International Plan">
    <br/>

    <p>Almost half of customers who sign up for an international plan eventually churn.</p>
    
    <h3>Which customers are most valuable? And what is their retention rate?</h3>
    <br/>
    <img src="charges.png" alt="Chart representing charges per day per customer">
    <br/>
    <p>The median spend per day is $0.56, so the customers that spend $1 or more are essentially worth 2 or more customers. Their current churn rate is 18% which is higher than the overall rate of 14%. Focusing on this group will impose more signifigance on the bottom line.</p>
    
    <h2> Models Tested </h2>
    <h2> Focusing on Recall for this project as it is more important to catch all customers likely to churn even if it means we are catching ones that do not</h2>
    
    <h3> KNN </h3>
    <p> KNN provided a recall of 87% and an overall accuracy of 72%.
    <h3> Decision Tree </h3>
    <p> KNN provided a recall of 83% and an overall accuracy of 80%.
    <h3> Binomial Logistic Resgression </h3>
        <p> Provided an accuracy of 70% </p>
    <h2> Final Model </h2>
    <p> The KNN was the best model. The high recall along with decent accuracy gives us more of what we are looking for. In addition, the customers that are incorrectly labeled as churn are identified to be close enough to others in certain qualities, that it would be prudent to intervene with them as well as they could be churn in the future.</p>
    <h2> Future Work </h2>
    <h3> Additional Data </h3>
    <p> # of accounts, specific locations, age, sex, race, income, dropped calls, job, education, calls answered / unanswered, married/single, education, credit score, employer or personal account </p>
    <h3> Analyzing the data on why customers stay rather than churn, to help assist with churn </h3>
    
</body>