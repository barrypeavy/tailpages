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
        <p class="text-gray-500 mb-4 text-center">{{site.author-bio}}</p>
        {% endif %}
        <p class="mb-2">Below are multitudinous bullet points outlining information about me, along with sundry duties that I can perform:</p>
      </div> <!-- bg-white -->
    </div> <!-- w-full -->
  </div> <!-- flex -->
</div> <!-- container -->