---
title       : 大数据时代，放大创造力
subtitle    : 创造力研究展示
author      : 朱浚铭 Jeremy
job         : 商务分析
date        : 04/16/2016
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, shiny, interactive]
ext_widgets : {rCharts: [libraries/nvd3, libraries/highcharts]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## 目录

1. 大数据时代所需技能
2. 创造力的发现与重建
3. 相关研究结果展示

--- .class #id

## 大数据，所需技能

1. 批判性思维
2. 跨学科合作能力
3. 数据驱动的科研能力
4. 创造力！

批判性思维指的是通过一定的标准评价进而改善思维，是一种反思性的思维。通过对已有事物不断的质疑，研究，重新归纳以得到更完善的理论。这种思维方式在分析和解决问题时是不可或缺。

第二方面，需要跨学科合作能力。这个名字听起来更像是学术研究必备的技能，但是，其实并不是。跨学科合作能力发生在平时工作和生活的方方面面。简单的例子比如说，一个在公司做数据分析或统计分析的分析师也需要多了解市场营销等领域的专业知识，只有那样，在做统计分析时做出的假设，拟合的模型才能更好的具有实际意义。再比如说，在投资机构做行业分析的分析师一方面要非常了解公司估值，财务分析，二级市场等金融的知识，另一方面也需要对研究的行业有一定的了解，比如说新能源，锂电池行业或者是农业，畜牧业一定的了解。这具体取决于做的是什么行业的分析了。

第三，数据驱动的科研能力。这里所指的科研能力我认为是包含了提出问题，分析问题，解决问题等一系列的技能。我为什么要强调数据驱动呢？因为随着信息技术的不断突破，消费电子品的推陈出新，数据采集已经变得越来越方便与高效。相对应的数据分析与预测也变得前所未有的便捷。这些变化一方面给统计分析带来了诸多便捷，也带来了许多挑战，诸如伪相关，存储瓶颈，可扩展性等挑战。

第四，创造力。只有在自己的领域中，发挥创造力，才能不断的突破，不断的反思，优化，提出更多有用的工具与理论。

--- &radio

## 小调查

什么样的人创造力更高？

1. 男人
2. 女人
3. 工程师
4. 艺术家

*** .hint
创造力有很多种

*** .explanation
解释参考来自于上一页

--- 

## 发现创造力

创造力多样性：任何人都有创造力

<center>![Creative Diversity](figure/Jab.png =250x)

---
## 发现创造力

1. 不同创造力水平
2. 创造力类型
3. 动机
4. 机遇

- 通过四个关键变量衡量不同人之间创造力的区别：
- 创造力水平：你的潜力以及显示出的认知能力
- 创造力类型：你对于结构的认知倾向
- 动机：你如何引导你的能量
- 机遇：所具有的资源及你对其认知
- 这几个方面都是有价值的，只是不同的组合可能在特定处境下有更高的效率。


---
## 放大创造力

1. Wild Mind
2. Idea Journal
3. Intelligent Fast Failure

- IFF主要关注对创意、产品的快速建模，在快速并且聪明的建模过程中不断吸取信息和知识，从而对创意的应用，产品的设计提供更多有效的信息。

- 创造力与失败之间的关系一直是科学研究，业界应用所感兴趣的问题。许多学者对于失败是否对创造性成果的质和量有正向或负向的影响。关于这样的讨论，IFF就被提出来了。它可以作为一种学习工具，可以用来解密失败所扮演的角色。通过有精准计算与思考每次失误带来的后果，进而通过学习增加未来成功的几率。

- 拥有了批判性思维，在结合较强的执行力，我觉得就可以很好的执行后续研究将要探讨的IFF，通过带有智能的快速失败，以达到反思，自我修正，自我优化，最终走向成功。
- 通过构建创造力发现与激励社区，增强观点的交流，创造力将容易被发现与开拓
- 通过领导团队来推动创造力的开发
- 为创造力构建温床

---
## 统计分析结果展示

- 相关性

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---
## 统计分析结果展示

- 智能快速失败在男、女间的区别
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)

---
## Interactive Chart


