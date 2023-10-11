---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="image-container">
    <div class="text-container">
        <p class="line1">Scalable HCI Symposium</p>
        <p class="line2">2023</p>
    </div>
</div>

<div class="section-title">
    <h1 class="custom-h1">Date</h1>
    <p class="section-content">
    January 8 to January 12, 2024
    </p>
</div>

<div class="section-title">
    <h1 class="custom-h1">Introduction</h1>
    <p class="section-content">
    Field trips to Huaqiangbei, factories (e.g., PCB manufacturing company), and start-ups.<br>
    24 Hours Hackathon.<br>
    Cultural Exchange events.<br>     
    Poster Presentations by Students (MIT, KAIST, SUSTech, etc.).<br>
    Seminar Presentations by distinguished guests.<br>
    </p>
</div>

<div class="section-title">
    <h1 class="custom-h1">Program</h1>
    <p class="section-content">
    Field trips to Huaqiangbei, factories (e.g., PCB manufacturing company), and start-ups.<br>
    24 Hours Hackathon.<br>
    Cultural Exchange events.<br>  
    Poster Presentations by Students (MIT, KAIST, SUSTech, etc.).<br>
    Seminar Presentations by distinguished guests.<br>
    </p>
</div>

<div class="section-title">
    <h1 class="custom-h1">Organizer</h1>
    <p class="section-content">
    Seungwoo JE (SUSTech School of Design, Assistant Professor) <br>
    Xueliang Li (SUSTech School of Design, Assistant Professor)  <br>
    Pengcheng An (SUSTech School of Design, Assistant Professor) <br>
    Stefanie Mueller (MIT, Associate Professor)  <br>
    Cedric Honnet (MIT, PhD student) <br>
    Chang Hee Lee (KAIST, Assistant Professor)  <br>
    Tek-Jin Nam (KAIST, Professor) <br>
    </p>
</div>

<div class="section-title">
    <h1 class="custom-h1">Sponsor</h1>
    <p class="section-content">
    SUSTech School of Design, Seeed Studio / Chaihuo 
    </p>
</div>

<style>
.image-container {
    position: relative;
    width: 100%;
    height: 400px; /* 根据你的图片和设计需求调整高度 */
    background-image: url('assets/Background.jpg'); /* 根据你的图片路径调整 */
    background-size: cover;
    background-position: center;
}

.text-container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-align: center; /* 添加这行来水平居中文本 */
    width: 100%; /* 添加这行来确保文本容器宽度和图片一致 */
}

.line1 {
    font-size: 4em;
    margin: 0;
    front-weight: bold;
}

.line2 {
    font-size: 3em;
    margin: 0;
}

.custom-h1 {
    font-size: 2em; /* 或其他你需要的大小 */
    font-weight: bold; /* 使文本加粗 */
    color: #6f2316; /* 设置文本颜色为红色 */
    text-align: center; /* 居中文本 */
    margin: 0; /* 移除默认的边距 */
    padding: 10px 0; /* 可选：添加一些上下填充 */
}

/* 如果你想让每个标题在一个特定的区域或者容器中居中，你也可以使用 .section-title 类： */
.section-title {
    text-align: center; /* 这会使容器内的所有元素居中 */
}

.section-content {
    color: black; /* 设置文本颜色为黑色 */
    text-align: center; /* 居中文本 */
    margin: 0; /* 移除默认的边距 */
    padding: 10px 0; /* 可选：添加一些上下填充 */
    font-size: 1.5em; /* 设置字体大小，根据需要调整 */
}

</style>