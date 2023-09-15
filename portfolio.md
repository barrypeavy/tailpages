---
layout: page
title: Portfolio
permalink: portfolio
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
        <p class="mb-2">Page under construction. In the meantime, please see this <a class="text-amber-500 hover:text-amber-600 underline decoration-amber-200 underline-offset-2" href="{{site.baseurl}}/assets/files/peavy-portfolio-xsmall-edited.pdf" target="_blank">PDF Portfolio File<i class="fa-solid fa-up-right-from-square fa-sm text-gray-400 ms-1"></i></a></p>
        <p class="mb-2">And here's a <a class="text-amber-500 hover:text-amber-600 underline decoration-amber-200 underline-offset-2" href="{{site.baseurl}}/assets/files/Barry-Peavy-resume-24.pdf" target="_blank">PDF Resume File<i class="fa-solid fa-up-right-from-square fa-sm text-gray-400 ms-1"></i></a></p>
      </div> <!-- bg-white -->
    </div> <!-- w-full -->
  </div> <!-- flex -->
</div> <!-- container -->