<div id = 'chart1' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart1()
    });
    function drawchart1(){  
      var opts = {
 "dom": "chart1",
"width":    800,
"height":    400,
"x": "Hair",
"y": "Freq",
"group": "Eye",
"type": "multiBarChart",
"id": "chart1" 
},
        data = [
 {
 "Hair": "Black",
"Eye": "Brown",
"Sex": "Male",
"Freq":             32 
},
{
 "Hair": "Brown",
"Eye": "Brown",
"Sex": "Male",
"Freq":             53 
},
{
 "Hair": "Red",
"Eye": "Brown",
"Sex": "Male",
"Freq":             10 
},
{
 "Hair": "Blond",
"Eye": "Brown",
"Sex": "Male",
"Freq":              3 
},
{
 "Hair": "Black",
"Eye": "Blue",
"Sex": "Male",
"Freq":             11 
},
{
 "Hair": "Brown",
"Eye": "Blue",
"Sex": "Male",
"Freq":             50 
},
{
 "Hair": "Red",
"Eye": "Blue",
"Sex": "Male",
"Freq":             10 
},
{
 "Hair": "Blond",
"Eye": "Blue",
"Sex": "Male",
"Freq":             30 
},
{
 "Hair": "Black",
"Eye": "Hazel",
"Sex": "Male",
"Freq":             10 
},
{
 "Hair": "Brown",
"Eye": "Hazel",
"Sex": "Male",
"Freq":             25 
},
{
 "Hair": "Red",
"Eye": "Hazel",
"Sex": "Male",
"Freq":              7 
},
{
 "Hair": "Blond",
"Eye": "Hazel",
"Sex": "Male",
"Freq":              5 
},
{
 "Hair": "Black",
"Eye": "Green",
"Sex": "Male",
"Freq":              3 
},
{
 "Hair": "Brown",
"Eye": "Green",
"Sex": "Male",
"Freq":             15 
},
{
 "Hair": "Red",
"Eye": "Green",
"Sex": "Male",
"Freq":              7 
},
{
 "Hair": "Blond",
"Eye": "Green",
"Sex": "Male",
"Freq":              8 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

--- &interactive

## Interactive Console

<textarea class='interactive' id='interactive{{slide.num}}' data-cell='{{slide.num}}' data-results='asis' style='display:none'>require(googleVis)
M1 <- gvisMotionChart(Fruits, idvar = 'Fruit', timevar = 'Year')
print(M1, 'chart')</textarea>

---

## Interactive Chart with Shiny Controls

<div class="row-fluid">
  <div class="col-sm-4">
    <form class="well">
      <div class="form-group shiny-input-container">
        <label class="control-label" for="sex">Choose Sex</label>
        <div>
          <select id="sex"><option value="Male" selected>Male</option>
<option value="Female">Female</option></select>
          <script type="application/json" data-for="sex" data-nonempty="">{}</script>
        </div>
      </div>
      <div class="form-group shiny-input-container">
        <label class="control-label" for="type">Choose Type</label>
        <div>
          <select id="type"><option value="multiBarChart" selected>multiBarChart</option>
<option value="multiBarHorizontalChart">multiBarHorizontalChart</option></select>
          <script type="application/json" data-for="type" data-nonempty="">{}</script>
        </div>
      </div>
    </form>
  </div>
  <div class="col-sm-8">
    <div id="nvd3plot" class="shiny-html-output nvd3 rChart"></div>
  </div>
</div>

--- &interactive

## Interactive Console

<textarea class='interactive' id='interactive{{slide.num}}' data-cell='{{slide.num}}' data-results='asis' style='display:none'>require(rCharts)
a <- Highcharts$new()
a$chart(type = "spline")
a$series(data = c(1, 3, 2, 4, 5, 4, 6, 2, 3, 5, NA), dashStyle = "longdash")
a$series(data = c(NA, 4, 1, 3, 4, 2, 9, 1, 2, 3, 4), dashStyle = "shortdot")
a$legend(symbolWidth = 80)
a$print('chart3')</textarea>

--- &interactive

## Results = Markup

<textarea class='interactive' id='interactive{{slide.num}}' data-cell='{{slide.num}}' data-results='markup' style='display:none'>require(xtable)
options(xtable.type = 'html')
xtable(head(mtcars))</textarea>

--- &interactive

## Interactive economic 

<textarea class='interactive' id='interactive{{slide.num}}' data-cell='{{slide.num}}' data-results='markup' style='display:none'>data(economics, package = "ggplot2")
econ = transform(economics, date = as.character(date))
m1 = mPlot(x = "date", y = c("psavert", "uempmed"), type = "Line", data = econ)
m1$set(pointSize = 0, lineWidth = 1)
m1</textarea>

