<h1>A Tale of Two Cities</h1>

<h2>Contextual Review of the 2018 - 2019 Premier League Title Race</h2>

Questions often lead to more questions. And sometimes we would like answers.

Further to an initial review of transfer activity by Liverpool and Manchester City, which can be viewed <a href= "https://mogwail.github.io/transfers.html">here<a/> , we obtained data for revenues which we find reliable.

For those interested in R code and additional analysis, the most current R Notebook(html) can be viewed <a href= "https://mogwail.github.io/LiverpoolFCvManchesterCityFC.html">here<a/>.

Data, R Notebooks and other files are available on github in the following repository: <a href= "https://github.com/MogwaiL/mogwail.github.io">MogwaiL<a/>

<h3>Revenues</h3>


<h4>Total Revenues</h4>

The total revenues declared for each club from the 2007/2008 season to the end of 2017/2018 season are as follows:


<html>
<head>
<meta charset="utf-8"/>
<script src="lib/htmlwidgets-1.3/htmlwidgets.js"></script>
<script src="lib/plotly-binding-4.9.0/plotly.js"></script>
<script src="lib/typedarray-0.1/typedarray.min.js"></script>
<script src="lib/jquery-1.11.3/jquery.min.js"></script>
<link href="lib/crosstalk-1.0.0/css/crosstalk.css" rel="stylesheet" />
<script src="lib/crosstalk-1.0.0/js/crosstalk.min.js"></script>
<link href="lib/plotly-htmlwidgets-css-1.46.1/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="lib/plotly-main-1.46.1/plotly-latest.min.js"></script>

