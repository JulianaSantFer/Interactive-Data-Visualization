jjhj
hkehjrfrewf

https://julianasantfer.github.io/Interactive-Data-Visualization/graph1

Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@JulianaSantFer 
0
0 0 JulianaSantFer/Interactive-Data-Visualization
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Insights  Settings
Interactive-Data-Visualization/Chart.html
@JulianaSantFer JulianaSantFer Add files via upload
18a92c4 2 days ago
1340 lines (1323 sloc)  9.07 KB
    
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
  "https://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="https://www.w3.org/1999/xhtml">
<head>
<title>Cholestrol</title>
<meta http-equiv="content-type" content="text/html;charset=utf-8" />
<style type="text/css">
body {
  color: #444444;
  font-family: Arial,Helvetica,sans-serif;
  font-size: 75%;
  }
  a {
  color: #4D87C7;
  text-decoration: none;
}
</style>
</head>
<body>
 <!-- BarChart generated in R 3.5.1 by googleVis 0.6.3 package -->
<!-- Sun Apr 28 11:17:45 2019 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataCholestrol () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
233,
145
],
[
250,
130
],
[
204,
130
],
[
236,
120
],
[
354,
120
],
[
192,
140
],
[
294,
140
],
[
263,
120
],
[
199,
172
],
[
168,
150
],
[
239,
140
],
[
275,
130
],
[
266,
130
],
[
211,
110
],
[
283,
150
],
[
219,
120
],
[
340,
120
],
[
226,
150
],
[
247,
150
],
[
239,
140
],
[
234,
135
],
[
233,
130
],
[
226,
140
],
[
243,
150
],
[
199,
140
],
[
302,
160
],
[
212,
150
],
[
175,
110
],
[
417,
140
],
[
197,
130
],
[
198,
105
],
[
177,
120
],
[
219,
130
],
[
273,
125
],
[
213,
125
],
[
177,
142
],
[
304,
135
],
[
232,
150
],
[
269,
155
],
[
360,
160
],
[
308,
140
],
[
245,
130
],
[
208,
104
],
[
264,
130
],
[
321,
140
],
[
325,
120
],
[
235,
140
],
[
257,
138
],
[
216,
128
],
[
234,
138
],
[
256,
130
],
[
302,
120
],
[
231,
130
],
[
141,
108
],
[
252,
135
],
[
201,
134
],
[
222,
122
],
[
260,
115
],
[
182,
118
],
[
303,
128
],
[
265,
110
],
[
309,
108
],
[
186,
118
],
[
203,
135
],
[
211,
140
],
[
183,
138
],
[
222,
100
],
[
234,
130
],
[
220,
120
],
[
209,
124
],
[
258,
120
],
[
227,
94
],
[
204,
130
],
[
261,
140
],
[
213,
122
],
[
250,
135
],
[
245,
125
],
[
221,
140
],
[
205,
128
],
[
240,
105
],
[
250,
112
],
[
308,
128
],
[
318,
102
],
[
298,
152
],
[
265,
102
],
[
564,
115
],
[
277,
118
],
[
197,
101
],
[
214,
110
],
[
248,
100
],
[
255,
124
],
[
207,
132
],
[
223,
138
],
[
288,
132
],
[
160,
112
],
[
226,
142
],
[
394,
140
],
[
233,
108
],
[
315,
130
],
[
246,
130
],
[
244,
148
],
[
270,
178
],
[
195,
140
],
[
240,
120
],
[
196,
129
],
[
211,
120
],
[
234,
160
],
[
236,
138
],
[
244,
120
],
[
254,
110
],
[
325,
180
],
[
126,
150
],
[
313,
140
],
[
211,
110
],
[
262,
130
],
[
215,
120
],
[
214,
130
],
[
193,
120
],
[
204,
105
],
[
243,
138
],
[
303,
130
],
[
271,
138
],
[
268,
112
],
[
267,
108
],
[
199,
94
],
[
210,
118
],
[
204,
112
],
[
277,
152
],
[
196,
136
],
[
269,
120
],
[
201,
160
],
[
271,
134
],
[
295,
120
],
[
235,
110
],
[
306,
126
],
[
269,
130
],
[
178,
120
],
[
208,
128
],
[
201,
110
],
[
263,
128
],
[
295,
120
],
[
303,
115
],
[
209,
120
],
[
223,
106
],
[
197,
140
],
[
245,
156
],
[
242,
118
],
[
240,
150
],
[
226,
120
],
[
180,
130
],
[
228,
160
],
[
149,
112
],
[
227,
170
],
[
278,
146
],
[
220,
138
],
[
197,
130
],
[
253,
130
],
[
192,
122
],
[
220,
125
],
[
221,
130
],
[
240,
120
],
[
342,
132
],
[
157,
120
],
[
175,
138
],
[
175,
138
],
[
286,
160
],
[
229,
120
],
[
268,
140
],
[
254,
130
],
[
203,
140
],
[
256,
130
],
[
229,
110
],
[
284,
120
],
[
224,
132
],
[
206,
130
],
[
167,
110
],
[
230,
117
],
[
335,
140
],
[
177,
120
],
[
276,
150
],
[
353,
132
],
[
225,
150
],
[
330,
130
],
[
230,
112
],
[
243,
150
],
[
290,
112
],
[
253,
130
],
[
266,
124
],
[
233,
140
],
[
172,
110
],
[
305,
130
],
[
216,
128
],
[
188,
120
],
[
282,
145
],
[
185,
140
],
[
326,
170
],
[
231,
150
],
[
254,
125
],
[
267,
120
],
[
248,
110
],
[
197,
110
],
[
258,
125
],
[
270,
150
],
[
274,
180
],
[
164,
160
],
[
255,
128
],
[
239,
110
],
[
258,
150
],
[
188,
120
],
[
177,
140
],
[
229,
128
],
[
260,
120
],
[
219,
118
],
[
307,
145
],
[
249,
125
],
[
341,
132
],
[
263,
130
],
[
330,
130
],
[
254,
135
],
[
256,
130
],
[
407,
150
],
[
217,
140
],
[
282,
138
],
[
288,
200
],
[
239,
110
],
[
174,
145
],
[
281,
120
],
[
198,
120
],
[
288,
170
],
[
309,
125
],
[
243,
108
],
[
289,
165
],
[
289,
160
],
[
246,
120
],
[
322,
130
],
[
299,
140
],
[
300,
125
],
[
293,
140
],
[
304,
125
],
[
282,
126
],
[
269,
160
],
[
249,
174
],
[
212,
145
],
[
274,
152
],
[
184,
132
],
[
274,
124
],
[
409,
134
],
[
246,
160
],
[
283,
192
],
[
254,
140
],
[
298,
140
],
[
247,
132
],
[
294,
138
],
[
299,
100
],
[
273,
160
],
[
309,
142
],
[
259,
128
],
[
200,
144
],
[
244,
150
],
[
231,
120
],
[
228,
178
],
[
230,
112
],
[
282,
123
],
[
269,
108
],
[
206,
110
],
[
212,
112
],
[
327,
180
],
[
149,
118
],
[
286,
122
],
[
283,
130
],
[
249,
120
],
[
234,
134
],
[
237,
120
],
[
234,
100
],
[
275,
110
],
[
212,
125
],
[
218,
146
],
[
261,
124
],
[
319,
136
],
[
166,
138
],
[
315,
136
],
[
204,
128
],
[
218,
126
],
[
223,
152
],
[
207,
140
],
[
311,
140
],
[
204,
134
],
[
232,
154
],
[
335,
110
],
[
205,
128
],
[
203,
148
],
[
318,
114
],
[
225,
170
],
[
212,
152
],
[
169,
120
],
[
187,
140
],
[
197,
124
],
[
176,
164
],
[
241,
140
],
[
264,
110
],
[
193,
144
],
[
131,
130
],
[
236,
130
] 
];
data.addColumn('number','Cholestrol');
data.addColumn('number','RestingBPS');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartCholestrol() {
var data = gvisDataCholestrol();
var options = {};
options["allowHtml"] = true;
options["title"] = "Cholestrol x RestingBPS";
options["width"] = 600;
options["height"] = 400;
    chartCholestrol = new google.visualization.ChartWrapper({
    dataTable: data,       
    chartType: 'BarChart',
    containerId: 'Cholestrol',
    options: options
    });
    chartCholestrol.draw();
    
}
  function openEditorCholestrol() {
  var editor = new google.visualization.ChartEditor();
  google.visualization.events.addListener(editor, 'ok',
  function() { 
  chartCholestrol = editor.getChartWrapper();  
  chartCholestrol.draw(document.getElementById('Cholestrol')); 
  }); 
  editor.openDialog(chartCholestrol);
  }
    
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "charteditor";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartCholestrol);
})();
function displayChartCholestrol() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartCholestrol"></script>
 
<!-- divChart -->
<input type='button' onclick='openEditorCholestrol()' value='Edit this chart if you want!'/>  
<div id="Cholestrol" 
  style="width: 600; height: 400;">
</div>
 <div><span>Data: data &#8226; Chart ID: <a href="Chart_Cholestrol.html">Cholestrol</a> &#8226; <a href="https://github.com/mages/googleVis">googleVis-0.6.3</a></span><br /> 
<!-- htmlFooter -->
<span> 
  R version 3.5.1 (2018-07-02) 
  &#8226; <a href="https://developers.google.com/terms/">Google Terms of Use</a> &#8226; <a href="https://google-developers.appspot.com/chart/interactive/docs/gallery/barchart">Documentation and Data Policy</a>
</span></div>
</body>
</html>
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
