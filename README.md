# Bank-client-data-
we have build this model on Bank client data set to check  that client has Subscribed the term Deposite (Yes / no ) , with Classifier models like Random_forest, Naive_bayes, KNN & Logistic_Regression
# Bank client data:
age (numeric)
job: type of job(categorical:"admin.","bluecollar","entrepreneur","housemaid","management","retired","selfemploy ed","services","student","technician","unemployed","unknown")
marital: marital status (categorical: "divorced","married","single","unknown"; note: "divorced" means divorced or widowed)
education: education of individual (categorical: "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","u nknown")
default: has credit in default? (categorical: "no","yes","unknown")
housing: has housing loan? (categorical: "no","yes","unknown")
loan: has personal loan? (categorical: "no","yes","unknown") Related with the last contact of the current campaign:
contact: contact communication type (categorical: "cellular","telephone")
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
dayofweek: last contact day of the week (categorical: "mon","tue","wed","thu","fri")
duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y="no"). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model. Other attributes:
campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: "failure","nonexistent","success") Social and economic context attributes
emp.var.rate: employment variation rate - quarterly indicator (numeric)
cons.price.idx: consumer price index - monthly indicator (numeric)
cons.conf.idx: consumer confidence index - monthly indicator (numeric)
concavepoints_se: standard error for number of concave portions of the contour
euribor3m: euribor 3 month rate - daily indicator (numeric) 21) nr.employed: number of employees - quarterly indicator (numeric) Output variable (desired target):
y: has the client subscribed a term deposit? (binary: "yes","no")
# Motivation :
This dataset presents an opportunity to build a predictive model to determine if a client will subscribe to a term deposit, aiding banks in optimizing marketing efforts. It contains a mix of personal, financial, and macroeconomic data, making it ideal for exploring complex relationships and identifying key factors driving client behavior. Predictive modeling will help target high-potential customers, improving campaign efficiency and reducing costs. Additionally, handling both categorical and numerical data enhances skills in preprocessing and feature engineering, making this a practical, real-world project for customer behavior prediction in banking.
# Conclusion
All three models provide good accuracy scores.
Logistic Regression has the highest accuracy, but other performance metrics (like precision, recall, or F1 score) are not as strong.
KNN is a solid choice overall, balancing accuracy and other performance metrics.
Considering class imbalance, Random Forest is the best option, offering robust performance and handling the imbalance well with a good accuracy score.






