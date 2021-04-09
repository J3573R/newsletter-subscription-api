# Newsletter Subscription API

Newsletter Subscription API is a microservice that takes emails and adds them to newsletter subscription. You can think it as feature when user register to website and registration form asks if they are allowed to send newsletter.

Application generates file once a month containing all of newsletter subscribers.

The Service have to run with **NodeJs** and it should use **MongoDB** as database solution. You are free to choose framework & packages for the application.

Created service shall be in publicly accessible repository and include README file containing atleast instructions to launch application. **Please return your solution atleast day before interview so we have time to go trough it**.

## Summary

Features that application has to provide are following:

- Register user subscriptions (E.g. `POST /subscriptions`)
- Query newsletter subscriptions (E.g. `GET /subscriptions` & `GET /subscriptions/:id`)
- Generate file containing subscriber list once a month

Tips:

- Create the solution by yourself, we want to see your code
- Be prepared to present your solution and answer possible questions about it
- Use good practices with git, we will check commit history
- For additional bonus points you can add automatic testing for your solution
