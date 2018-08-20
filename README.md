# Opiria Diagrams

Below we present diagrams explaining the structure of the Opiria application and the server API methods used for communicating with the Opiria app. We are happy to provide further explanations and a guided tour through the source code. 
Please contact us at marlene.gagesch@opiria.com (Marlene Gagesch, CTO)

#### This diagram contains the class diagram of Opiria application
![GitHub Logo](https://github.com/opiria-pdata/opiria-diagrams/blob/master/OpiriaClasses.png)

#### This diagram contains the services of Opiria application and interaction between them
![GitHub Logo](https://github.com/opiria-pdata/opiria-diagrams/blob/master/OpiriaServices.png)

#### This diagram contains the packages of Opiria application and interaction between them
![GitHub Logo](https://github.com/opiria-pdata/opiria-diagrams/blob/master/OpiriaPackages.png)

#### Mobile api spec

 ApiAccount:

        - Register POST - Register a new  mobile user

        - CheckRegister POST - check if the email is used

        - Wizard POST - add the "Gender", "Birthdate", "Country" to the connected mobile user

        -DeviceToken POST - update the device token used for notification for the connected mobile user

        -WizardData GET - get the "Gender", "Birthdate", "Country" to the connected mobile user

        -Login POST - login a mobile user with email and password

        -Logout POST - logout the current user

        - ForgotPassword POST - forgot password functionality


    ApiSurvey:

        - GetSurveys GET - get the current valid surveys for an mobile account

        - GetSurvey GET - get a valid survey by id

        - RemoveSurvey GET - remove a survey from mobile user list

        - SaveResults POST - save the survey results

        -SaveComments POST - save the comments for a survey
        
![GitHub Logo](https://github.com/opiria-pdata/opiria-diagrams/blob/master/ApiSpec.png)        
