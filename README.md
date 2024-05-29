# AWS project, hosting a static website using S3 and route 53
This project was intended to host a static website using AWS service Route 53 and S3, the website would contain a copy of my CV. Benefits of hosting a static website using S3, cost effective, easily maintained.
To start with I purchased a unique domain name in this case it was schell-cloud.com. I purchased this through the AWS console and have rights to this domain name for the next 12 months. 

![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/1eb49a40-12ba-444e-a6cb-f167ca6093f6)
Once the domain was selected and registered, I then created an S3 bucket. I held the bucket in the region closest to my location so in this example it was EU- West 2 (London). By default public access is disabled and hosting a static website is disabled, using the console this had to be enabled.

![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/5ad794ea-d6f8-498f-88b8-988c9a24a68f)
![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/58973668-525d-4047-9454-1de91d4c2c58)
![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/951bc977-0884-4f25-a0fb-8a14b85e50e0)

The next stage in this project is to route traffic to the S3 bucket via the domain name using the S3 endpoint as the target selecting an A Record type. 
![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/409ef364-aa48-40eb-bc18-2df30e8f9715)

Now I had upload and object to the bucket, this needed to be the html code to website I wished to host. To do this, I copied the html code and saved as html.index, this was then uploaded to the S3 bucket. Once uploaded the website was fully functioning and my CV was shared publicly using a custom domain name.

![image](https://github.com/JimSchell/AWS-Projects/assets/165466444/502df3eb-96d6-475d-a757-9cee646b936a)



 



