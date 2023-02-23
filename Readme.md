# My Personal Portfolio
[![Deploy](https://github.com/PaulAnsh/FlexStart/actions/workflows/main.yml/badge.svg)](https://github.com/PaulAnsh/FlexStart/actions/workflows/main.yml) 
[![Website](https://img.shields.io/badge/Website-anshpaul.me-green)](https://anshpaul.me)

## Techstack : 
- HTML & CSS
- Bootstrap 
- AWS S3
- AWS Cloud Front 
- Route 53


### Hosting:

AWS cloud platform is used for hosting the website. The services used are:
- S3- for storing the content(Code) of the website. 
- CloudFront- For caching the content which provides better website performance. 
- Route53- For domain sservices. 
- AWS Certificate Manager- For providng secure certificate to the website. 

#### Architechure Diagram:

![image](https://user-images.githubusercontent.com/74669526/168925005-25d22612-7a23-42c1-93a2-6f9eaba0fa57.png)



#### Template Used:

-[Template URL](https://bootstrapmade.com/flexstart-bootstrap-startup-template/)
-[License](https://bootstrapmade.com/license/)


# Cloud Resume Challenge:

This websitwe is part of my attempt at cloud resume challenge.


## More services used:
- API Gateway: To fetch the current records count. 
- DynamoDB: Created DynamoDB table to store data. 
- Lambda function: Created two functions:
                   1. First functions to fetch the visitor count from Dynamo DB records. 
                   2. Second to update the visitor count in Dynamo DB records. 

Edited website using javascript to show the total view count on the website.

## Website screen shot with views functionality.  
![image](https://user-images.githubusercontent.com/74669526/220795136-b9c21c83-98d4-47a2-a0c4-1b4e2b9b69ff.png)
 


  
  
