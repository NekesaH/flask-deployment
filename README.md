# flask-deployment
Deploy A Simple Flask app with AWS Elastic BeanStalk
Step 0:
"AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS."


Step 1:

    Start with creating a .gitignore file and add __pycache__ and .env environment

Step 2:

Create a requirements.txt file where you save the python packages your application needs with the version. Then, push the application to github. We will use github as the source of the code.

Step 3:
Go to  AWS and Use Elastic BeanStalk and Create a New Application for your deployment.


Step 4:
Connect the deployment to github and follow through the steps to deploy.
![F2](https://user-images.githubusercontent.com/26283613/180016596-7cd977b1-5803-4c00-8f12-f52290d78d87.PNG)




Finally, if you deploy the application currectly, you will get a success message from the logs and when you visit the AWS EBS GUI, you will be able to see the following screen.

The static and templates folder stays the same![deploy](https://user-images.githubusercontent.com/26283613/180016465-0a5c4393-1843-4ee7-b9ac-396a0ecccbbd.PNG)
