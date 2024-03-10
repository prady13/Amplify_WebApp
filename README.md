# Amplify_WebApp

We will deploy a WebApp to calculate a power of a number using AWS Amplify and will also use services like AWS Lambda, IAM, API Gateway and DynamoDB.

Deployed basic HTML code which we will update in the later steps on Amplify.
<img width="1440" alt="Screenshot 2024-03-10 at 3 16 36 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/5d94024c-99bb-4cda-9ac8-0a587ccf7bc6">

Lambda function to calculate the power of the number.
<img width="1440" alt="Screenshot 2024-03-10 at 3 22 35 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/6f9a7d75-e88d-4c56-8ff1-7d29059612c9">

Testing the function to check the right result is being calculated.
<img width="1440" alt="Screenshot 2024-03-10 at 3 33 57 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/06b909c2-d128-44b6-afe6-08c19fe77f51">

Now we need a public endpoint to trigger the Lambda function to run. So we will use API Gateway.
<img width="1440" alt="Screenshot 2024-03-10 at 3 38 57 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/eec8e587-91f6-4313-8ce4-20c50f9eec41">

We also need to enable CORS (Cross Origin Resource Sharing), it allows a web app running in one origin/domain to be able to access resources on different origin/domain. Since our app is running on one domain on Amplify and Lambda func on another we need to work accross those origins.
<img width="1440" alt="Screenshot 2024-03-10 at 3 47 57 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/169df60d-6459-4a4d-a0cc-b19309b51494">

We create a table to store and return the values to the users.
<img width="1416" alt="Screenshot 2024-03-10 at 3 59 25 PM" src="https://github.com/prady13/Amplify_WebApp/assets/62207613/705b2761-7b36-441a-8994-946ca6c19996">



