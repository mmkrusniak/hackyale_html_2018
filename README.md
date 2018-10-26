# Intro to Web Design and Development - HackYale 2018

Table of contents:

- [Intro to Web Design and Development - HackYale 2018](#intro-to-web-design-and-development---hackyale-2018)
    - [Goals of this session](#goals-of-this-session)
    - [Pre-session tasks](#pre-session-tasks)
        - [1. Create accounts and install software](#1-create-accounts-and-install-software)
        - [2. Fork the example code from this GitHub account to yours](#2-fork-the-example-code-from-this-github-account-to-yours)
        - [3. Download the example code to your computer](#3-download-the-example-code-to-your-computer)
    - [Optional "reading"](#optional-reading)
    - [End of session: Ready to publish this project?](#end-of-session-ready-to-publish-this-project)

## Goals of this session

* Learn about HTML/CSS
* Iteratively create better web pages
* Publish our finished website to a domain
* If we have time: Learn about how web servers work + teaser for next session

## Pre-session tasks

If you go through as many of these as possible, it will save us time in the session. If you get stuck, feel free to email us.

### 1. Create accounts and install software

1. Make an account on http://github.com
2. Make an account on http://heroku.com
3. Download and install a code-editor. Here are some good ones:
    * VSCode (https://code.visualstudio.com/)
    * Atom (https://atom.io/)
4. Download and install GitHub Desktop from https://desktop.github.com/

Why are we doing all of this? I'll explain in class but:
1. GitHub is where our code is going to live
2. Heroku is where we will publish our website
3. A code-editor makes things look pretty. The ones we've listed also work nicely with GitHub
4. GitHub Desktop lets us use the service in a visual way. Many programmers use GitHub from their Terminals, which is easy to do on a Mac, but requires some effort on Windows. Using GitHub Desktop helps us get up and running on both Windows and Mac easily!

### 2. Fork the example code from this GitHub account to yours

1. Open a web browser
2. Go to https://github.com/sarimabbas/hackyale_html_2018
3. On the top right you'll see a button called Fork. Click it!

Why are we doing this? This is so you have a copy of our code on your account. You will be able to modify it as you please.

### 3. Download the example code to your computer

Easy/convenient way:
1. Open up GitHub Desktop
2. Sign in with your GitHub account, if you haven't already
3. Click "Clone" a repository
4. Select "hackyale_html_2018" from the list
5. You can choose where you want the folder cloned. By default it goes to Documents > GitHub > hackyale_html_2018
6. You probably won't need to use GitHub Desktop again after this!

Alternatively, if you're feeling adventurous:
1. Open up a Terminal
2. Navigate to where you like using `cd`
3. Type and enter: `git clone https://github.com/sarimabbas/hackyale_html_2018`
4. Confirm the folder was downloaded using Finder/Explorer

## Optional "reading"

Confused about what we did/will do? What do terms like "fork" and "clone" mean? How do Heroku and GitHub tie together? 

1. Programming is a social activity! GitHub lets us keep a history of our code, and make it easily accessible to others. Learn more about GitHub: https://www.youtube.com/watch?v=w3jLJU7DT5E

2. With web development, it's important to know how to create web pages as well as know how to share them once we're finished. Here is how the Internet works: https://www.youtube.com/watch?v=7_LPdttKXPc

3. In the above video, Aaron mentions "servers". When we finish making a website in class, how can we share our website with others without buying a separate computer for a server? We can use Heroku. Here is how Heroku works: watch the first 20 seconds of https://www.youtube.com/watch?v=H2Q4vJrxTwo

4. Now, the actual writing of code! Find out more about HTML, CSS and JavaScript: https://www.youtube.com/watch?v=gT0Lh1eYk78

## End of session: Ready to publish this project?

1. Use VSCode or Atom's git features to stage, commit and push changes (we'll go over this in class).  

1. Alternatively, if you're feeling adventurous, open up a Terminal and:
    * Navigate to your project folder using `cd`
    * `git add .` to add all your changes
    * `git commit -m "a change"` to register the change
    * `git push` to upload your changes

2. Next, revisit this page at:
    * `http://github.com/[yourusername]/hackyale_html_2018`
    
3. Click the button below!

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

4. Walk through the steps on heroku.com. If you don't already have an account, go ahead and create one. Your website will be published for free!

5. Want to make changes in the future?
    * Go to `https://dashboard.heroku.com/apps/[yourappname]/deploy/github`
    * Connect to your GitHub account and choose `hackyale_html_2018` as the repo
    * Enable Automatic Deploys
    * Now anytime you `git push` changes to your GitHub repo, it will automatically be uploaded to Heroku!