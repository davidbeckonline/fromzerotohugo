+++
title = "Intro"
date = 2022-02-20T13:24:12Z
weight = 20
chapter = true
pre = "<b>01. </b>"
+++

### 01 - Intro and Service Overview

#### The story

Today, I am 'AWS certified Solution Architect - Associate'. And many people ask me how got this certification. This is the reason why I am setting up this website. The core element of learning AWS is building with AWS. At least, this is what I believe. You need some sort of 'pet project'. And I think that setting up a website is a good start.


#### The Services covered in this tutorial

On this website, I want to provide an (almost) click by click overview on how to set up a website from scratch. 'From scratch' meaning without any prior knowledge about AWS or web development. 
So this is what we will touch on:

**THE WEBSITE**

- **Amplify.** We will build a website which will run on Amazon Amplify. This service will do the hosting for us. 
- **Hugo.** The framework on which we are developing the website is Hugo. This is an open source framework which helps to build static website fast and and mostly in markdown.
- *Markdown.** Markdown is a so called markup language. With just a few tricks, you can format your text. For example, the usage of a * in a new line will create a bullet point list. This is much easier then doing the formatting in html.


**THE BACKBONE**

- **Github.** In this overview, I am using Github. We will push the code we write in AWS to Github. Amplify will then read the code from there. Now, for this step we are moving away from the AWS world. If you want to strictly stick to AWS, I will tell you how to use AWS Code Commit. No problem. However, I think that there is an advantage in learning how to deal with Github, as it is such a commont tool in the developer world.
- **Cloud9.** With Cloud9, we will set up a Linux Computer within our cloud (an IDE - Integrated Development Environment). Technically, you could also do the same on your desktop computer. But then your website development is somewhat connected to a desktop computer and that misses the point of cloud computing, in my opinion.

**THE FUNDAMENTALS**

Before we start working on the website, we will need to cover a few fundamentals. 
- **AWS Account Setup**. You will need an AWS account. For the registration, you need a Credit Card. In terms of costs, you should expect that the setup of this website in a simple format will cost about 5 USD per month. Most likely it is going to be less, but I want to you to have an idea.
- **IAM.** You will need to create a user with certain permissions. The account with which you create your AWS account is your 'root account'. We do not use this one for any activities. Best practice. And we protect this root account with 2FA.
- **Billing and Billing Alarm.** As mentioned, you should expect cost of 5 USD per months. Probably less, but I want you to be aware of this. We will set up two billing alarms, so that you receive an email when the monthly cost surpasses 3 USD and when it surpasses 10 USD. 


**OPTIONAL**

A lot of optional things that can be done.
- **Domain registration via Route53.** Assign a domain to your website.
- **Sustainability**. Some thoughts on sustainability in the cloud. 