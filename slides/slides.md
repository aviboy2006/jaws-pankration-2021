---
theme: seriph
background: >-
  https://s3.amazonaws.com/demo.avinashdalvi.com/assets/aws-amplify-hosting-first-slide.png
class: text-white
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
---

<!--
Hello everyone, 
My self Avinash Shashikant Dalvi, you call me Avi. I am full stack developer and Currently working as senior software engineer at Eagleview India. I am AWS Community Builder.
Today we are going to learn about how to host static website
using AWS Amplify.
-->

<!--
Hello everyone, 
My self Avinash Shashikant Dalvi, you call me Avi. I am full stack developer and Currently working as senior software engineer at Eagleview India. I am AWS Community Builder.
Today we are going to learn about how to host static website
using AWS Amplify.
-->

---

# Agenda
- What is **AWS Amplify** ? 
- What **AWS Amplify** provides ?
- **AWS Amplify** support for ? 
- Steps to host static website on **AWS Amplify**
- How to keep environment variable secured ?
- Demo
 

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# What is **AWS Amplify** ? 

amplify means to make something **stronger**, **bigger**, **louder** or **more important**
<!-- Before amplify come into picture AWS was providing static hosting using S3 bucket. Problem with S3 was only any library installation like node modules have to
to do it before pushing code into S3 bucket. To solve this problem and make more stronger and better solution come with Amplify console.  -->

AWS Amplify is a package of tools and services

- To accelerate deploying app over AWS cloud 
- make more easiler installation of dependent library 
- built-in CLI

<!--
Before amplify come into picture AWS was providing static hosting using S3 bucket. Problem with S3 was only any library installation like node modules have to
to do it before pushing code into S3 bucket. To solve this problem and make more stronger and better solution come with Amplify console.
-->

---
layout: image-right
image: https://s3.amazonaws.com/demo.avinashdalvi.com/assets/aws-amplify-tools.png
---

# What **AWS Amplify** provides ?

- Configure serverless backends with authentication, storage, data, and more, using intuitive workflows.

- Connect web and mobile apps to new and existing AWS resources in just a few lines of code.

- Collaborate effortlessly in the Amplify admin UI, where you can easily manage app users and content.

- Deploy and **host static websites**, **single-page web apps**, and server-side rendered apps in a few clicks.

<!--
You can see right hand side of slides many list of feature provided by Amplify
-->

---

# **AWS Amplify** support for
Amplify libraries support 
- iOS 
- Android 
- Web 
- Flutter
- React Native apps
- For Web apps, there is deep integration with React, Ionic, Angular, and Vue.js.

---

# Steps to host static website on **AWS Amplify**
<!-- This is a note -->

<br><br>
<img src="/images/aws-hosting-static-website.png">

<!--
AWS Amplify offers a fully managed static web hosting service that can be accessed directly from the AWS console. AWS Amplify's static web hosting service provides a complete workflow for building, deploying, and hosting single page web apps or static sites with serverless backends.
-->

---
class: px-20
---

# How to keep environment variable secured ?
<img src="/images/environment-variable.png">
<img src="/images/build-setting.png">

<!--
Mostly we always worried about  where to keep environmental value if web apps going to host as static hosting. It is not recommended to keep under git repository. To solve this issue Amplify provide  environment console UI where we can set environmental variable.Once we set those variable we have to do small changes in build configuration under amplify.yaml file as shown in left side of picture.
-->

---

# Demo 

Hosting react app along passing environmental variable on AWS Amplify console. 

<br>
<img src="https://c.tenor.com/uba3gOLyOSsAAAAC/stickergiant-action.gif">

---

# Q&A, Links

* [GitHub repo (slides + sample code)]()
* [AWS Amplify FAQ](https://aws.amazon.com/amplify/faqs/)
* [AWS Amplify](https://aws.amazon.com/amplify/)
* [AWS Amplify Environment variable](https://docs.aws.amazon.com/amplify/latest/userguide/environment-variables.html)
* [Static hosting of Angular on AWS Amplify ](https://www.internetkatta.com/static-hosting-of-angular-build-using-aws-amplify)
* Connect me on [Twitter](https://twitter.com/aviboy2006), [GitHub](https://github.com/aviboy2006), [LinkedIn](https://www.linkedin.com/in/avinash-dalvi-315b021a/)
