# data-cleansing / data pre-processing

dataset : https://storage.googleapis.com/dqlab-dataset/dqlab_telco.csv

dataset terdiri dari :

-UpdatedAt Periode of Data taken
-customerID Customer ID
-gender Whether the customer is a male or a female (Male, Female)
-SeniorCitizen Whether the customer is a senior citizen or not (1, 0)
-Partner Whether the customer has a partner or not (Yes, No)
-Dependents Whether the customer has dependents or not (Yes, No)
-tenure Number of months the customer has stayed with the company
-PhoneService Whether the customer has a phone service or not (Yes, No)
-MultipleLines Whether the customer has multiple lines or not (Yes, No, No phone service)
-InternetService Customer’s internet service provider (DSL, Fiber optic, No)
-OnlineSecurity Whether the customer has online security or not (Yes, No, No internet service)
-OnlineBackup Whether the customer has online backup or not (Yes, No, No internet service)
-DeviceProtection Whether the customer has device protection or not (Yes, No, No internet service)
-TechSupport Whether the customer has tech support or not (Yes, No, No internet service)
-StreamingTV Whether the customer has streaming TV or not (Yes, No, No internet service)
-StreamingMovies Whether the customer has streaming movies or not (Yes, No, No internet service)
-Contract The contract term of the customer (Month-to-month, One year, Two year)
-PaperlessBilling Whether the customer has paperless billing or not (Yes, No)
-PaymentMethod The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
-MonthlyCharges The amount charged to the customer monthly
-TotalCharges The total amount charged to the customer
-Churn Whether the customer churned or not (Yes or No)

DENGAN OUTPUT KESIMPULAN :

A. Gender (Female, Male, Wanita, Laki-Laki), yang bisa di standardkan nilainya menjadi (Female, Male) karena mempunyai makna yang sama.
B. Dependents (Yes, No, Iya), yang bisa di standardkan nilainya menjadi (Yes, No) karena mempunyai makna yang sama.
C. Churn (Yes, No, Churn), yang bisa di standardkan nilainya menjadi (Yes, No) karena mempunyai makna yang sama.
