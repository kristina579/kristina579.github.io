---
layout: article
title:  "把可视化图嵌入网页里"
date:   2018-01-06
categories: posts_infovis
image:
  teaser: visual_5.jpg
  feature: visual_5.jpg
---
怎么把pubilic.tableau里面的图表嵌入网页里面

### 操作步骤

> 根据步骤一步步操作，记得最后的代码顺序不要乱更改，是一个包一个的。

> 最好是将几张工作表直接放在tableau的仪表板里，那样方便读者观看，并且减少放图步骤

1. 先登进去public.github.com，找到你要上传的视图
![image](https://kristina579.github.io/images/share.jpg)
2. 点击下方的分享链接，找到有embed code的那一串代码
![image](https://kristina579.github.io/images/load.jpg)
3. 复制下来，粘贴到你的notepad++上
4. 然后根据下面贴出的代码顺序进行修改

- <div class='tableauPlaceholder' id='viz1515242650823' style='position: relative'>
        <noscript><a href='#'><img alt='总计 '
		src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;4_&#47;4_540&#47;sheet3&#47;1_rss.png' style='border: none' /></a>
		</noscript>
		<object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='4_540&#47;sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;4_&#47;4_540&#47;sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' />
		</object>
</div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1515242650823');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>)

