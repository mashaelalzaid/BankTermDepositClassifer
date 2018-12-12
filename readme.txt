   The data is related with direct marketing campaigns of a Portuguese banking institution. 
   The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, 
   in order to access if the product (bank term deposit) would be (or not) subscribed. 

   The original bank-full.csv dataset available on the UC Irvine website has been preprocessed to remove certain attributes as well as the missing values. The dataset to be used for assignment purposes is to be called 'bankdata-cleaned.csv'

Attribute information:

   Input variables:
   # bank client data:
   1 - age (numeric)
   2 - job : type of job (categorical: "admin.","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4 - education (categorical: "unknown","secondary","primary","tertiary")
   5 - default: has credit in default? (binary: "yes","no")
   6 - balance: average yearly balance, in euros (numeric) 
   7 - housing: has housing loan? (binary: "yes","no")
   8 - loan: has personal loan? (binary: "yes","no")
   # related with the last contact of the current campaign:
   9 - contact: contact communication type (categorical:"telephone","cellular") 


  Output variable (desired target):
  10 - y - has the client subscribed a term deposit? (binary: "yes","no")



Getting Started Tip 1:

Loading the dataset into R:

		bankdata <- read.csv("/file location/bankdata-cleaned.csv", header= T)
