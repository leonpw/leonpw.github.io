---
layout: post
title:  "The creation of Cover Letter AI"
date:   2023-02-19 11:59:03 +0300
categories: cover letter ai react typescript
---



In the XXI century when you have to do a tedious task that you happen to do over and over again, you might ask yourself; Why isn't there an app for that? I was applying for a job application and they want me to write a cover letter. So I created the app myself. Just for fun.

Lo and behold. I created Cover Letter AI. A cover letter generator using chatGPT. Give it the Position, Company name and the full job description and it generates the cover letter for you! How does it work? A simple web application uses OpenAI GPT-3 to generate the cover letter based on the input for you. No need to sign up or anything! It takes about 20 seconds to get the results to you. I used #NodeJS, #NextJS, #TypeScript and #React for the front-end, #Azure Tables for logging, #GitHub for hosting the code, Azure #DevOps for the Release pipelines. #Docker for building, deploying and running the app on a VM in the Azure Cloud. This is not the usual stack I'm working on, so it was fun as well.





Preview:
![cover_letter]({{ site.baseurl }}/static/images/example_dutch.gif)

Try it yourself here: [https://cover-letter.wieisleon.nl/](https://cover-letter.wieisleon.nl/)

[Source code](https://github.com/leonpw/gpt-cover-letter)

[Release pipeline](https://dev.azure.com/leonpw/gpt-cover-letter/_release?definitionId=1&view=mine&_a=releases)

Tech stack used:
React, TypeScript, Node, Azure DevOps, GitHub, Docker, bash, CI/CD