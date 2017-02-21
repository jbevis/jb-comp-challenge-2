##Static Comp Challenge 2

###Synopsis
In this challenge I was tasked with recreating a static layout comp using HTML and CSS to build and style a webpage.

###Motivation
This challenge was assigned as part of the Turing School of Software and Design's FEE Mod1 course.

###Code Snippet
````HTML
header class="main-head">
  <nav>
    <ul class="navbar">
      <li><img class="nav-icons" id="shares" src="icons/icon_share.png" alt="Share this page" /></li>
      <li class="nav-text">Share</li>
      <li><img class="nav-icons" id="conservation" src="icons/icon_tree.png" alt="conservation efforts" /></li>
      <li class="nav-text">Conservation</li>
      <li><img class="nav-icons" id="conditions" src="icons/icon_weather.png" alt="Check weather conditions" /></li>
      <li class="nav-text">Weather</li>
    </ul>
  </nav>
  <article class="header-logo">
    <img id="username" src="icons/icon_profile.png" alt="User profile"/>
    <p class="nav-text">Admin Username</p>
    <img id ="logo" src="images/icon_npslogo.png" alt="National Park Service logo"/>
  </article>

  ````CSS
  .main-head {
    background-color: #474544;
    display: flex;
    width: 100%;
    height: 100%;
  }

  h1 {
    margin-left: 15px;
    color: #474544;
  }

  nav {
    align-self: flex-end;
    display: flex;
    width: 66.67%;
    height: 100%;
    top: 45px;
    margin-bottom: 10px;
  }
````
###Resources
Below is the comp on which the challenge is based and my version.
![comp_mockup](comp_mockup.jpg)

![my_version](my_version.jpg)
