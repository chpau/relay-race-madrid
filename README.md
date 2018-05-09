# Relay-Data-Race with DSX, In Madrid - About Madrid!

![im](images/relay_race.jpg)

Assign roles to each team member - and follow the instuctions.

- Person sitting most to the North is the Project Manager.
- From her/him, point remaining member clockwise, in same order as listed here.

## 1 - Project Manager

Create a project in DSX

![im](images/new_project_dsx.png)

Add each team member as a collaborator, giving her/him full admin rights. Go to **Collaborators** and **Add Collaborator**. You need the email address for each collaborator.

![im](images/add_collaborator.png)

## 2 - Data Uploader

- Tell the Project Manager your email, she/he needs this to add you to the page.
- Download the Data from this Repository (Data folder), `madrid_test.csv.csv` & `madrid_train.csv`
- If you are added, add the data to the project. Go to "Assets" and upload the data.

![im](images/load_data.png)

## 3 - Notebook Uploader

- Tell the Project Manager your email, she/he needs this to add you to the page.
- Download the .ipynb from this Repository (Notebook folder), `Madrid Houses.ipynb`
- If you are added, add the notebook to the project. Go to "Assets" > "New Notebook"
- use "Default Anaconda Free (1 vCPU and 4 GB RAM)"

![im](images/new_notebook_environment.png)

## 4, 5, 6... - All other members

- Tell the Project Manager your email, she/he needs this to add you to the page.
- Give coffee or tea to team members and class instructor
- Take a look at the data, think of what model you would apply to predict price. The data was collected from https://www.fotocasa.es/en/.

## Everybody - Start creating a daffy Model!

Read the notebook instructions and try create the best performing model!
The method of calculating the performance is outlined in the notebook. For this the Test set is used. Play fair- dont train on the test set.

## General Hints & Tips

- You can duplicate notebooks - members can try out strategies in parallel (or create your own project with own environment).
- Some models can be deployed in WML, and a webapplication can be easily created with them.
Alonso from Madrid, has created this demo:
http://ialonso.es/projects/dsxwml/
- DSX Can connect to other data sources as well
