+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 25  # Order that this section will appear.

title = "**Research highlights**"
subtitle = ""

[design]

  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.

  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  gradient_start = "White"
  gradient_end = "Snow"

  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]

  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""

 # CSS class.
 css_class = ""

+++

<head>
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=yes">
<style>
.alert {
  padding: 20px;
  background-color: #B2EBF2;
  color: #091f29;
  }
  .closebtn {
  margin-left: 15px;
  color: white;
  font-weight: bold;
  float: right;
  font-size: 22px;
  line-height: 20px;
  cursor: pointer;
  transition: 0.3s;
}
.closebtn:hover {
  color: black;
}
</style>
</head>

<br>


<font size="+2"><b><span style="color: #00008B">Selective inference/ Post-selection inference</span></b></font>
  
 <div class="alert"> 
 <p>Selective inference offers a rigorous statistical framework for making honest inferences post selection. My recent and ongoing work focuses on developing flexible, tractable, and scalable methods of selective inference.
</p>


  <p>Most notably, methods have been developed that: (i) handle selection events that do not have a polyhedral shape or even straightforward descriptions; (ii) provide distribution-free inferences for different types of data, rather than relying on specific parametric models such as Gaussian models; (iii) yield easy-to-solve selective inferences in both a Bayesian and frequentist framework. </p>Click <a href="javascript:void(0)" onclick="document.getElementById('light').style.display='block';document.getElementById('fade').style.display='block'"><b><span style="color: #00008B">HERE</b></a> for some of the main <b><span style="color: #00008B">research highlights.
  </b>
  
</div> 


