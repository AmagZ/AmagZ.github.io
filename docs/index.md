# 欢迎光临AmagZ的小站
- 如你所见，AmagZ的咕咕嘎嘎日常

## Overview
<div class="links-content">
<div class="link-navigation">
    <div class="card">
        <img class="ava" src="https://raw.githubusercontent.com/AmagZ/AmagZ.github.io/refs/heads/main/docs/sdl.jpg" />
        <div class="card-header">
            <div>
                <a href="https://amagz.github.io/yueping/" target="_blank">一些乐评</a>
            </div>
            <div class="info">AmagZ的春日歌单</div>
        </div>
    </div>
    <div class="card">
        <img class="ava" src="https://raw.githubusercontent.com/AmagZ/AmagZ.github.io/refs/heads/main/docs/image.png" />
        <div class="card-header">
        <div>
            <a href="https://amagz.github.io/photo" target="_blank">一些摄影</a>
        </div>
        <div class="info">用音乐发起一场爱的革命</div>
        </div>
    </div>

</div>
</div>

## 留言板

<div id="waline"></div>

<link rel="stylesheet" href="https://unpkg.com/@waline/client@v3/dist/waline.css" />

<script type="module">
  import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

  init({
    el: '#waline',
    serverURL: 'https://amagz-waline.vercel.app',
    lang: 'zh-CN',
    login: 'disable',
    requiredMeta: ['nick'],
    dark: 'body[data-md-color-scheme="slate"]',
  });
</script>

