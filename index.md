---
layout: home
title: Home
permalink: /
---

<div class="container w-full md:max-w-4xl mx-auto">
  <div class="flex flex-wrap text-sm">
    <div class="w-full">
      <div class="bg-white border shadow-md p-3 md:py-5 md:px-10 h-full ">
      <!-- <img class="object-cover mx-auto h-36 w-36 rounded-full" src="{{site.baseurl}}/assets/img/{{site.author-image}}" alt="author profile image"> -->
      <h1 class="uppercase text-center font-semibold text-gray-500 text-lg">{{site.author}}</h1>
        {% if site.author-bio %}
        <p class="text-gray-500 mb-4 text-center font-medium">{{site.author-bio}}</p>
        {% endif %}
        <p class="mb-2">I am a hybrid web UI/graphic designer and front-end developer with 15+ years remote experience, well-versed in both creative work in Adobe Creative Suite and the like — and more technical work in HTML/CSS and frameworks such as Bootstrap and Tailwind.</p>
        <p class="mb-2">Outside of work, my hobbies and interests include playing guitar and banjo, singing, background/commercial acting, nationwide hiking/camping/overlanding, golf, fitness, and DIY projects. I also travel frequently to Texas to spend time with my daughter, and the Georgia coast to visit extended family.</p>
        <p class="mb-2">Here's my <a class="text-amber-500 hover:text-amber-600 underline decoration-amber-200 underline-offset-2" href="{{site.baseurl}}/assets/files/Barry-Peavy-resume-24-2pg.pdf" target="_blank">PDF Resume File<i class="fa-solid fa-up-right-from-square fa-sm text-gray-400 ms-1"></i></a></p>
        <p class="mb-2" style="display:none;">Below are multitudinous bullet points outlining information about me, along with sundry duties that I can perform:</p>
      </div> <!-- bg-white -->
    </div> <!-- w-full -->
  </div> <!-- flex -->
</div> <!-- container -->