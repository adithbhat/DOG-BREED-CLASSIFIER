# DOG-BREED-CLASSIFIER
Image Classification using CNN


Project Overview
Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification and localization, you will make important design decisions about the user experience for your app. Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. Your imperfect solution will nonetheless create a fun user experience!

Project Instructions
Instructions
Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/deep-learning-v2-pytorch.git
	cd deep-learning-v2-pytorch/project-dog-classification
Download the dog dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.

Download the human dataset. Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

Make sure you have already installed the necessary Python packages according to the README in the program repository.

Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb
NOTE: While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. Unless requested, do not modify code that has already been included.

NOTE: In the notebook, you will need to train CNNs in PyTorch. If your CNN is taking too long to train, feel free to pursue one of the options under the section Accelerating the Training Process below.

(Optionally) Accelerating the Training Process
If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU. If you'd like to use a GPU, you can spin up an instance of your own:

Amazon Web Services
You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money, but enrolled students should see a coupon code in their student resources.)

Evaluation
Your project will be reviewed by a Udacity reviewer against the CNN project rubric. Review this rubric thoroughly and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.

Project Submission
Your submission should consist of the github link to your repository. Your repository should contain:

The dog_app.ipynb file with fully functional code, all code cells executed and displaying output, and all questions answered.
An HTML or PDF export of the project notebook with the name report.html or report.pdf.
Please do NOT include any of the project data sets provided in the dogImages/ or lfw/ folders.

Ready to submit your project?
Click on the "Submit Project" button in the classroom and follow the instructions to submit!
