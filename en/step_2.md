## Create your machine learning model

First, create your machine learning model on Machine Learning for Kids:

--- task ---

Open the website [Machine Learning for Kids](https://machinelearningforkids.co.uk/#!/login){:target="_blank"}.

--- /task ---

--- task ---

On the screen that appears, choose **Log In** if your have an account at Machine Learning For Kids. Enter your username and password on the next screen.

![A picture of the blue log in button.](images/singup_login.png)

Choose **Sign Up** if you want to create your own account and then follow the prompts to create a new account.

Choose **Try it now** if you don't have an account, and don't want to sign up for a new one.

--- /task ---

--- collapse ---
---
title: If you logged in with an account
---

Select **Go to your projects**.
![Image of the blue 'go to your projects' button on Machine Learning for Kids.](images/go2projects.png)

--- /collapse ---

--- task ---

Select **Add a new project**.
![Image of a grey button that reads 'Add a new project'.](images/add_new_project.png)

--- /task ---

--- task ---

Give the project a name and set it to recognise **text**.
![](images/name_project.png)

--- /task ---

--- task ---

Select **CREATE**. Once created, click on the project title.

![](images/create_button.png)

--- /task ---


Now that you have created a project that identifies text, you need to set out the different ways your text can be classified - these will be your **classes**.

--- collapse ---
---
title: Classes and labels
---

**Classes** are the major categories we're trying to sort those quotes into. In our case, we only have two **classes**: 'hero' and 'villain'.

**Labels** are the specific names we give to each picture in the training data to help the model identify what is in each quote.

For instance, if you see a quote from a hero in the training data, you'll label that quote as `hero`. By doing this, you're telling the model that this quote belongs to the `hero` class. Similarly, if you have a quote from a villain, you'll label it `villain`, placing it in the `villain` class. Once you train it on this information, the model can be used to predict which class new quotes belong to.

![An image explaining that a class is a major category an image can be sorted into. It shows a group of apple pictures in one box, next to an explanation that a label is given to each image to show which class it fits into, with a single apple picture.](images/class_vs_label.png)

You can use as many classes as you want in your model. In our scenario, it's pretty straightforward: every image is either a `hero` or `villain`. But in other projects, you could have multiple classes based on various characteristics of the data you're working with. (Specific words, a cheerful tone, the language of a piece of writing....)

--- /collapse ---

--- task ---

Select **Train**. This will let your add new training data to your model.
![](images/train.png)

--- /task ---
