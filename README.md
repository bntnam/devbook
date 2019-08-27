<h1>Devbook - A social network for developers</h1>
<img class="img-fluid mb-5" src="https://bntnam.github.io/img/portfolio/devbook-profile.png" alt="">
<h3>1. Introduction</h3>
<p>- Website: <a href="https://bntn-devbook.herokuapp.com/" target="_blank">https://bntn-devbook.herokuapp.com/</a></p>
<p>- Source Code: <a href="https://github.com/bntnam/devbook" target="_blank">https://github.com/bntnam/devbook</a></p>
<p>- Run the project at localhost: <strong>npm run dev</strong></p>
<h3>2. Technologies</h3>
<ul>
    <li><strong>Backend:</strong> NodeJS, ExpressJS.</li>
    <li><strong>Frontend:</strong> ReactJS, Redux, Bootstrap, HTML, CSS and some libraries/tools.</li>
    <li><strong>Database:</strong> MongoDB.</li>
    <li><strong>Hosting:</strong> Heroku.</li>
</ul>
<h3>3. Feature</h3>
<p>- Sign up / Login.</p>
<p>- Create / Edit / Delete a Profile.</p>
<p>- Share a portfolio with other developers.</p>
<p>- Create / Delete posts to share your thoughts.</p>
<p>- Like / Unlike a topic.</p>
<p>- Create / Delete comments to a post.</p>
<h3>4. APIs</h3>
<ul><strong>User:</strong>
  <li>POST api/users/register</li>
  <li>POST api/users/login</li>
  <li>GET api/users/current</li>
</ul>
<ul><strong>Profile:</strong>
  <li>GET api/profile</li>
  <li>GET api/profile/all</li>
  <li>GET api/profile/handle/:handle</li>
  <li>GET api/profile/user/:user_id</li>
  <li>POST api/profile</li>
  <li>POST api/profile/experience</li>
  <li>POST api/profile/education</li>
  <li>DELETE api/profile/experience/:exp_id</li>
  <li>DELETE api/profile/education/:edu_id</li>
  <li>DELETE api/profile</li>
</ul>
<ul><strong>Post:</strong>
  <li>GET api/posts</li>
  <li>GET api/posts/:id</li>
  <li>POST api/posts</li>
  <li>DELETE api/posts/:id</li>
  <li>POST api/posts/like/:id</li>
  <li>POST api/posts/unlike/:id</li>
  <li>POST api/posts/comment/:id</li>
  <li>DELETE api/posts/comment/:id/:comment_id</li>
</ul>
