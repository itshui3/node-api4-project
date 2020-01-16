# Web API IV Challenge

In this challenge, you will **deploy** an API of your choosing to `heroku`.

## Instructions

You are allowed, and **encouraged**, to collaborate with other peers. Please follow the twenty-minute rule, before seeking support from your PM and Instructor.

## Minimum Viable Product

Pick any API, could be one of your past projects, and deploy it to `heroku`. Once deployed, send the URL to the TL for your group.

## Stretch Goal

- add support for environment variables using `.env` files. You can use the [dotenv](https://www.npmjs.com/package/dotenv) npm module.


#Deployed Link: https://node-api2-deploy-1-16-thurs.herokuapp.com/

EndPoints : 


/api/posts 
  - GET posts
  - POST new post
    { "title": "", "name": "" }
    
/api/posts/:id 
  - GET post by id
  - DELETE post by id
  - PUT post by id
    { "title": "", "contents": "" }
    
/api/posts/:id/comments
  - GET comments at post id
  - POST comment at post id

