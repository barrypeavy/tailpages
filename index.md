---
layout: home
title: Home
permalink: /
---

<div class="container w-full md:max-w-4xl mx-auto">
  <div class="flex flex-wrap text-sm">
    <div class="w-full sm:w-1/2 lg:w-1/4 py-3 px-2">
      <div class="bg-white border shadow-md p-3 h-full ">
      <!-- <img class="object-cover mx-auto h-36 w-36 rounded-full" src="{{site.baseurl}}/assets/img/{{site.author-image}}" alt="author profile image"> -->
      <h1>{{site.author}}</h1>
        {% if site.author-bio %}
        <p class="text-gray-500 pb-4">{{site.author-bio}}</p>
        {% endif %}
        <p class="mb-2">Lorem ipsum</p>
      </div> <!-- bg-white -->
    </div> <!-- w-full -->
  </div> <!-- flex -->
</div> <!-- container -->