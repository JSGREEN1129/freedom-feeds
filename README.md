# freedom-feeds
The project is to develop a static and basic web application to promote a charity called **Freedom-feeds**. 

# Table of Contents
1. [Built with](*Builtwith)
2. [About](#about)
3. [Features](#features)
4. [Deployment](#deployment-using-github-and-vs-code)
5. [Updating the site](#updating-the-site)
6. [Code validation](#code-validation)
7. [External assistance used and image repositories](#external-assistance-used-and-image-repositories)
8. [Assistance acknowledments](#assistance-acknowledments)

---

# Built with
**HTML**

**CSS**

---

# About
The charity engages in fundraising activites to help support war veterans and their families, when they suffer hardship due to military deployment.

This can be in the form of donating food, everyday essentials and technology grants.

---

# Features

## Charity Information page: Information about the charity.
**Our mission section**: A section detailing what Freedom-feeds activities are and why they do what they do.

**Sophie's story section**: A personalised story form the wife of a war veteran whos husband suffered extreme mental health difficulties when returning from deployment.

**Impact to date section**: A section sharing what the charity has achieved so far with its received donations.

## Donations details page
**Donations page**: Details on the donations that Freedom-feeds are requesting and how those will be put to use.

## Contact details page
**Contact details page**: Deatails for members of the public or corporate clients how to contact the charity and offer their support.

## Donate button
**Donate button** A purpose built CTA button which can be positioned throughout the website to guide visitors to the donations page.

## Contact form
**Contact form** An easy to navigate contact form and submit button for users to contact through the web. 

## Salvation Army external link
**Salvation army external link** An external link which opens the salvation army website in a new tab by clicking the logo.

# Deployment using GitHub and VS Code

In this section, I’ll explain how I deployed my project using **GitHub** and **VS Code**.

## Prerequisites

Before starting the deployment, I made sure that I had the following tools installed on my computer:
- **Git**: I downloaded Git from [here](https://git-scm.com/downloads) and followed the installation steps.
- **VS Code**: I also installed Visual Studio Code, which is my code editor. I got it from [here](https://code.visualstudio.com/).
- **GitHub Account**: I signed up for a GitHub account at [GitHub](https://github.com/).

## Steps I Followed to Deploy the Project

### 1. Set Up the Local Project with Git

First, I initialized my project as a Git repository on my local machine. Here’s how I did it:

1. I opened **VS Code** and navigated to the folder where my project files were located.
2. I opened the terminal in VS Code.
3. Then, I ran the following command to initialize the Git repository in my project folder:

    ```bash
    git init
    ```

4. After initializing the Git repository, I added all the project files to Git:

    ```bash
    git add .
    ```

5. Next, I made my first commit to the repository with the following command:

    ```bash
    git commit -m "Initial commit"
    ```

### 2. Created a Repository on GitHub

Once my project was initialized locally, I created a new repository on **GitHub** to store my project online. Here’s what I did:

1. I logged into my GitHub account and clicked on the **New** button to create a new repository.
2. I gave the repository a name (e.g., "my-project") and made it public.
3. After creating the repository, I was directed to a page with instructions on how to link my local repository to this GitHub repository.

### 3. Linked the Local Project to GitHub

Next, I linked my local project to the GitHub repository so that I could push my changes to GitHub:

1. In the VS Code terminal, I ran the following command to add the remote URL of my GitHub repository:

    ```bash
    git remote add origin https://github.com/jsgreen1129/freedom-feeds.git
    ```

2. Then, I pushed my local project to GitHub using the following command:

    ```bash
    git add .
    git push
    ```

    Git prompted me to enter my GitHub credentials (username and password or personal access token), which I provided. This pushed all my files to GitHub.

### 4. Deployed the Project Using GitHub Pages

Since my project is a static website, I decided to use **GitHub Pages** to deploy it. Here's how I set it up:

1. I went to my GitHub repository and clicked on the **Settings** tab.
2. I scrolled down to the **GitHub Pages** section.
3. Under **Source**, I selected the branch I wanted to use for deployment.
4. After enabling GitHub Pages, I received a URL ( https://jsgreen1129.github.io/freedom-feeds/ ) where my project was now live.

### 5. Testing the Deployment

Once I enabled GitHub Pages, I waited a few moments for the deployment to complete. I then opened the provided URL in my browser to see my site live and working!

---

## Updating the Site

Whenever I made changes to my project, I followed these simple steps to update the live site:

1. **Commit Changes**: Whenever I modified the project, I added and committed the changes using:

    ```bash
    git add .
    git commit -m "Updated changes"
    ```

2. **Push to GitHub**: I pushed my changes to GitHub:

    ```bash
    git add .
    git push
    ```

GitHub Pages would then automatically update the live site.

---

## Code validation

https://validator.w3.org/ - For HTML error checking and validation

https://jigsaw.w3.org/css-validator/validator - for CSS error checking and validation


## External assistance used and image repositories 

https://www.youtube.com/watch?v=gWgzzVVcqfA - For contact form

https://www.cleanpng.com/free/salvation-army.html - Salvation army PNG

https://unsplash.com/ - Images throughout website

https://www.pexels.com/ - Images throughout website

https://www.freepik.com/ - Images throughout website

https://www.flaticon.com/free-icons/poppy - Poppy icon used in header and footer

## Assistance acknowledments 

Throughout my project I used sources to help me with the development and understanding of specifc elements of code that I struggled with. I used the below assistance. I mainly used the below for help with applying overlay to images in the hero section and also for mobile responsiveness. 

https://www.w3schools.com/

https://www.geeksforgeeks.org/

https://chatgpt.com/

