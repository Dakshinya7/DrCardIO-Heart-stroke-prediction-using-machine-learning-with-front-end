# DrCardIO Heart Stroke Prediction 🩺


A simple ML and DL based website which predicts if a person is capable of acquiring a heart stroke during his lifetime.

DISCLAIMER ⚠️
This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the creator. So, don't use it for making health decisions. If you do so, the creator is not responsible for anything. However, this project presents the idea that how we can use ML/DL into precision predicting if developed at large scale and with authentic and verified data.

MOTIVATION 💪
A stroke is a life-changing event — physically and emotionally. A stroke can make everyday activities challenging. These challenges may be due to several stroke-related conditions, such as limb weakness, numbness or paralysis, communication challenges, vision challenges and one-side neglect challenges.

In this project, I present a website in which the stroke can be predicted based on the data given by the user.

In the stroke prediction application, the user can provide the health data from their side and the application will predict if the person with such health status can acquire stroke.



DATA SOURCE 📊
Heart stroke prediction dataset (custom built dataset)
Notebooks 📓
Stroke Prediction

       

    

DEPLOYMENT 🚀
Deployment is done using deploy branch
This website is deployed using flask

How to use 💻
Stroke Prediction system ==> enter the corresponding data of your health status.

How to run locally 🛠️
Before the following steps make sure you have git, Anaconda or miniconda installed on your system.
Clone the complete project with git clone https://github.com/Dakshinya7/DrCardIO-Heart-stroke-prediction-using-machine-learning-with-front-end.git or you can just download the code and unzip it.
Note: The master branch doesn't have the updated code used for deployment, to download the updated code used for deployment you can use the following command
❯ git clone -b deploy https://github.com/Dakshinya7/DrCardIO-Heart-stroke-prediction-using-machine-learning-with-front-end.git
deploy branch has only the code required for deploying the app (rest of the code that was used for training the models, data preparation can be accessed on master branch)
It is highly recommended to clone the deploy branch for running the project locally (the further steps apply only if you have the deploy branch cloned)
Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block
conda create -n drcardio python=3.6.12
pip install -r requirements.txt
conda activate drcardio
And finally run the project with
python app.py
Open the localhost url provided after running app.py and now you can use the project locally in your web browser.


Further Improvements 📈
This was my first big project so there are lot of things to improve upon

CSS code is totally messed up 😔 (some code in file and some inline)
Frontend can be made more nicer (PS: I suck at frontend development) 😢
More data can be collected manually via web scrapping to make the system more accurate 🧐
Additional plant images can be collected to make the disease detection part more robust and generalized 🤕
Modularized code can be written instead of writing in Jupyter Notebooks (will follow this in upcoming projects)
