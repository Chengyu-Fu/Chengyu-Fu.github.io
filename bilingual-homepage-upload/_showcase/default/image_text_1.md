---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" class="lazy w-100 rounded-xl" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay" style="overflow: scroll; background: rgb(255,255,255,0.8)">
    <h5 class="card-title">
      <span data-content-language="en" lang="en">Image Lazyload</span>
      <span data-content-language="zh-CN" lang="zh-CN">图片延迟加载</span>
    </h5>
    <p class="card-text" data-content-language="en" lang="en">
      It is highly recommended to use lazyload for images to improve page loading speed, especially for pages with many images.
      Example code snippet:
    </p>
    <p class="card-text" data-content-language="zh-CN" lang="zh-CN">
      延迟加载可以提高页面加载速度，尤其适合图片较多的页面。以下是代码示例。
    </p>
    <p class="card-text">
      {% raw %}
      <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-xl&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
      {% endraw %}
    </p>
  </div>
</div>
