# Financial_Inclusion_in_Africa

About:

We are asked to predict the likelihood of the person having a bank account or not (Yes = 1, No = 0), for each unique id in the test dataset . We will train our model on 70% of the data and test our model on the final 30% of the data, across four East African countries - Kenya, Rwanda, Tanzania, and Uganda.

The main dataset contains demographic information and what financial services are used by approximately 33,600 individuals across East Africa. This data was extracted from various Finscope surveys ranging from 2016 to 2018, and more information about these surveys can be found here:

FinAccess Kenya 2018
Finscope Rwanda 2016
Finscope Tanzania 2017
Finscope Uganda 2018


Dataset Descrption:

| Variable               | Definitions                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| country                | Country interviewee is in.                                                                                                                                                                                                                     |
| year                   | Year survey was done in.                                                                                                                                                                                                                       |
| uniqueid               | Unique identifier for each interviewee                                                                                                                                                                                                         |
| location_type          | Type of location: Rural, Urban                                                                                                                                                                                                                 |
| cellphone_access       | If interviewee has access to a cellphone: Yes, No                                                                                                                                                                                              |
| household_size         | Number of people living in one house                                                                                                                                                                                                           |
| age_of_respondent      | The age of the interviewee                                                                                                                                                                                                                     |
| gender_of_respondent   | Gender of interviewee: Male, Female                                                                                                                                                                                                            |
| relationship_with_head | The interviewee's relationship with the head of the house: Head of Household, Spouse, Child, Parent, Other relative, Other non-relatives, Dont know                                                                                            |
| marital_status         | The martial status of the interviewee: Married/Living together, Divorced/Seperated, Widowed, Single/Never Married, Dont know                                                                                                                   |
| education_level        | Highest level of education: No formal education, Primary education, Secondary education, Vocational/Specialised training, Tertiary education, Other/Dont know/RTA                                                                              |
| job_type               | Type of job interviewee has: Farming and Fishing, Self employed, Formally employed Government, Formally employed Private, Informally employed, Remittance Dependent, Government Dependent, Other Income, No Income, Dont Know/Refuse to answer |
