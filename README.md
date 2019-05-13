# LFCvMCFC
A contextual review of the 2018 - 2019 Premier League title race

in 2017 - 2018, Manchester City won the title with 5 games to spare. During their run to last year's title, they set records for points (100), goals (106) and margin of victory (19 points).

To see the 2018 - 2019 season won by a single point was remarkable. Liverpool FC stayed neck and neck with Manchester City in 2018 2019 eventually finishing one point behind Manchester City (98 points vs 97 points). Liverpool are also playing in the Champions League final on June 1st, 2019.

We decided to take a look at what data we could find and build some situational awareness and context to the battle between Manchester City and Liverpool FC in 2018 - 2019. We chose to look at strategic data rather than tactical. Currently, transfer activity is available for analysis and we hope to include revenue and salary data. We firmly believe that professional managers, coaches, scouting departments and analysts are better equipped than we are to investigate tactical questions.

We also wanted to have some fun with the R programming language. Most analysis and graphics have been produced in R.

The most current R Notebook can be viewed <a href= "https://mogwail.github.io/LiverpoolFCvManchesterCityFC.html">here<a/> 


We decided to look at transfer data from 2008 until present. This is a slightly arbitrary period but our reasoning was; 2008 was the year Manchester City was bought by Abu Dhabi United Group Investment and Development Limited, bringing new investment to the club. It was also the year that Vincent Kompany was bought from Hamburg for £7 Million (which we shall see was some bargain); Mr. Kompany is the current captain of Manchester City.

