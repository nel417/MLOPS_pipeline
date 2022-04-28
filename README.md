# MLOPS_pipeline

### CI/CD pipeline for a machine learning model that predicts wine quality.  

The build pipeline triggers on push and will run the apps requirements, the app itself, and then print a report of based off of the changes of the code changed.

below is the first push of stock code using a max depth of 2: 

![first run](https://user-images.githubusercontent.com/45861790/132251633-e464fdbb-1b34-4eb9-9fc0-9d6249e849ea.png)  

Below is the second push after modifying the regressor to have a max depth of 5, you can see that more of the features are popping up in the report and the fitting of the data has changed in the residuals.

![second run](https://user-images.githubusercontent.com/45861790/132251631-a6213b83-bdf8-4c9c-bcc7-43a06ec7fa68.png)


#### you can view the script in .github/workflows/cml.yaml
