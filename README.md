# Relay-Data-Race with Watson Studio -  In Madrid - About Madrid!

![im](images/relay_race.jpg)

Assign roles to each team member - and follow the instuctions.

- Person sitting most to the North is the Project Manager.
- From her/him, point remaining member clockwise, in same order as listed here.

## 1 - Project Manager

Create a project in DSX (-Data Science Project-)

![im](images/new_project_dsx.png)

Add each team member as a collaborator, giving her/him full admin rights. Go to **Collaborators** and **Add Collaborator**. You need the email address for each collaborator. Collaborators can edit data, notebooks and more.

![im](images/add_collaborator.png)

## 2 - Data Uploader

- Tell the Project Manager your email, she/he needs this to add you to the Project Page.
- Download the Data from this Repository (Data folder), `madrid_test.csv.csv` & `madrid_train.csv`
- If you are added to the Project, add the data to the project. Go to "Assets" and upload the data.

![im](images/load_data.png)

## 3 - Notebook Uploader

- Tell the Project Manager your email, she/he needs this to add you to the Project page.
- Download the .ipynb from this Repository (Notebook folder), `Madrid Houses.ipynb`
- If you are added, add the notebook to the project. Go to "Assets" > "New Notebook" > "From File"
- use "Default Python 3.5 Free (1 vCPU and 4 GB RAM)"

![im](images/new_notebook_environment.png)

## 4, 5, 6... - All other members

- Tell the Project Manager your email, she/he needs this to add you to the Project page.
- Take a look at the data, think of what model you would apply to predict price. The data was collected from https://www.fotocasa.es/en/.
- Feel free to create your own Project to try out a wacky idea.

## Everybody - Start creating a daffy Model!

Read the notebook instructions and try create the best performing model!
The method of calculating the performance is outlined in the notebook. For this the Test set is used. Play fair- dont train on the test set.

Rules of the Hackathon:

1. Be fare with using Train & Test test.
2. Each team member should be able to explain data tranformations & model. Each team member will be asked to explain differents parts. Make sure everybody understands what was created.

## General Hints & Tips

- You can duplicate notebooks - members can try out strategies in parallel (or create your own project with own environment).
- Some models can be deployed in WML, and a webapplication can be easily created with them.
Alonso from Madrid, has created this demo:
http://ialonso.es/projects/dsxwml/
- DSX Can connect to other data sources as well
- Day 1 there was a talk about basic data check - for this there is a python package- pandas profiling. See the result on the test set at http://htmlpreview.github.io/?https://raw.githubusercontent.com/willemhendriks/relay-race-madrid/master/pandasprofiling_example.htm .  This was created in Watson Studion, where the package can be installed.
