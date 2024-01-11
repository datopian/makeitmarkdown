# Tutorial 1: Create a website from scratch using Markdown

## Introduction

In this tutorial, we will walk you through creating an elegant, fully functional website written in simple markdown and published with Flowershow.

By the end of this tutorial you will:

- have a working markdown-based website powered by Flowershow.
- be able to edit the text and add pages, all from an online interface without installing anything.

Below is a screenshot of how the final website will look like:

![[tutorial-1-result.png]]
## Prerequisites

- A [GitHub](https://github.com/) account.

## Setting up a website

### 1. Navigate to your Github account and create a new repository

Once you're on your GitHub account, create a new repository by navigating to the top right of the page and clicking 'Create new...', and then 'New repository'.

![[tutorial-1-create-new.png]]

Next, give your repository a name. A good practice is to use lowercase and dashes.

![[tutorial-1-repo-name.png]]

You can also provide an optional description, and choose whether the repository will be private (you can choose who may see and edit it), or public (anyone can see it, but you can choose who may edit it).

Make sure 'Add a README file' is selected. This file will act as a 'home page' for your site.

![[tutorial-1-add-readme.png]]

When you're done, click 'Create repository'. 

### 2. Sign in to Flowershow and create a new site

Navigate to [Flowershow Cloud](https://cloud.flowershow.app/) and sign in using your GitHub account details. 

Click 'Create New Site'. When prompted, select the GitHub account where you created the repository in the previous step, and then select your repository. Click 'Create Site'.

![[tutorial-1-create-site.png]]

### 3. Change your subdomain name

And voila! Your site is up and running. To view your published site, click on the link with the subdomain name that Flowershow has randomly generated for you. It will look something like this (top right):

![[tutorial-1-subdomain.png]]

To edit your subdomain name, click on the tab 'Domains'. Under 'Subdomain', enter the name you would like to give to your site. Note that you can only use letters, digits, uppercase and lowercase dashes for your subdomain name. Click 'Save Changes'.

![[tutorial-1-subdomain-update.png]]

## Editing a page on your website

Once your site is up and running, the next step is to customize it to your liking. Let's start by editing our home page.

### 1. Navigate to the repository of your website on GitHub

You can get there by going to GitHub, clicking on your profile icon, and going to "Your repositories".

### 2. Edit the "README.md" file

Find the file called 'README.md' (it should be the only file in your repository for now.) This is the file on which the homepage of your website is built. Click on it to open.

Then, click on the "Edit this file" icon...

![[tutorial-1-edit-readme.png]]

... and add some content (in Markdown).

![[tutorial-1-add-content.png]]

### 3. Save your changes

To see your changes live, you need to "commit" them. Click on "Commit changes..." button in the top-tight corner.

![[tutorial-1-commit-changes.png]]

In the "Commit message" field add a concise description of your changes (for example, "add welcome message to home page"). Optionally, if the commit message is not enough, you can add more info in the "Extended description" field.

Leave "Commit directly to `main` branch" selected and click on "Commit changes". 

### 4. Preview your site after changes

Once you've committed your changes, GitHub will automatically preview what your site will look like. 

To see the changes on the site itself, navigate back to your Flowershow Cloud account, and click on the link to the site. 

For easy access, you can copy the URL to your site into your GitHub repo. Simply go to the 'About' section on your repo, and click on the settings icon. You will be prompted to enter an optional description, and the URL to the site.

![[tutorial-1-copy-link-to-repo.png]]

## Add a single Markdown-based page

### 1. Navigate to the "content" folder in your website's repository

See how to find it in the previous section.

### 2. Create new file

Click on "Add file"...

![Step 2 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/1708e4fa-8234-4393-a8e9-cd972afce770/b986ab26-d53f-4b57-8520-fb87782dfb22.png?crop=focalpoint&fit=crop&fp-x=0.9119&fp-y=0.2208&fp-z=2.9167&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=737&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zMDkmaD0xMTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

...and "Create new file".

![Step 2 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/e79d32ef-9385-4903-8ca1-408f78752633/7006ac1c-796c-4bb6-95ef-dd4d9969c9b6.png?crop=focalpoint&fit=crop&fp-x=0.8712&fp-y=0.2679&fp-z=2.9167&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=476&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz01NDcmaD0xMTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

### 3. Type the name of the new file you want to create

![Step 3 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/54c786cb-15d6-4abe-8893-fa95dff3ed0a/c39152b2-f446-4e39-a2f3-9b3cf0e7c193.png?crop=focalpoint&fit=crop&fp-x=0.3476&fp-y=0.2214&fp-z=2.1864&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=394&mark-y=418&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00MTMmaD04NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

### 4. Write the content of the file

![Step 4 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/8ffe1e8c-45f9-42b7-8053-bc8bc61b098c/56489034-d5a9-495e-8fb7-1fbfff62d7f3.png?crop=focalpoint&fit=crop&fp-x=0.5170&fp-y=0.3440&fp-z=1.0470&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=7&mark-y=300&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0xMTg2Jmg9ODYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

### 5. Save your changes

To see your changes live, you need to "commit" them. Click on "Commit changes..." buttom in the top-tight corner.

![Step 5 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/382d133d-19f3-4aee-a0fa-535fcb361090/fe7b1fc6-c8f0-4f3f-958a-204c4fc65cf8.png?crop=focalpoint&fit=crop&fp-x=0.9227&fp-y=0.2208&fp-z=2.9167&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=696&mark-y=417&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz00NjgmaD0xMTkmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D)

In the "Commit message" field add a concise description of your changes. Optionally, if the commit message is not enough, you can add more info in the "Extended description" field.

![Step 5 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/13c5873d-4071-4ae2-b641-d6202631076c/53029856-5543-4681-919a-092ed2dacb02.png?crop=focalpoint&fit=crop&fp-x=0.4998&fp-y=0.3476&fp-z=1.4555&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=262&mark-y=447&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz02NzYmaD01OCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

Leave "Commit directly to `main` branch" selected and click on "Commit changes". Doing that will trigger rebuilding of your site on Vercel.

![Step 5 screenshot](https://images.tango.us/workflows/c14ae6dc-9e15-49f5-af87-b513daa701ba/steps/68002c21-451a-4536-89b6-8a0d01d327eb/bb71cbb3-7a79-45f3-a71e-2500a380556c.png?crop=focalpoint&fit=crop&fp-x=0.6278&fp-y=0.7315&fp-z=2.3207&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=418&mark-y=428&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTYlMkNGRjc0NDImdz0zNjUmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

### 6. Preview your site after changes

As you already know, Vercel will now start rebuilding your website. When it's done, you can navigate to `/about` url on your website to see the new file we've just added.

## What's next?

While editing on GitHub UI is acceptable, it has its limitations – it doesn't support working offline, adding multiple files simultaneously, or previewing many markdown syntax elements supported by Flowershow-based websites. We'll delve into these issues and solutions to overcome them in our next tutorial. Stay tuned!

[Next](tutorial-2.md)
