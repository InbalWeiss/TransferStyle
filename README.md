# Transfer Style with Keras

## Getting Started
In this workshop we will be using IBM Watson Studio to run a Jupyter Notebook, which are an open-source web application for creating and sharing documents containing live code. To follow through in this workshop you will need the following
* IBM Cloud Account 
* Watson Studio instance
* Cloud Object Storage instance
* Watson Machine Learning instance

The following steps will show you how to create a IBM Cloud account and to set up the needed resources. If you have already done this, you can skip ahead to `Create a Watson Studio Project`.
### IBM Cloud
* [Sign up](https://cloud.ibm.com/registration) for an IBM Cloud account.
* When you are logged in, click `Create Resource` at the top right corner of the starting page.
* Search for Watson Studio and click on the tile. Choose the Lite plan and click `Create`.
* Go back to the `Catalog` and repeat the previous step but now search for Cloud Object Storage respectively Watson Machine Learning.
  
The setup is now complete.

### Create a Watson Studio Project
In IBM Cloud, click the hamburger menu and the `Resource List`. Under Services, click on Watson Studio and then `Get Started`.
#### 1. Create a new project
* In Watson Studio, click on `Create project` or `New project`.
* Select the created Object Storage if this is not selected automatically. **Do not forget to click refresh.** 
* Click `Create`.
#### 2. Load the notebook
* Add a new notebook. Click `Add to project` and then `Notebook`.
* Choose new notebook from URL. Give the notebook a name and copy the URL (https://github.com)
  
#### 3. Setup service credentials
##### 3.1. Cloud Object Storage
* Go back to the `Resource List` in IBM Cloud.
* Click on `Cloud Object Storage` under Storage. 
* Under the `Service credentials` tab, click `New credential`. Make sure you tick the `Include HMAC Credential` to On.
* Click Add.
##### 3.2. Watson Machine Learning
* Go back to the `Resource List` in IBM Cloud.
* Click on `Machine Learning` under services. 
* Under the `Service credentials` tab, click `New credential`.
* Click Add.
  
  
You now have all the resources and code to run the workshop. All further instructions can be found in the notebook.

