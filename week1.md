
```html
<!doctype html>
<html>
<head>
  <style>


    body {
      background-color: #f0f0f0; /* 这里设置网页背景颜色 */
      font-family: Arial, sans-serif; /* 这里设置网页字体 */
    }

    h1 {/* 这里设置标题 */
      color: #333; /* 这里设置标题颜色 */
      text-align: center; /* 设置标题居中 */
      margin-top: 20px; /* 标题上方留空20像素 */
    }

    p {/* 这里设置内容 */
      color: #666; /* 这里设置段落文本颜色*/
      line-height: 1.5; /* 这里设置行高 */
      margin: 20px; /* 段落四周留空20像素 */
      text-align: justify; /* 使段落文本两端对齐 */
    }

    #image-here {/* 这里调节图片1 */
  position: fixed;
  top: 0px;
  right: 0px;
  width: 1200px;
  opacity: 0.6; /* 不透明度 */
  border-radius: 15px 50px 30px 5px; /* 圆角 */
}
    #image-2 {/* 这里调节图片2 */
      position: absolute;
      top: 500px;
      right: 100px;
      opacity: 0.6;
      border-radius: 15px 50px 30px 5px;
      width: 200px; /* 图片宽度 */
      height: auto; /* 高度自动调整，保持比例 */
      }


    #text-here { /* 设立设置不动文本 */
  position: fixed; /* 固定位置 */
  color: red; /* 文本颜色为红色 */
  /* background-color: #99004d; /* 背景颜色 */
  /* text-shadow: 1px 3px 1px white; /* 文本阴影 */
  /* border: 6px solid black; /* 边框 */
  width: 300px; /* 宽度 */
  left: 300px; /* 距左边的距离 */
  top: 100px; /* 距顶部的距离 */
}

  #video1 {/* 这里编辑视频 */
    position: absolute;
    width: 30vw; /* 视频宽度占视口宽度的30% */
    border-radius: 30% 60% 15% 10%; /* 设置视频的圆角 */
    top: 15vh; /* 距顶部15%的视口高度 */
    left: 50vw; /* 距左边6%的视口宽度 */
  }

      #verticalText {
      writing-mode: vertical-rl; /* 文字从上到下排列 */
      text-orientation: mixed; /* 保持文字的正常方向 */
      white-space: nowrap; /* 防止文字换行 */
      border: 1px solid black; /* 可选：添加边框 */
      padding: 10px; /* 可选：增加内边距 */
      font-size: 24px; /* 设置字体大小 */
      color: blue; /* 设置文字颜色 */
      line-height: 1.5; /* 设置行高 */
      margin: 20px; /* 设置外边距 */

      /* 设置滑动文本 */
    #scrolling-text {
      position: absolute;
      top: 100px; /* 设置元素距其包含块顶部的距离 */
      left: 50px; /* 设置元素距其包含块左侧的距离 */
      color: blue;
      background-color: lightyellow;
      border: 1px solid black;
      padding: 10px;
      width: 200px;
    }

  /* 这里设置层级 数值越大越靠上 */

    #vedio1 {
    z-index: 10; /* 设置层级为10 */
  }

  #image-here {
    z-index: 1; /* 设置层级为5 */
  }

  #image-2 {
    z-index: 3; /* 设置层级为15 */
  }

    }
  </style>
</head>


<body>
  <!-- 这里添加标题 -->
  <h1>这里添加标题</h1>

    <!-- 这里添加不动文本体 -->
  <div id="text-here">这是一行不动的字</div>
    <!-- 这里添加图片 -->
  <img id="image-here" src="exploding-head_1f92f.png" alt="这里添加图片1">
  <img id="image-2" src="brain_1f9e0.png" alt="这里添加图片2">
    <!-- 这里添加视频 -->
    <video id="video1" controls>
  <source src="WeChat_20240805131051.mp4" type="video/mp4">
</video>
    <!-- 这里编辑竖排文本 -->
  <div id="verticalText">
    这是一个竖排文本的示例，你可以在这里写任何内容。竖排文字可以用于特别的设计效果。
  </div>
     <!-- 这里编辑滑动文本 -->
    <div id="scrolling-text">
    这个文本会随着页面滚动而移动位置。
  </div>


</body>
</html>
```
