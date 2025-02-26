---
layout: layout.liquid
title: Use of AI
---

<div class="about-container">
  <h2 class="about-title">About the use of AI</h2>
  
  <div class="about-content">
    The use of AI in this assignment was proven effective in some ways, but in others, rather useless. Starting from the beginning of the site, I asked all three options of GPT4, Claude and Gemini, with prompt: "Using Alpine.js and Alpine Fetch, create a layout that supports two JSON endpoints of information on this screen". While GPT4 was the closest to being correct, none of them were able to implement Alpine Fetch in their implementation of the prompt, all of which just used regular JS Fetch commands. GPT4 wrote a function to do the Fetch part, but the other two just spit out some sort of confusing code that I couldn't keep up with. I also prompted "Using Alpine.js, create a layout that supports two JSON endpoints of information on this screen. Use Alpine Fetch for the JSON calls." to both GPT4 and Claude, and got pretty much the same results in return. After, I gave the AI the link to Alpine Fetch, using "Using Alpine.js, create a layout that supports two JSON endpoints of information on this screen. Use Alpine Fetch for the JSON calls. Information about Alpine.js Fetch is here: https://hankhank10.github.io/alpine-fetch/", and the AI was able to find the script source link that needed to go in the head of the file, but after gave just about the same results as before, from both GPT4 and Claude.

    I pulled some of the code from GPT4, to gather the layout together, and got rid of it's JS Fetch function to add in the functionality to use Alpine Fetch. After I completed this, and made sure that the Alpine Fetch was working, I then went on to the style part of the assignment. I prompted GPT4 "Style this page with modern shopping website styling cues using tailwindcss", which gave me some basic, but workable style. However, I wanted a bit more out of it, so I added, "give the style a bit more pizzaz", which added some green text for the money, some borders, and an Add To Cart button. I switched files to get to the file with the navigation bar, and prompted GPT4 "style the navbar using tailwindcss", which gave me another workable, but basic style. I wasn't totally satisfied with that result, however, so I went to Claude with "give this page a clean, modern shopping website style using tailwindcss". This gave me the current style that's on the website, and I'm quite satisfied with it. I then gave Claude the freedom to style this page however it felt, with "give me a style for this simple page using css", and I'm happy with it. 

    Overall, the use of AI in this assignment proved to be useful for coming up with a relatively simple style using a framework I'm not too familiar with (tailwindcss) and making a page look decent, better than the default HTML. It also did decently with coming up with basic Alpine.js solutions, however completely faulted when it came to using Alpine Fetch, so I had to more-or-less re-write the Alpine and Alpine Fetch code myself. Overall, I found GPT4 to be the most useful when helping to write HTML code, but Claude came in on top for styling. I can see it as being a good helper to come up with some draft design ideas, however, is most certainly not ready to replace any human at their job.
  </div>
</div>

