## <h1><p align="center">Deployment of a Flask app(Simple login page) with AWS services</p></h1>
<p align="center">
  <img src="https://github.com/AWS-Re-Start-RDC-KINSHASA-1/LoadBalance-Config-MenaVeko/assets/90093320/9fe4f07b-0cca-4f29-9c2a-2dbe655ef187" />

</p>
<h2>Purpose of this deployment</h2>

We want to use this simple app to show how to deploy an app in the cloud using the AWS LoadBalance and the Autoscale services. And the below diagram show the result of the configuration.

<img src="https://github.com/AWS-Re-Start-RDC-KINSHASA-1/LoadBalance-Config-MenaVeko/assets/90093320/fdc216bc-c3a0-4955-887e-498578b36289" />

<h2>Start the configuration</h2>
Feel free to just copie the code that I provided in the LoginPage folder you will find the Flask app and its templates, the Config-userdata folder contain the userdata script that you will put in the server configuration and his template.
<h3>1-The Flask App</h3>
Create a simple flask app that will help you to understand the configuration then you will update to your desire appliaction.
Don't forget to put this line :

```
if __name__ == '__main__':
    app.run(host='0.0.0.0', debug=True, port=5000)
```

If you notice in the below screenshot my Flask login page it's running in the port 3000, its the default configuration for the test. We will use the port 5000 for this lab. This is the result that you will have if you take my code.
<img src="https://github.com/AWS-Re-Start-RDC-KINSHASA-1/LoadBalance-Config-MenaVeko/assets/90093320/44a80bc9-b7ae-45bc-b2e7-4b9376291a48" />


<h3>2-Star the configuration on AWS Console</h3>
Connect into your AWS console, and write in the search bar EC2. This will open the console where we launch the EC2 instance.
Create your server 

##The readme is not done yet
