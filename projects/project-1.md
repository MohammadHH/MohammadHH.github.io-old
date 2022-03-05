---
layout: project
type: project
image: images/nutrition-tracker-mock.png
title: Nutrition Tracker
permalink: projects/nutrition-tracker
# All dates must be YYYY-MM-DD format!
date: 2021-07-19
labels:
  - ReactJS
  - Typescript
  - Storybook
  - Express
  - MongoDB
  - imgbb
summary: "A responsive web app that tracks its users foods consumption and presents them with convenient charts and statistics regarding their recommended nutrients and calories consumption."
---

<a href="https://reverent-swartz-334ee9.netlify.app/" target="_blank" style="display:flex; align-items:center; gap:8px;">
<img class="ui image mini" src="../images/nutrition-tracker-logo.svg"/>
Live Demo
</a> 
<p class="sub header paragraph">
  <span>
    Nutrition tracker is a full-stack responsive web app application. The app
    collects its user's food consumption and presents them with convenient
    charts and statistics regarding their daily recommended nutrients and
    calories consumption.
  </span>
</p>
<p class="sub header paragraph">
  <span>
    The client-side of this app was written with ReactJs, Typescript, SCSS, and
    many other libraries that provide the user with a rich and responsive visual
    experience.It exchanges its data with the server through multiple Rest API
    endpoints. The server has been developed using NodeJs, Express, and MongoDB.
  </span>
</p>
<div class="ui grid">
  <div class="middle aligned two column row">
    <div class="column flex-top">
      <h3 class="ui black huge header">
        <span>Signup/Login</span>
      </h3>
      <p class="sub header paragraph">
        <span>
          Before using the app, the user must log in with his credentials or he
          can go and signup. When the users sign up, they should fill in some
          information regarding their weight, height, age, activity level, and
          the weight they aspire to reach. These pieces of information will be
          used to calculate the recommended amount of nutrients a user should
          consume on daily basis to reach their goal weight.
        </span>
      </p>
    </div>
    <div class="left aligned column">
      <a
        href="../images/nutrition-tracker-signup.png"
        class="ui medium image project-image"
        target="_blank"
        style="margin-right: 5px"
      >
        <img src="../images/nutrition-tracker-signup.png" alt="signup" />
      </a>
      <a
        href="../images/nutrition-tracker-login.png"
        class="ui medium image project-image"
        target="_blank"
      >
        <img src="../images/nutrition-tracker-login.png" alt="login" />
      </a>
    </div>
  </div>
  <div class="middle aligned two column row">
    <div class="column flex-top">
      <h3 class="ui black huge header">
        <span>Foods</span>
      </h3>
      <p class="sub header paragraph">
        <span>
          After the user has signed in. he can go to the foods page where he can
          view the foods he added earlier and update/add new food. Each added
          food has its nutritional content of calories, proteins, carbohydrates,
          and fats.
        </span>
      </p>
    </div>
    <div class="left aligned column">
      <a
        href="../images/nutrition-tracker-foods.png"
        class="ui medium image project-image"
        target="_blank"
        style="margin-right: 5px"
      >
        <img src="../images/nutrition-tracker-foods.png" alt="foods" />
      </a>
      <a
        href="../images/nutritions-tracker-add-food.png"
        class="ui medium image project-image"
        target="_blank"
      >
        <img src="../images/nutritions-tracker-add-food.png" alt="add-food" />
      </a>
    </div>
  </div>
  <div class="middle aligned two column row">
    <div class="column flex-top">
      <h3 class="ui black huge header">
        <span>History</span>
      </h3>
      <p class="sub header paragraph">
        <span>
          On the history page, the user can fill in the foods he ate throughout
          the day and their quantities, and he can view the foods he ate on a
          certain date.
        </span>
      </p>
    </div>
    <div class="left aligned column">
      <a
        href="../images/nutrition-tracker-history.png"
        class="ui medium image project-image"
        target="_blank"
      >
        <img src="../images/nutrition-tracker-history.png" alt="history" />
      </a>
    </div>
  </div>
  <div class="middle aligned two column row">
    <div class="column flex-top">
      <h3 class="ui black huge header">
        <span>Dashboard</span>
      </h3>
      <p class="sub header paragraph">
        <span>
          On the dashboard page, the user is presented with statistics on his
          daily consumption of calories and nutrients. In addition, the user can
          view various charts that show the change in his weight and consumption
          of nutrients over the past few days
        </span>
      </p>
    </div>
    <div class="left aligned column">
      <a
        href="../images/nutrition-tracker-dashboard.png"
        class="ui medium image project-image"
        target="_blank"
      >
        <img src="../images/nutrition-tracker-dashboard.png" alt="dashboard" />
      </a>
    </div>
  </div>
</div>