<div id="light" class="white_content">
  <br>
  <p><b><span style="color: #00008B"> Beyond polyhedral-shaped selection events</b>:  New methods of selective inference have been developed to address selection events that do not have a polyhedral shape or easy descriptions. These advancements have made it possible to perform selective inferences for problems involving the selection of [<a href="https://www.jmlr.org/papers/volume24/21-1186/21-1186.pdf">groups of variables</a>],  [<a href="https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-1/Selective-inference-for-sparse-multitask-regression-with-applications-in-neuroimaging/10.1214/23-AOAS1796.short">multi-task learning</a>],  [<a href="https://arxiv.org/pdf/2312.16734.pdf">graph learning</a>], and unsupervised learning such as [<a href="https://arxiv.org/abs/2402.16725">PCA</a>]. 
  </p>
  <br>
  
  <p><b><span style="color: #00008B"> Distribution-free inferences</b>: My work under this theme broadens the scope of selective inferences beyond normal data. This includes asymptotic properties of conditional methods for a [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-51/issue-6/Carving-model-free-inference/10.1214/23-AOS2318.short">nonparametric</a>] family of models, selective inferences for likelihood-based estimation problems using the [<a href="https://arxiv.org/pdf/2306.13829">GLMs</a>] and more general estimation problems such as quasi-likelihood estimation and [<a href="https://arxiv.org/pdf/2404.03059v1.pdf">quantile regression</a>].
  </p>
  <br>
  
   <p><b><span style="color: #00008B"> Tractable and scalable inferences</b>: My work develops: (i) sampling methods, leveraging the benefits of the  [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-49/issue-5/Integrative-methods-for-post-selection-inference-under-convex-constraints/10.1214/21-AOS2057.short">Bayesian</a>]  machinery, (ii) probabilistic [<a href="https://www.tandfonline.com/doi/full/10.1080/01621459.2022.2081575">approximation</a>] techniques that bypass sampling or resampling from data and instead rely on convex optimization techniques, (iii) [<a href="https://academic.oup.com/biomet/advance-article-abstract/doi/10.1093/biomet/asae019/7639974">exact</a>]  methods for polyhedral-shaped selection events.  
  </p>
  
   <a href="javascript:void(0)" onclick="document.getElementById('light').style.display='none';document.getElementById('fade').style.display='none'"><b><span style="color: #00008B"><u> CLOSE </u></b></a>
  </div>
  <div id="fade" class="black_overlay">
  </div>







<div style="clear: both;"></div>

<font size="+2"><b><span style="color: #00008B">Data aggregation and integration</span></b></font>
  
 <div class="alert"> 
 <p>
 My work utilizes new randomization-based tools for aggregating and integrating information from large datasets. This has led to the development of high-dimensional methods for drawing inferences from distributed data, conducting efficient meta-analyses, and inferring from models integrated over different modalities of information. 

</p>

<body>
 Click <a href="javascript:void(0)" onclick="document.getElementById('light0').style.display='block';document.getElementById('fade0').style.display='block'"><b><span style="color: #00008B">HERE</b></a> for some of the main <b><span style="color: #00008B">research highlights.</b>
</div>




<div id="light0" class="white_content0">
 <br>
 <p><b><span style="color: #00008B"> Large-scale estimation from data</b>:  My work enables the integration of low-dimensional summary statistics from many large datasets for [<a href="https://arxiv.org/abs/2203.12726">unbiased estimation</a>] and [<a href="https://arxiv.org/abs/2301.06162">large-scale inferences</a>].  Besides data aggregation, I also develop methods that allow for inferences in data-adaptive integrative models. These models combine various types of data, such as imaging and genomics, to model clinical outcomes in  [<a href="https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13740">cancer</a>] patients.
 </p>
  
 <a href="javascript:void(0)" onclick="document.getElementById('light0').style.display='none';document.getElementById('fade0').style.display='none'"><b><span style="color: #00008B"><u> CLOSE </u></b></a>
  </div>
  <div id="fade0" class="black_overlay0">
  </div>










<div style="clear: both;"></div>

<font size="+2"><b><span style="color: #00008B">Scientific applications</span></b></font>
  
 <div class="alert"> 
 <p>
My research finds applications in various scientific fields, specifically in the development of replicable inferential pipelines. This gives me an opportunity to collaborate with data scientists from diverse fields. 

</p>

<body>
Click <a href="javascript:void(0)" onclick="document.getElementById('light1').style.display='block';document.getElementById('fade1').style.display='block'"><b><span style="color: #00008B">HERE</b></a> to find some of the <b><span style="color: #00008B">practical applications</b> of my methodology in various domains. 
</div>


<div id="light1" class="white_content1">
 <br>
 <p><b><span style="color: #00008B"> Applications</b>:  The applications of my work have included analyzing data from [<a href="https://academic.oup.com/biostatistics/advance-article-abstract/doi/10.1093/biostatistics/kxz024/5532132?redirectedFrom=fulltext">genomics</a>], [<a href="https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13740">imaging</a>], [<a href="https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-1/Selective-inference-for-sparse-multitask-regression-with-applications-in-neuroimaging/10.1214/23-AOAS1796.short">neuroimaging</a>], and [<a href="https://arxiv.org/pdf/2312.16734.pdf">health trials</a>]. 
 </p>
  
  <p>
  Some of my current efforts are directed toward developing honest inferences and enabling reliable decision-making in mobile health trials. Additionally, I have an ongoing collaboration with the National Institutes of Health to understand malaria serology.
  </p>
  
 <a href="javascript:void(0)" onclick="document.getElementById('light1').style.display='none';document.getElementById('fade1').style.display='none'"><b><span style="color: #00008B"><u> CLOSE </u></b></a>
  </div>
  <div id="fade0" class="black_overlay0">
  </div>









<div style="clear: both;"></div>

<font size="+2"><b><span style="color: #00008B">Miscellaneous</span></b></font>
  
 <div class="alert"> 
 <p>
Some of my previous work in applied probability has studied the  [<a href="https://www.sciencedirect.com/science/article/pii/S0304414921000181?casa_token=GnUi_w_-Pq8AAAAA:1O3RvY6dA2Pg_o3Q7i2NjPC0svSrKOR7nG2hvOn3re0nNxkOCIc18hh2vur1m4SilWiKvBZx">path characteristics</a>] and [<a href="https://www.sciencedirect.com/science/article/abs/pii/S0304414918303314">integral geometric properties</a>] of random fields. In addition, I’ve worked on learning and structure estimation using [<a href="http://proceedings.mlr.press/v119/saeed20a/saeed20a.pdf">mixture models</a>].

</p>
</div>

































