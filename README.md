
[v0.0.3](https://github.com/littleflute/blPicViewer/edit/master/README.md)


<br> 
<div id="divCurPic"></div> 
<br> 
<button onclick="show(1)">+1</button>

<button onclick="show(-1)">-1</button> <br>
<img id="myImg"   src="https://littleflute.github.io/b44/044/DSC_4726.JPG" > 
</img>  
<br>

<script>  
var vid = document.getElementById("myImg"); 
var n = 4726;
function show(i) {
    n += i;
    var s = "https://littleflute.github.io/b44/";
    s += "044/DSC_";
    s += n;
    s += ".JPG";
	  document.getElementById("divCurPic").innerHTML = s;  
    vid.src = s;
} 
</script> 



~~~html
<!DOCTYPE html>	  
<html>  
<body> 

<br> 
<div id="divCurPic"></div> 
<br> 

<img id="myImg" width="320" height="200" src="DSC_9535.jpg" > 
</img>  
<br>

<button onclick="show('000.jpg')">1:000.jpg</button> 
<a href="xdtest.html" onclick="show('999.jpg')">xdtest</a>  
<button onclick="show('DSC_9527.jpg')">3:DSC_9527.jpg</button> 
<button onclick="show('DSC_9528.jpg')">4:DSC_9528.jpg</button> 
<button onclick="show('DSC_9529.jpg')">5:DSC_9529.jpg</button> 
<button onclick="show('DSC_9530.jpg')">6:DSC_9530.jpg</button> 
<button onclick="show('DSC_9531.jpg')">7:DSC_9531.jpg</button> 
<button onclick="show('DSC_9532.jpg')">8:DSC_9532.jpg</button> 
<button onclick="show('DSC_9533.jpg')">9:DSC_9533.jpg</button> 
<button onclick="show('DSC_9534.jpg')">10:DSC_9534.jpg</button> 
<br> 
<button onclick="show('DSC_9535.jpg')">11:DSC_9535.jpg</button> 
<button onclick="show('DSC_9536.jpg')">12:DSC_9536.jpg</button> 
<button onclick="show('DSC_9537.jpg')">13:DSC_9537.jpg</button> 
<button onclick="show('DSC_9538.jpg')">14:DSC_9538.jpg</button> 
<button onclick="show('DSC_9539.jpg')">15:DSC_9539.jpg</button> 
<button onclick="show('DSC_9540.jpg')">16:DSC_9540.jpg</button> 
<button onclick="show('DSC_9541.jpg')">17:DSC_9541.jpg</button> 
<button onclick="show('DSC_9542.jpg')">18:DSC_9542.jpg</button> 
<button onclick="show('DSC_9543.jpg')">19:DSC_9543.jpg</button> 
<button onclick="show('DSC_9544.jpg')">20:DSC_9544.jpg</button> 
<br> 
<button onclick="show('DSC_9545.jpg')">21:DSC_9545.jpg</button> 
<button onclick="show('DSC_9546.jpg')">22:DSC_9546.jpg</button> 
<button onclick="show('DSC_9547.jpg')">23:DSC_9547.jpg</button> 
<button onclick="show('DSC_9548.jpg')">24:DSC_9548.jpg</button> 
<button onclick="show('DSC_9549.jpg')">25:DSC_9549.jpg</button> 
<button onclick="show('DSC_9550.jpg')">26:DSC_9550.jpg</button> 
<button onclick="show('DSC_9551.jpg')">27:DSC_9551.jpg</button> 
<button onclick="show('DSC_9552.jpg')">28:DSC_9552.jpg</button> 
<button onclick="show('DSC_9553.jpg')">29:DSC_9553.jpg</button> 
<button onclick="show('DSC_9554.jpg')">30:DSC_9554.jpg</button> 
<br> 
<button onclick="show('DSC_9555.jpg')">31:DSC_9555.jpg</button> 
<button onclick="show('DSC_9556.jpg')">32:DSC_9556.jpg</button> 
<button onclick="show('DSC_9557.jpg')">33:DSC_9557.jpg</button> 
<button onclick="show('DSC_9558.jpg')">34:DSC_9558.jpg</button> 
<button onclick="show('DSC_9559.jpg')">35:DSC_9559.jpg</button> 
<button onclick="show('DSC_9560.jpg')">36:DSC_9560.jpg</button> 
<button onclick="show('DSC_9561.jpg')">37:DSC_9561.jpg</button> 
<button onclick="show('DSC_9562.jpg')">38:DSC_9562.jpg</button> 
<button onclick="show('DSC_9563.jpg')">39:DSC_9563.jpg</button> 
<button onclick="show('DSC_9564.jpg')">40:DSC_9564.jpg</button> 
<br> 
<button onclick="show('DSC_9565.jpg')">41:DSC_9565.jpg</button> 
<button onclick="show('DSC_9566.jpg')">42:DSC_9566.jpg</button> 
<button onclick="show('DSC_9567.jpg')">43:DSC_9567.jpg</button> 
<button onclick="show('DSC_9568.jpg')">44:DSC_9568.jpg</button> 
<button onclick="show('DSC_9569.jpg')">45:DSC_9569.jpg</button> 
<button onclick="show('DSC_9570.jpg')">46:DSC_9570.jpg</button> 
<button onclick="show('DSC_9571.jpg')">47:DSC_9571.jpg</button> 
<button onclick="show('DSC_9572.jpg')">48:DSC_9572.jpg</button> 
<button onclick="show('DSC_9573.jpg')">49:DSC_9573.jpg</button> 
<button onclick="show('DSC_9574.jpg')">50:DSC_9574.jpg</button> 
<button onclick="show('DSC_9575.jpg')">51:DSC_9575.jpg</button> 
<button onclick="show('DSC_9576.jpg')">52:DSC_9576.jpg</button> 
<button onclick="show('DSC_9577.jpg')">53:DSC_9577.jpg</button> 
<button onclick="show('DSC_9578.jpg')">54:DSC_9578.jpg</button> 
<button onclick="show('DSC_9579.jpg')">55:DSC_9579.jpg</button> 
<button onclick="show('DSC_9580.jpg')">56:DSC_9580.jpg</button> 
<button onclick="show('DSC_9581.jpg')">57:DSC_9581.jpg</button> 
<button onclick="show('DSC_9582.jpg')">58:DSC_9582.jpg</button> 
<button onclick="show('DSC_9583.jpg')">59:DSC_9583.jpg</button> 
<button onclick="show('DSC_9584.jpg')">60:DSC_9584.jpg</button> 
<button onclick="show('DSC_9585.jpg')">61:DSC_9585.jpg</button> 
<button onclick="show('DSC_9586.jpg')">62:DSC_9586.jpg</button> 
<button onclick="show('DSC_9587.jpg')">63:DSC_9587.jpg</button> 
<button onclick="show('DSC_9588.jpg')">64:DSC_9588.jpg</button> 
<button onclick="show('DSC_9589.jpg')">65:DSC_9589.jpg</button> 
<button onclick="show('DSC_9590.jpg')">66:DSC_9590.jpg</button> 
<button onclick="show('DSC_9591.jpg')">67:DSC_9591.jpg</button> 
<button onclick="show('DSC_9592.jpg')">68:DSC_9592.jpg</button> 
<button onclick="show('DSC_9593.jpg')">69:DSC_9593.jpg</button> 
<button onclick="show('DSC_9594.jpg')">70:DSC_9594.jpg</button> 
<button onclick="show('DSC_9595.jpg')">71:DSC_9595.jpg</button> 
<button onclick="show('DSC_9596.jpg')">72:DSC_9596.jpg</button> 
<button onclick="show('DSC_9597.jpg')">73:DSC_9597.jpg</button> 
<button onclick="show('DSC_9598.jpg')">74:DSC_9598.jpg</button> 
<button onclick="show('DSC_9599.jpg')">75:DSC_9599.jpg</button> 
<button onclick="show('DSC_9600.jpg')">76:DSC_9600.jpg</button> 
<button onclick="show('DSC_9601.jpg')">77:DSC_9601.jpg</button> 
<button onclick="show('DSC_9602.jpg')">78:DSC_9602.jpg</button> 
<button onclick="show('DSC_9603.jpg')">79:DSC_9603.jpg</button> 
<button onclick="show('DSC_9604.jpg')">80:DSC_9604.jpg</button> 
<button onclick="show('DSC_9605.jpg')">81:DSC_9605.jpg</button> 
<button onclick="show('DSC_9606.jpg')">82:DSC_9606.jpg</button> 
<button onclick="show('DSC_9607.jpg')">83:DSC_9607.jpg</button> 
<button onclick="show('DSC_9608.jpg')">84:DSC_9608.jpg</button> 
<button onclick="show('DSC_9609.jpg')">85:DSC_9609.jpg</button> 
<button onclick="show('DSC_9610.jpg')">86:DSC_9610.jpg</button> 
<button onclick="show('DSC_9611.jpg')">87:DSC_9611.jpg</button> 
<button onclick="show('DSC_9612.jpg')">88:DSC_9612.jpg</button> 
<button onclick="show('DSC_9613.jpg')">89:DSC_9613.jpg</button> 
<button onclick="show('DSC_9614.jpg')">90:DSC_9614.jpg</button> 
<button onclick="show('DSC_9615.jpg')">91:DSC_9615.jpg</button> 
<button onclick="show('DSC_9616.jpg')">92:DSC_9616.jpg</button> 
<button onclick="show('DSC_9617.jpg')">93:DSC_9617.jpg</button> 
<button onclick="show('DSC_9618.jpg')">94:DSC_9618.jpg</button> 
<button onclick="show('DSC_9619.jpg')">95:DSC_9619.jpg</button> 
<button onclick="show('DSC_9620.jpg')">96:DSC_9620.jpg</button> 
<button onclick="show('DSC_9621.jpg')">97:DSC_9621.jpg</button> 
<button onclick="show('DSC_9622.jpg')">98:DSC_9622.jpg</button> 
<button onclick="show('DSC_9623.jpg')">99:DSC_9623.jpg</button> 
<button onclick="show('DSC_9624.jpg')">100:DSC_9624.jpg</button> 
<button onclick="show('DSC_9625.jpg')">101:DSC_9625.jpg</button> 
<button onclick="show('DSC_9626.jpg')">102:DSC_9626.jpg</button> 
<button onclick="show('DSC_9627.jpg')">103:DSC_9627.jpg</button> 
<button onclick="show('DSC_9628.jpg')">104:DSC_9628.jpg</button> 
<button onclick="show('DSC_9629.jpg')">105:DSC_9629.jpg</button> 
<button onclick="show('DSC_9630.jpg')">106:DSC_9630.jpg</button> 
<button onclick="show('DSC_9631.jpg')">107:DSC_9631.jpg</button> 
<button onclick="show('DSC_9632.jpg')">108:DSC_9632.jpg</button> 
<button onclick="show('DSC_9633.jpg')">109:DSC_9633.jpg</button> 
<button onclick="show('DSC_9634.jpg')">110:DSC_9634.jpg</button> 
<button onclick="show('DSC_9635.jpg')">111:DSC_9635.jpg</button> 
<button onclick="show('DSC_9636.jpg')">112:DSC_9636.jpg</button> 
<button onclick="show('DSC_9637.jpg')">113:DSC_9637.jpg</button> 
<button onclick="show('DSC_9638.jpg')">114:DSC_9638.jpg</button> 
<button onclick="show('DSC_9639.jpg')">115:DSC_9639.jpg</button> 
<button onclick="show('DSC_9640.jpg')">116:DSC_9640.jpg</button> 
<button onclick="show('DSC_9641.jpg')">117:DSC_9641.jpg</button> 
<button onclick="show('DSC_9642.jpg')">118:DSC_9642.jpg</button> 
<button onclick="show('DSC_9643.jpg')">119:DSC_9643.jpg</button> 
<button onclick="show('DSC_9644.jpg')">120:DSC_9644.jpg</button> 
<button onclick="show('DSC_9645.jpg')">121:DSC_9645.jpg</button> 
<button onclick="show('DSC_9646.jpg')">122:DSC_9646.jpg</button> 
<button onclick="show('DSC_9647.jpg')">123:DSC_9647.jpg</button> 
<button onclick="show('DSC_9648.jpg')">124:DSC_9648.jpg</button> 
<button onclick="show('DSC_9649.jpg')">125:DSC_9649.jpg</button> 
<button onclick="show('DSC_9650.jpg')">126:DSC_9650.jpg</button> 
<br> 

<script>  
var vid = document.getElementById("myImg"); 
function show(i) {
    vid.src=i;
	document.getElementById("divCurPic").innerHTML = i;  
} 
</script> 
</body> 

~~~


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/blPicViewer/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/blPicViewer/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
