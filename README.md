# Project-5-Potato-Disease-Classification
![](picture.png)

# Introduction - 
This project lets the user upload pictures of plant leaves through the website or the mobile and the project then let's the user know whether the potato plant has any disease or it's healthy.

# Tech stack used - 
1. Python
2. Numpy and pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn and Tensorflow for model building
5. Jupyter Notebook in VS Code as IDE
6. Python flask/fast api server for http server
7. Node.js and NPM
8. React for website UI
9. React Native for Android App
10. Android Studio for testing android app
11. Google Cloud's App Engine for deployment

# Train the ML model - 
1. Download this repo and run the 'model_creation.ipynb' jupter notebook.
2. After the notebook has run successfully, a 'potatoes.h5' model file will be created in the same directory.
3. Move the model to 'saved_models' folder.

# Deploy the website locally - 
1. Navigate to the frontend folder in both the IDE and the terminal.
2. Run the following command to install all the dependencies.
```
npm install
```
3. Now run the following command to fix dependency issues.
```
npm audit fix
```
4. Now open the 'flask_code.py' file and change the address in the python file to your model in the 'saved_model' folder. Run the python file.
5. Copy the IP address which starts with '127' and ends with '8080', add '/predict' at the end and paste it in the '.env' file. For example - 
```
REACT_APP_API_URL=http://127.0.0.1:8080/predict
```
6. Now open a new terminal window and navigate to the frontend folder and run the following command.
```
npm run start
```
7. Congratulations!! Your website should work now locally














