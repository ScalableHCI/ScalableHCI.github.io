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

<style>
.image-container {
    position: relative;
    width: 100%;
    height: 500px; /* 根据你的图片和设计需求调整高度 */
    background-image: url('../assets/_RAY1729.jpg'); /* 根据你的图片路径调整 */
    background-size: cover;
    background-position: center;
}

.text-container {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: black; /* 根据你的设计需求调整文字颜色 */
}

.line1 {
    font-size: 2em;
    margin: 0;
}

.line2 {
    font-size: 1.5em;
    margin: 0;
}
</style>