layout: simple
extends: default.liquid
title: 'Startseite'
---

<div class="container">
  <div class="row">
    <div class="col-md-8 m-0 p-0" style="height:26vw;
background-image: url(https://bewegung.jetzt/wp-content/uploads/2018/01/DiB_Alexanderplatz_weiland-36-1920x1080.jpg);
background-size: cover; overflow: hidden">
      <!-- <div class="embed-responsive embed-responsive-21by9" style="opacity: 0.75">
        <video class="victories_video-video victories_video-hero_container-responsive-embed-video" loop="" muted="" poster="https://avaazimages.avaaz.org/victories/vicvideo-frame1.jpg" preload="auto" autoplay="autoplay" style="display: inline-block;">
          <source src="https://avaazimages.avaaz.org/victories/avaaz_victories.mp4" type="video/mp4">
          <source src="https://avaazimages.avaaz.org/victories/avaaz_victories.webm" type="video/webm">
          <source src="https://avaazimages.avaaz.org/victories/avaaz_victories.ogv" type="video/ogg">
        </video>
      </div> -->
      <div class="overlay" style="display: inline-block; position: absolute; bottom: 3em; left: -5px; transform: rotate(-5deg);">
        <h1 class="text-white bg-primary px-4 m-0" style="display: inline-block">500.000 Menschen</h1><br/>
        <h3 class="text-white bg-primary px-4 m-0" style="display: inline-block; margin-top: -1px">erarbeiten Visionen für unser Europa</h3>
      </div>
    </div>
    <div class="col-md-4 bg-info text-white d-flex justify-content-between align-items-begin" style="
background-image: url(/assets/images/backdrops/dib-protest.png);
background-size: cover; background-position: bottom center;">
      <div>
        <h3>Gemeinsam.<br/>Politik. Machen.</h3>
      </div>
      <a href="/" class="align-self-end btn btn-lg btn-primary border-white text-white ">⇢</a>
    </div>
  </div>
  <div class="row mt-4 p-0">
    <div class="col-md-6 px-0">
      <a href="" class="btn-lg p-3 m-0 w-100 btn btn-warning text-white rounded-0">Jetzt online beteiligen ⇢</a>
    </div>
    <div class="col-md-6 px-0">
      <a href="" class="btn-lg p-3 m-0 w-100 btn btn-success text-white rounded-0">Zu einem Treffen kommen ⇢</a>
    </div>
  </div>
  <form class="row mt-4 p-0 bg-secondary text-white align-items-center">
    <div class="col-md-5 p-3 text-left text-uppercase">
      Immer auf dem Neuesten per E-Mail
    </div>
    <div class="col-md-3 px-1 mx-0">
        <input class="w-100 form-control" placeHolder="E-Mail-Adresse" />
    </div>
    <div class="col-md-2 px-1 mx-0">
        <input class="w-100 form-control " placeHolder="PLZ" />
    </div>
    <div class="col p-0 mr-0">
        <button class=" btn btn-primary" type="submit">eintragen</button>
    </div>
  </form>
  <div class="row align-items-center justify-content-center mt-4">
    <span class="text-right h4">Oder per</span>
    <ul class="h1 text-left">
      <li class="inline-icon">{% include "icons/brands/facebook.svg" %}</li>
      <li class="inline-icon">{% include "icons/brands/twitter.svg" %}</li>
      <li class="inline-icon">{% include "icons/brands/youtube-square.svg" %}</li>
      <li class="inline-icon">{% include "icons/brands/instagram.svg" %}</li>
      <li class="inline-icon">{% include "icons/brands/snapchat-ghost.svg" %}</li>
      <li class="inline-icon">{% include "icons/brands/whatsapp.svg" %}</li>
    </ul>
  </div>
  <div class="row mt-1 text-center justify-content-center align-items-center">
      <div class="text-uppercase px-2"><span class="inline-icon">{% include "icons/solid/bolt.svg" %}</span>Direkt zu</div>
      <div class="px-2"><a href='/'><u>Marktplatz der Ideen</u></a></div>
      <div class="px-2"><a href='/'><u>Abstimmungs-Plenum</u></a></div>
      <div class="px-2"><a href='/'><u></u></a></div>
    </ul>
  </div>
</div>
