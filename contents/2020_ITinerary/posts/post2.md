---
title: ""
key: itinerary-post2
permalink: /posts/network
header: false
comments: true
---

<style>
  /* DON'T USE JS TO THIS!! */
  #grid_for_list{
    box-shadow: 1px 1px 1px 1px #ccc;  
    border: 1px solid gray;
    border-radius: 3px;
    cursor: pointer;

    transform: scale(1);
    -webkit-transform: scale(1);
    -moz-transform: scale(1);
    -ms-transform: scale(1);
    -o-transform: scale(1);
    transition: all 0.1s ease-in-out;
  }

  #grid_for_list:hover {
    transform: scale(1.0125);
    -webkit-transform: scale(1.0125);
    -moz-transform: scale(1.0125);
    -ms-transform: scale(1.0125);
    -o-transform: scale(1.0125);
  }

  #cell_for_list{
    padding: 2px 2px 2px 2px;
  }
  #h_for_list{
    margin: 0 0 0 0.5rem;
  }
  #p_for_list{
    margin: 0 0 0 0.5rem;
  }
  div.cell img{
    border-right: 1px solid gray;
    max-width: 100%;  
    max-height: 100%;
  }

  .video-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
  }

  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>

<a class="button button--primary button--rounded button--xl" href="/ITinerary">HOME</a>

# Network Programming
## Introduction
**How do we communicate with each other?** In the connected world, it is important to understand how do Internet work. In this session, you can learn about this, and implement your own application that uses network and communication.


## Pre-class Lecture Video

<div style="width:100%;">
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/lZsCY3R3rgs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

##  Pre-class Material

<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/preclass.pdf';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/ppt.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Pre-class PPT</h5>
    <p id="p_for_list">The lecture video is based on this</p>
  </div>
</div>

<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/exercise.pdf';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/write.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Exercises</h5>
    <p id="p_for_list">Exercises for you</p>
  </div>
</div>

<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/supplement.pdf';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/books.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Supplement</h5>
    <p id="p_for_list">Additional explanation about the topic</p>
  </div>
</div>

## In-class: Lab Session
<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/labsession.pdf';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/labsession.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Lab Session PPT</h5>
    <p id="p_for_list">PPT</p>
  </div>
</div>


## Post-class: Recording

<div style="width:100%;">
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/3m6pFNXaafk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>


<div style="width:100%;">
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/ckIKboN0DfM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>


## Post-class: Assignment & Supplement

<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/net/lab_server.py';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/idea.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Sample Solution for the lab session</h5>
    <p id="p_for_list">Server</p>
  </div>
</div>

<div class="grid scale" id="grid_for_list" onclick="location.href='/ITinerary/contents/2020_ITinerary/assets/session_2/net/lab_client.py';">
  <div class="cell cell--2"><img src="/ITinerary/contents/2020_ITinerary/assets/imgs/idea.png"></div>
  <div class="cell cell--auto">
    <h5 id="h_for_list">Sample Solution for the lab session</h5>
    <p id="p_for_list">Client</p>
  </div>
</div>