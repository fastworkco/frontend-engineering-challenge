<p align="center">
  <img src="https://design.fastwork.co/_nuxt/img/fw-logo-full-mono-600x100.0dfad36.png" width="600">
</p>

# { "developer": "Full Stack Engineer(Frontend)" } to FastWork

Objective of this challenge is to evaluate your domain in fullstack development, that is, its organization, style and good practices with the code, creation of Restfull APIs, knowledge of the frameworks and technologies used.

## Rules

1. All your code should be made available in a public or private repository on your personal github or bitbucket. Send the link to [ben@fastwork.co](mailto:ben@fastwork.co) or pull-request from this repository;

2. Develop the project using:
    - HTML and CSS (or some preprocessor);
    - Some SPA framework (Single Page Application). Suggestion: **Vue.js, ReactJS** ;
    - APIs em **Node.js, Go, Python**;
3. Submit the link of your repository with the challenge code until **10 days** after its application.

## The challenge

Here is the layout that should be produced:
![Layout](files/layout-onepage.png)

Here's the layout in PSD:
[File Download](files/layout-onepage.psd)

### APIs

Note that in the layout above we have a form, a table with information of percentage of participation of each person and a graph of pizza that represents this distribution, that is, we need API that sends and receives these from server.

#### POST /employees

You should develop this API that waits for this "employee" resource to register.

Do not worry about authentication methods, validation, token for this API, but we'll be happy if you develop tests for it =)

#### GET /employees

You should develop this API that returns the JSON with the list of "employees" with their due participation.

### Some tips and remarks

> Note 1: Feel free to use any 3rd party, be it for graphics, tests, etc;
> Note 2: Consider that all fields are mandatory in the form.
> Note 3: Consider validating the fields also in the API and in case of inconsistency return error in a structured JSON with HTTP 400 code

## Doubts

Send your questions directly to [ben@fastwork.co](mailto:ben@fastwork.co) or opening a issue