To the meat of the question... how much money have these two teams spent on incoming transfers since 2008?

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
  <div id="htmlwidget-671cefa3c622042fd9a4" style="width:100%;height:400px;" class="plotly html-widget"></div>
  <script type="application/json" data-for="htmlwidget-671cefa3c622042fd9a4">{"x":{"visdat":{"37ac7f77b20":["function () ","plotlyVisDat"]},"cur_data":"37ac7f77b20","attrs":{"37ac7f77b20":{"labels":{},"values":{},"marker":{"colors":["#C8102E","#6CABDD"]},"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"pie"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":"Total Transfer Spend LFC v MCFC - 2008 to 2019 (£ Millions)","hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"labels":["LFC","MCFC"],"values":[900.95,1391.05],"marker":{"color":"rgba(31,119,180,1)","colors":["#C8102E","#6CABDD"],"line":{"color":"rgba(255,255,255,1)"}},"type":"pie","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</body>
</html>

Yup, quite a lot.

And in some context, Manchester City spent half as much again as Liverpool (£1.39 Billion vs £900 Million).

Looking at this deployment of financial resources over the timeline in question (2008 - 2019) is also informative.

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
  <div id="htmlwidget-f1791d6d667cc094e75f" style="width:100%;height:400px;" class="plotly html-widget"></div>
  <script type="application/json" data-for="htmlwidget-f1791d6d667cc094e75f">{"x":{"visdat":{"37ac37b414f8":["function () ","plotlyVisDat"]},"cur_data":"37ac37b414f8","attrs":{"37ac37b414f8":{"x":{},"y":{},"mode":"line","color":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"scatter"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"legend":{"x":0.05,"y":0.95},"title":"LFC & MCFC Annual Transfer Spending","yaxis":{"domain":[0,1],"automargin":true,"title":"Spent (£ Millions)"},"xaxis":{"domain":[0,1],"automargin":true,"title":"Year"},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"x":[2008,2009,2010,2011,2012,2013,2014,2015,2016,2017,2018],"y":[39,36,22.45,114.3,28.9,69.3,117,85,73,80,236],"mode":"line","type":"scatter","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"textfont":{"color":"rgba(200,16,46,1)"},"error_y":{"color":"rgba(200,16,46,1)"},"error_x":{"color":"rgba(200,16,46,1)"},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x","yaxis":"y","frame":null},{"x":[2008,2009,2010,2011,2012,2013,2014,2015,2016,2017,2018,2019],"y":[77.7,168,134.75,100,57,103.2,59.5,180,140.25,243.9,119.75,7],"mode":"line","type":"scatter","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"textfont":{"color":"rgba(108,171,221,1)"},"error_y":{"color":"rgba(108,171,221,1)"},"error_x":{"color":"rgba(108,171,221,1)"},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</body>
</html>



Age plot


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
  <div id="htmlwidget-ae4f867a38ff26cf698b" style="width:100%;height:400px;" class="plotly html-widget"></div>
  <script type="application/json" data-for="htmlwidget-ae4f867a38ff26cf698b">{"x":{"visdat":{"34b03a3358c3":["function () ","plotlyVisDat"]},"cur_data":"34b03a3358c3","attrs":{"34b03a3358c3":{"x":{},"y":{},"box":{"visible":true},"meanline":{"visible":true},"color":{},"split":{},"colors":["#C8102E","#6CABDD"],"alpha_stroke":1,"sizes":[10,100],"spans":[1,20],"type":"violin"}},"layout":{"margin":{"b":40,"l":60,"t":25,"r":10},"title":"LFC & MCFC Age Distribution of Transfer Targets","xaxis":{"domain":[0,1],"automargin":true,"title":"Club","type":"category","categoryorder":"array","categoryarray":["LFC","MCFC"]},"yaxis":{"domain":[0,1],"automargin":true,"title":"Age at Transfer","zeroline":false},"hovermode":"closest","showlegend":true},"source":"A","config":{"showSendToCloud":false},"data":[{"fillcolor":"rgba(200,16,46,0.5)","x":["LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC","LFC"],"y":[24.7041095890411,23.4027397260274,25.8109589041096,26.7753424657534,19.8328767123288,25.0602739726027,23.3780821917808,24.0602739726027,26.5041095890411,23.041095890411,24.9150684931507,24.241095890411,30.7424657534247,25.7123287671233,23.7616438356164,18.1178082191781,27.7780821917808,22.9534246575342,29.5068493150685,24.2547945205479,24.6493150684932,19.7452054794521,20.0657534246575,32.3917808219178,26.158904109589,20.3835616438356,25.0767123287671,19.2931506849315,22.1205479452055,24.0520547945205,20.8438356164384,20.7698630136986,25.9342465753425,32.3068493150685,25.3369863013699,20.5260273972603,23.5671232876712,21.3068493150685,22.4246575342466,24.0219178082192,18.2821917808219,23.3534246575342,20.6493150684932,16.0767123287671,21.0520547945205,25.572602739726,31.7123287671233,26.9972602739726,25.5643835616438,20.9123287671233,32.1561643835616,18.5013698630137,18.6191780821918,18.3534246575342,29.2219178082192,18.5232876712329,28.7123287671233,30.4739726027397,28.3041095890411,27.4712328767123,29.2328767123288,16.6246575342466,15.2849315068493,24.0356164383562,22.0821917808219,24.8712328767123,18.1287671232877,16.3945205479452,25.1013698630137,30.0986301369863,29.0493150684932,25.3917808219178,26.8301369863014,25.6,28.0739726027397,18.5397260273973,26.4,19.3260273972603],"box":{"visible":true},"meanline":{"visible":true},"type":"violin","name":"LFC","marker":{"color":"rgba(200,16,46,1)","line":{"color":"rgba(200,16,46,1)"}},"line":{"color":"rgba(200,16,46,1)"},"xaxis":"x","yaxis":"y","frame":null},{"fillcolor":"rgba(108,171,221,0.5)","x":["MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC","MCFC"],"y":[27.4,21.4821917808219,18.0109589041096,19.6082191780822,24.2849315068493,23.8876712328767,22.9068493150685,19.1972602739726,27.1479452054795,26.041095890411,23.0356164383562,23.6958904109589,21.2082191780822,24.2931506849315,25.7041095890411,25.8109589041096,29.7315068493151,20.5534246575342,20.572602739726,19.7616438356164,19.8876712328767,22.2164383561644,33.3917808219178,18.1671232876712,20.6109589041096,18.4602739726027,25.6630136986301,27.5369863013699,24.1890410958904,23.3095890410959,31.3972602739726,26.9534246575342,32.7972602739726,21.2602739726027,23.5068493150685,26.1123287671233,27.627397260274,28.1780821917808,27.9260273972603,23.7260273972603,15.7643835616438,32.7205479452055,21.4383561643836,23.4520547945205,19.441095890411,31.1205479452055,34.8438356164384,25.5780821917808,16.7232876712329,20.5041095890411,25.9561643835616,23.1671232876712,25.013698630137,24.1780821917808,30.6301369863014,20.2246575342466,21.8383561643836,16.3835616438356,27.1561643835616,24.5287671232877,24.7178082191781,20.013698630137,24.6328767123288,24.827397260274,28.3698630136986,27.8931506849315,22.2520547945205,28.6082191780822,25.4547945205479,25.4082191780822,28.3780821917808,35.3287671232877,27.0438356164384,33.5643835616438,22.5698630136986,21.3808219178082,26.3506849315068,22.3835616438356,26.786301369863,25.0904109589041,23.6383561643836,24.6191780821918,28.4301369863014,29.5424657534247,24.158904109589,32.8082191780822],"box":{"visible":true},"meanline":{"visible":true},"type":"violin","name":"MCFC","marker":{"color":"rgba(108,171,221,1)","line":{"color":"rgba(108,171,221,1)"}},"line":{"color":"rgba(108,171,221,1)"},"xaxis":"x","yaxis":"y","frame":null}],"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>
</div>
</body>
</html>
© 2019 GitHub, Inc.
