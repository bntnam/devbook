# Devbook - A social network for developers

<img class="img-fluid mb-5" src="https://bntnam.github.io/img/portfolio/devbook-profile.png" alt="devbook image">

### 1. Introduction

- Website: <a href="https://bntn-devbook.herokuapp.com/" target="_blank">https://bntn-devbook.herokuapp.com/</a>

- Run the project at localhost: **npm run dev**

### 2. Technologies

- **Backend:** NodeJS, ExpressJS.
- **Frontend:** ReactJS, Redux, Bootstrap, HTML, CSS and some libraries/tools.
- **Database:** MongoDB.
- **Hosting:** Heroku.

### 3. Feature

- Signing up / Logging in.
- Creating / Updating / Deleting a Profile.
- Sharing a portfolio with other developers.
- Creating / Deleting posts.
- Liking / Unliking a topic.
- Creating / Deleting comments to a post.

### 4. APIs

**User:**

- POST api/users/register
- POST api/users/login
- GET api/users/current

**Profile:**

- GET api/profile
- GET api/profile/all
- GET api/profile/handle/:handle
- GET api/profile/user/:user_id
- POST api/profile
- POST api/profile/experience
- POST api/profile/education
- DELETE api/profile/experience/:exp_id
- DELETE api/profile/education/:edu_id
- DELETE api/profile

**Post:**

- GET api/posts
- GET api/posts/:id
- POST api/posts
- DELETE api/posts/:id
- POST api/posts/like/:id
- POST api/posts/unlike/:id
- POST api/posts/comment/:id
- DELETE api/posts/comment/:id/:comment_id
