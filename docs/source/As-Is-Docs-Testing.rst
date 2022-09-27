As-Is-Docs-Testing
=====

.. _react-spa:

React SPA S3 Deployment 

Problem Statement 

 

Deploy React Single Page application(SPA) in Amazon S3 and compare the performance of the original application with application deployed in S3 and CloudFront. 

 

    Pre-Requisites 

 

    AWS Account with Free Tier Access 

    Chrome Browser for using lighthouse Extension 

    Demo Website to migrate (https://vercel.com/gorleabhilash/react-spa-demo) 

    Basic Knowledge of AWS 

    IntelliJ or any Framework which support React 

    Install Node Js, NPM & React js 

 

    Source Website Tech Stack 

 

    React Js 

 

    Migration Steps 

 

    Download the application from GitHub . 

    UnZip the downloaded file and open it with React Framework. 

    Check the application by running it using the below command 

 

                                                        npm run start 

    Build the application by using the below command 

 

                                                        npm run build   

     

    After running build command you will find build folder created in your code base which you have downloaded and running. 

 

    Please find the screenshot below 

 

Steps to deploy the application in S3. 

 

Please find below link for the migration steps. 

 

https://dev.to/oyetoket/how-to-deploy-your-frontend-application-on-aws-s3-31m9 

 

 

Please find the below screenshots to Deploy the application in S3 

 

    Migration Outcome. 

 

Performance of the application is checked with the help of light house extension in Chrome Browser. 

 

                         Performance: 

 

                          Deployed in S3 

 

 

 

 

 

Original Application (Deployed in vercel) 
 

 

 

 

 

 

           Deployed in CloudFront 

 

 

 

 

    Challenges 

 

    Please Add the S3 Bucket Policy if you are unable access the static website URL 

    References 

 

 

    https://vercel.com/gorleabhilash/react-spa-demo( Original Application) 

 

    https://www.geeksforgeeks.org/how-to-install-reactjs-on-macos/ 

 

 

    https://github.com/taranjeet/react-spa-demo 

 

 

    Chrome provides extension to gauge page load performance tool called lighthouse 

    https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en 

 

    https://dev.to/oyetoket/how-to-deploy-your-frontend-application-on-aws-s3-31m9 

 

 
