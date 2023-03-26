---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: SF Crimes
---

<div class="container">
  <div class="row">
    <div class="col-md-8">
      <h1>{{ page.title }}</h1>
      <hr>
      <article>
        <h2>Article Title</h2>
        <embed 
            type="text/html" 
            src="/img/bokeh.html"
            width="1100"
            height="425"
            >
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla malesuada massa ut felis vestibulum lobortis. Aliquam quis purus eget enim rutrum molestie. Sed at feugiat massa. Duis finibus metus quis bibendum imperdiet. Ut ut tellus vitae velit scelerisque faucibus. Sed nec ornare nibh. Proin vel nunc eleifend, posuere felis a, pellentesque ex.</p>
      </article>
      <hr>
      <article>
        <h2>Another Article Title</h2>
        <img src="/img/barplot.png" alt="Burglary crimes January 2005">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla malesuada massa ut felis vestibulum lobortis. Aliquam quis purus eget enim rutrum molestie. Sed at feugiat massa. Duis finibus metus quis bibendum imperdiet. Ut ut tellus vitae velit scelerisque faucibus. Sed nec ornare nibh. Proin vel nunc eleifend, posuere felis a, pellentesque ex.</p>
      </article>
    </div>
    <div class="col-md-4">
      <h2>Recent News</h2>
      <embed 
          type="text/html" 
          src="/img/geoplot.html"
          width="1000"
          height="625"
            >
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla malesuada massa ut felis vestibulum lobortis. Aliquam quis purus eget enim rutrum molestie. Sed at feugiat massa. Duis finibus metus quis bibendum imperdiet. Ut ut tellus vitae velit scelerisque faucibus. Sed nec ornare nibh. Proin vel nunc eleifend, posuere felis a, pellentesque ex.</p>
      <ul>
        <li><a href="#">Article Title</a></li>
        <li><a href="#">Another Article Title</a></li>
      </ul>
    </div>
  </div>
</div>