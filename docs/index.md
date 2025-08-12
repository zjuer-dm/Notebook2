---
comments: true
nostatistics: true
hide:
  - navigation
  - toc
---

<script async src="https://www.googletagmanager.com/gtag/js?id=G-D2WBR8B2E1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js'， new Date());

  gtag('config'， 'G-D2WBR8B2E1');
</script>
<h1 style="font-family:arial;text-align:center;">Hi,这是繁星若尘(zjuer-dm)的笔记本^_^</h1>
<p style="font-family:arial;color:grey;font-size:20px;text-align:center;">Mens et Manus</p>
<p style="font-family:arial;color:grey;font-size:20px;text-align:center;">思想与行动</p>



现在，进入了新阶段的学习，用这个笔记，记录一下新的知识。




<script>
function updateTime() {
    var date = new Date();
    var now = date.getTime();
    var startDate = new Date("2025/06/25 12:00:00");
    var start = startDate.getTime();
    var diff = now - start;
    var y, d, h, m;
    y = Math.floor(diff / (365 * 24 * 3600 * 1000));
    diff -= y * 365 * 24 * 3600 * 1000;
    d = Math.floor(diff / (24 * 3600 * 1000));
    h = Math.floor(diff / (3600 * 1000) % 24);
    m = Math.floor(diff / (60 * 1000) % 60);
    if (y == 0) {
        document.getElementById("web-time").innerHTML = d + " 天 " + h + " 小时 " + m + " 分钟";
    } else {
        document.getElementById("web-time").innerHTML = y + " 年 " + d + " 天 " + h + " 小时 " + m + " 分钟";
    }
    setTimeout(updateTime, 1000 * 60);
}
updateTime();
function toggle_statistics() {
    var statistics = document.getElementById("statistics");
    if (statistics.style.opacity == 0) {
        statistics.style.opacity = 1;
    } else {
        statistics.style.opacity = 0;
    }
}
</script>