
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>机器人之家</title>
<style>
  h1 {
    margin-top: 0; /* 设置标题上边距为0 */
  }
</style>
</head>
<body>
  <h2>热烈欢迎24级新同学</h2>

  <p>首先祝贺24级新同学进入机器人工程专业，开启人生的新篇章.</p>
  <p>机器人之家(zju-robotics)建立的初衷是提供一个分享资料、分享观点的专属浙江大学机器人工程专业的平台.</p>
  <p>希望机器人之家能对新同学老同学有所帮助. 欢迎新同学提出反馈，也欢迎大家加入贡献者的行列. 如果您有任何的反馈或是建议，请联系bclz19: chen.fang@zju.edu.cn </p>
  <p>如果这个网站在您的大学生活中起到一丝一毫的帮助，我们已感到不胜荣幸. <p></p>当然，尽信书则不如无书的道理无需多言，本站只是供您参考，真正精彩的大学旅途沿途的风光还将由您亲自去领略. 衷心祝愿您能够领略到我们所不曾领略的风景. </p>

  <h2>关于我们</h2>
  <p>这里是zju-robotics编写团队，我们来自浙江大学21，22，23级机器人工程.</p>

  <h2>致谢</h2>
  <p>在搭建机器人之家网站时，我们参考了<a href="https://zju-turing.github.io/TuringCourses/">图灵班学习指南</a>、<a href="http://csdiy.wiki">csdiy</a>以及本专业21级学长minifull参与撰写与维护的<a href="https://zjuers.com/welcome/">浙江大学本科新生指引</a>. 特此鸣谢.</p>
  <p>在网站搭建过程中，我们向许多学长学姐寻求了帮助，原谅这里不能一一列举.</p>


<font color="#B9B9B9">
  <p style="text-align: left; ">
      <span>本站已经运行</span>
      <span id='box1'></span>
</p>
  <div id="box1"></div>
  <script>
    function timingTime(){
      let start = '2024-8-14 00:00:00'
      let startTime = new Date(start).getTime()
      let currentTime = new Date().getTime()
      let difference = currentTime - startTime
      let m =  Math.floor(difference / (1000))
      let mm = m % 60  // 秒
      let f = Math.floor(m / 60)
      let ff = f % 60 // 分钟
      let s = Math.floor(f/ 60) // 小时
      let ss = s % 24
      let day = Math.floor(s  / 24 ) // 天数
      return day + "天" + ss + "时" + ff + "分" + mm +'秒'
    }
    setInterval(()=>{
      document.getElementById('box1').innerHTML = timingTime()
    },1000)
  </script>
  </font>

<span id="busuanzi_container_page_pv">本文总阅读量<span id="busuanzi_value_page_pv"></span>次</span>
<span id="busuanzi_container_site_uv">本站访客数<span id="busuanzi_value_site_uv"></span>人次</span>


</body>
</html>