</head>
<body style="background-color:white;">
<div align="center" style="display:inline-block">
  <div id="htmlwidget-6b7ef5c7c5a93d493d8d" style="width:100%;height:400px;" class="plotly html-widget"></div>
  <script type="application/json" data-for="htmlwidget-6b7ef5c7c5a93d493d8d">{"x":{"visdat":{"610044ac7d97":["function () ","plotlyVisDat"]},"cur_data":"610044ac7d97","attrs":{"610044ac7d97":{"labels":{},"values":{},"marker":{"colors":["#C8102E","#6CABDD"]},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"pie"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":"Total Revenue LFC v MCFC - 2007/2008 to 2017/2018 (£ Millions)","hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"labels":["Liverpool FC","Manchester City"],"values":[2790.3,2998.4],"marker":{"color":"rgba(31,119,180,1)","colors":["#C8102E","#6CABDD"],"line":{"color":"rgba(255,255,255,1)"}},"type":"pie","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</body>
</html>

What's £200 Million between friends? So, from the 2007/2008 season up to the 2017/2018 season, Manchester City officially recorded a smidgeon under £3 Billion in revenues while Liverpool recroded £2.79 Billion. One would not think this to be an astronomical advantage. But let's see how the numbers look over time.



<html>
<head>
<meta charset="utf-8"/>
<script src="lib/htmlwidgets-1.3/htmlwidgets.js"></script>
<script src="lib/plotly-binding-4.9.0/plotly.js"></script>
<script src="lib/typedarray-0.1/typedarray.min.js"></script>
<script src="lib/jquery-1.11.3/jquery.min.js"></script>
<link href="lib/crosstalk-1.0.0/css/crosstalk.css" rel="stylesheet" />
<script src="lib/crosstalk-1.0.0/js/crosstalk.min.js"></script>
<link href="lib/plotly-htmlwidgets-css-1.46.1/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="lib/plotly-main-1.46.1/plotly-latest.min.js"></script>

</head>
<body style="background-color:white;">
<div id="htmlwidget-bc69ef70f1b0cac469d0" style="width:100%;height:400px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-bc69ef70f1b0cac469d0">{"x":{"visdat":{"610031f7693a":["function () ","plotlyVisDat"]},"cur_data":"610031f7693a","attrs":{"610031f7693a":{"x":{},"y":{},"mode":"line","color":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"legend":{"x":0.05,"y":0.95},"title":"LFC & MCFC Annual Revenue","yaxis":{"domain":[0,1],"automargin":true,"title":"(£ Millions)"},"xaxis":{"domain":[0,1],"automargin":true,"title":"Season","type":"category","categoryorder":"array","categoryarray":["2007/2008","2008/2009","2009/2010","2010/2011","2011/2012","2012/2013","2013/2014","2014/2015","2015/2016","2016/2017","2017/2018"]},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[455.1,364.5,302,298.1,255.8,206.2,188.7,183.6,184.5,184.8,167],"mode":"line","type":"scatter","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"textfont":{"color":"rgba(200,16,46,1)"},"error_y":{"color":"rgba(200,16,46,1)"},"error_x":{"color":"rgba(200,16,46,1)"},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[503.5,453.5,392.6,352.6,346.5,271,231.1,153.2,125.1,87,82.3],"mode":"line","type":"scatter","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"textfont":{"color":"rgba(108,171,221,1)"},"error_y":{"color":"rgba(108,171,221,1)"},"error_x":{"color":"rgba(108,171,221,1)"},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</body>
</html>

This is an interesting graphic. Liverpool booked more revenue than Manchester City from the 2007/2008 season until 2010/2011 season. From 2011/2012 onwards, Manchester City has steadily outperformed Liverpool. Although, for 2017/2018 it appears Liverpool have shrunk the gap somewhat. Whether this becomes a future trend is impossible to say but worth watching. In any event, it is clear that over 11 seasons, the overall revenue for these two teams had a steep incline. No doubt this is a large reflection of the tv deals signed by the Premier League over the past decade.

We do not expect to see a striking visualization but let's check and see how each compares on the three major categories of revenue.


<html>
<head>
<meta charset="utf-8"/>
<script src="lib/htmlwidgets-1.3/htmlwidgets.js"></script>
<script src="lib/plotly-binding-4.9.0/plotly.js"></script>
<script src="lib/typedarray-0.1/typedarray.min.js"></script>
<script src="lib/jquery-1.11.3/jquery.min.js"></script>
<link href="lib/crosstalk-1.0.0/css/crosstalk.css" rel="stylesheet" />
<script src="lib/crosstalk-1.0.0/js/crosstalk.min.js"></script>
<link href="lib/plotly-htmlwidgets-css-1.46.1/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="lib/plotly-main-1.46.1/plotly-latest.min.js"></script>

</head>
<body style="background-color:white;">
<div id="htmlwidget-eb76b994a46299074997" style="width:100%;height:400px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-eb76b994a46299074997">{"x":{"data":[{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[81.2,68.8,56.8,57.1,51,44.6,45.2,40.9,42.9,42.5,39.2],"mode":"lines","showlegend":false,"type":"scatter","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"textfont":{"color":"rgba(200,16,46,1)"},"error_y":{"color":"rgba(200,16,46,1)"},"error_x":{"color":"rgba(200,16,46,1)"},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[56.6,51.9,52.5,43.4,47.5,39.6,30.8,26.6,24.4,20.8,18.5],"mode":"lines","showlegend":false,"type":"scatter","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"textfont":{"color":"rgba(108,171,221,1)"},"error_y":{"color":"rgba(108,171,221,1)"},"error_x":{"color":"rgba(108,171,221,1)"},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[222.6,156.8,125.7,124.6,101,63.9,63.3,65.3,79.5,74.6,76.3],"mode":"lines","showlegend":false,"type":"scatter","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"textfont":{"color":"rgba(200,16,46,1)"},"error_y":{"color":"rgba(200,16,46,1)"},"error_x":{"color":"rgba(200,16,46,1)"},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x2","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[211.5,203.5,161.4,135.4,133.2,88.4,88.2,68.8,54,48.2,43.3],"mode":"lines","showlegend":false,"type":"scatter","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"textfont":{"color":"rgba(108,171,221,1)"},"error_y":{"color":"rgba(108,171,221,1)"},"error_x":{"color":"rgba(108,171,221,1)"},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x2","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[151.3,138.9,119.5,116.4,103.8,97.7,80.2,77.4,62.1,67.7,51.5],"mode":"lines","type":"scatter","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"textfont":{"color":"rgba(200,16,46,1)"},"error_y":{"color":"rgba(200,16,46,1)"},"error_x":{"color":"rgba(200,16,46,1)"},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x3","yaxis":"y","frame":null},{"x":["2017/2018","2016/2017","2015/2016","2014/2015","2013/2014","2012/2013","2011/2012","2010/2011","2009/2010","2008/2009","2007/2008"],"y":[235.4,198.1,178.7,173.8,165.8,143,112.1,57.8,46.7,18,20.5],"mode":"lines","type":"scatter","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"textfont":{"color":"rgba(108,171,221,1)"},"error_y":{"color":"rgba(108,171,221,1)"},"error_x":{"color":"rgba(108,171,221,1)"},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x3","yaxis":"y","frame":null}],"layout":{"xaxis":{"domain":[0,0.313333333333333],"automargin":true,"type":"category","categoryorder":"array","categoryarray":["2007/2008","2008/2009","2009/2010","2010/2011","2011/2012","2012/2013","2013/2014","2014/2015","2015/2016","2016/2017","2017/2018"],"anchor":"y"},"xaxis2":{"domain":[0.353333333333333,0.646666666666667],"automargin":true,"type":"category","categoryorder":"array","categoryarray":["2007/2008","2008/2009","2009/2010","2010/2011","2011/2012","2012/2013","2013/2014","2014/2015","2015/2016","2016/2017","2017/2018"],"anchor":"y"},"xaxis3":{"domain":[0.686666666666667,1],"automargin":true,"type":"category","categoryorder":"array","categoryarray":["2007/2008","2008/2009","2009/2010","2010/2011","2011/2012","2012/2013","2013/2014","2014/2015","2015/2016","2016/2017","2017/2018"],"anchor":"y"},"yaxis":{"domain":[0,1],"automargin":true,"title":"(£ Millions)","anchor":"x"},"annotations":[{"x":0.0626666666666667,"y":0.95,"text":"Matchday","showarrow":false,"xref":"paper","yref":"paper"},{"x":0.470666666666667,"y":0.95,"text":"Broadcast","showarrow":false,"xref":"paper","yref":"paper"},{"x":0.874666666666667,"y":0.95,"text":"Commercial","showarrow":false,"xref":"paper","yref":"paper"}],"shapes":[],"images":[],"margin":{"b":40,"l":60,"t":25,"r":10},"hovermode":"closest","showlegend":true,"title":"LFC & MCFC Revenue Categories"},"attrs":{"55a4474c73b7":{"x":{},"y":{},"mode":"lines","showlegend":false,"color":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"},"55a41fa07a60":{"x":{},"y":{},"mode":"lines","showlegend":false,"color":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"},"55a426eb5c9a":{"x":{},"y":{},"mode":"lines","color":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"source":"A","config":{"showSendToCloud":false},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"subplot":true,"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</body>
</html>

That certainly tells a story.

1. Matchday revenue is less relied upon than broadcast or commercial. After some remodelling at Anfield, Liverpool has opened an advantage.
2. Broadcast revenue has seen huge growth and jumps can be seen every 3 years as new broadcast contracts are negotiated. Both teams are relatively even here with some fluctuation based on Champions League participation and other factors.
3. Commercial revenue is significantly disparate. The latest figures show Manchester City a whopping £84 Million ahead for 2017/2018. While Liverpool is also growing its commercial revenue, Manchester City have held this advantage for some time now.

One might suspect the club receives generous arrangements from sister companies within the family. However, we will have to see if this sort of data is available for review.
