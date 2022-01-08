# Social Media Login

---

The average number of social media accounts is 8.4 per person in 2020. The growth in the number of accounts per person is up 75% from 4.8 accounts per person in 2014 to 8.4 in 2020.

<img align="left" alt="Visual Studio Code" width="780px" src="https://github.com/harshithvh/Social-Media-Login-using-Facebook-API/blob/main/images/img-5.png" />

# Importance

---

86% of users report being bothered by having to create new accounts on websites. Out of all the available login methods available Facebook is the most used.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Social-Media-Login-using-Facebook-API/blob/main/images/img-2.png" />

# Web Authentication

---

Authentication is the process of verifying the identity of an individual. A user can interact with a web application using multiple actions. Access to specific activities or pages can be restricted using user levels. Authorization is the process of controlling user access via assigned roles & privileges.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Social-Media-Login-using-Facebook-API/blob/main/images/img-3.png" />

# Facebook API

---

The Conversions API is designed to create a direct connection between your marketing data and the Facebook systems that help optimise ad targeting, decrease cost per action and measure results.

The Conversions API is designed to create a direct and reliable connection between marketing data from your server, website platform or CRM to Facebook. This marketing data helps power ad personalisation, optimisation and measurement on Facebook so that your ads are shown to people who are more likely to be interested in them.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/Social-Media-Login-using-Facebook-API/blob/main/images/img-4.png" />


# Facebook Login Demo with Heroku

- mkdir <project>
- cd <project>
- code .
- npm init -y
- npm install http-server
- package.json > "start" script "http-server"
- index.html (facebook demo code)
- heroku website > register, create new app <project>
- heroku login
- heroku git:remote -a <project>
- git add . && git commit -m up && git push heroku master
- facebook developer website
 - create app <project><test-version>
 - quickstart > choose www > https://<project>.herokuapp.com
 - settings: turn on: Login with the JavaScript SDK
 - settings: Allowed Domains for the JavaScript SDK: https://<project>.herokuapp.com
