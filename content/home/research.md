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


<div class="alert"> 
<p> <font size="+1.5"><b><span style="color: #00008B">Inference for unsupervised learning</span></b></font>: My more recent efforts focus on developing inferential methodologies for data-adaptive targets arising in various learning settings, including unsupervised learning. This line of work introduces novel inferential techniques for widely used exploratory tools such as [<a href="https://arxiv.org/abs/2402.16725">PCA</a>]  and [<a href="http://arxiv.org/abs/2512.06522">clustering</a>].
</p>

   
<details>
    <summary>Key papers:</summary>
    <ul class="publications-list">
        <li>Ronan Perry, <b><font color=#2B0539>Snigdha Panigrahi</font></b>, Jacob Bien, and Daniela Witten.
   <b> Inference on the proportion of variance explained in principal component analysis</b>. 2025. Journal of the American Statistical Association (Accepted). [<a href="https://arxiv.org/abs/2402.16725">link</a>]</li>
        <li>Di Wu, Jacob Bien and <b><font color=#2B0539>Snigdha Panigrahi</font></b>. <b> Hierarchical Clustering with Confidence </b>. 2025. [<a href="http://arxiv.org/abs/2512.06522">link</a>] </li>
     </ul>
</details>

</div> 


  
<div class="alert"> 
<p> <font size="+1.5"><b><span style="color: #00008B">Distribution-free selective inference</span></b></font>: This line of research expands the scope of selective inference beyond normal data. My [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-51/issue-6/Carving-model-free-inference/10.1214/23-AOS2318.short">work</a>] provides a first-of-its-kind theoretical basis for <b><span style="color: #00008B">data carving</span></b>, a new class of inferential methods that, like data splitting, uses a subset of the data for selection but, unlike splitting, utilizes the full dataset for selective (or post-selection) inference.
</p>

The proof techniques developed have advanced selective inference in semi- and nonparametric settings where it was previously unavailable, including, for example, [<a href="https://arxiv.org/abs/2411.15908">causal effect moderation</a>] and [<a href="https://arxiv.org/abs/2404.03059">quantile regression</a>].

   
<details>
    <summary>Key papers:</summary>
    <ul class="publications-list">
        <li><b><font color=#2B0539>Snigdha Panigrahi</font></b>.  <b>Carving model-free inference</b>. 2023.  Annals of Statistics. [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-51/issue-6/Carving-model-free-inference/10.1214/23-AOS2318.short">link</a>] </li>
        <li>Soham Bakshi, Walter Dempsey, and <b><font color=#2B0539>Snigdha Panigrahi</font></b>.  <b>Selective Inference for Time-varying Effect Moderation</b>. 2024+. [<a href="https://arxiv.org/abs/2411.15908">link</a>] </li>
        <li>Yumeng Wang, <b><font color=#2B0539>Snigdha Panigrahi</font></b>, and Xuming He.  <b> Asymptotically-exact selective inference for quantile regression</b>. 2025. Annals of Statistics (Accepted). [<a href="https://arxiv.org/abs/2404.03059">link</a>] </li>
    </ul>
</details>

</div> 


<div class="alert"> 
<p> <font size="+1.5"><b><span style="color: #00008B">Selective inference beyond polyhedral constraints</span></b></font>: This line of research develops a simple Gaussian randomization scheme that enables feasible inference for selection events that do not satisfy polyhedral constraints. By contrast, early work in the area, e.g.,  [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-44/issue-3/Exact-post-selection-inference-with-application-to-the-lasso/10.1214/15-AOS1371.full">Lee et al. (2016)</a>], rely on a polyhedral representation of the selection event.

These randomization techniques make selective inference feasible across a broad range of learning problems, including the selection of [<a href="https://www.jmlr.org/papers/volume24/21-1186/21-1186.pdf">groups of variables</a>] via group lasso–type penalties, models fitted through [<a href="https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-1/Selective-inference-for-sparse-multitask-regression-with-applications-in-neuroimaging/10.1214/23-AOAS1796.short">multi-task learning</a>], and dependence structure learned through [<a href="https://arxiv.org/pdf/2312.16734.pdf">graph- or network-analysis</a>].   

<details>
    <summary>Key papers:</summary>
    <ul class="publications-list">
        <li><b><font color=#2B0539>Snigdha Panigrahi</font></b>, Peter W. Macdonald, and Daniel Kessler. <b>Approximate Post-Selective Inference for Regression with
the Group LASSO</b>. 2023. Journal of Machine Learning Research. [<a href="https://www.jmlr.org/papers/volume24/21-1186/21-1186.pdf">link</a>] </li>
        <li><b><font color=#2B0539>Snigdha Panigrahi</font></b>, Natasha Stewart, Chandra Sripada, and Elizaveta Levina.
   <b>Selective Inference for Sparse Multitask Regression with Applications in Neuroimaging</b>. 2024.  Annals of Applied Statistics. [<a href="https://projecteuclid.org/journals/annals-of-applied-statistics/volume-18/issue-1/Selective-inference-for-sparse-multitask-regression-with-applications-in-neuroimaging/10.1214/23-AOAS1796.short">link</a>]</li>
        <li>Yiling Huang, <b> <font color=#2B0539>Snigdha Panigrahi</font></b>, and Walter Dempsey. <b>Selective Inference for Sparse Graphs via Neighborhood Selection</b>. 2025. Electronic Journal of Statistics.  [<a href="https://arxiv.org/pdf/2312.16734.pdf">link</a>] </li>
        <li>Sofia Guglielmini, Gerda Claeskens, and <b><font color=#2B0539>Snigdha Panigrahi</font></b>. <b> Selective Inference in Graphical Models via Maximum Likelihood</b>. 2025+. [<a href="https://arxiv.org/abs/2503.24311">link</a>]</li>
    </ul>
</details>

</div> 




<div class="alert"> 
<p> <font size="+1.5"><b><span style="color: #00008B">Tractable and powerful selective inference</span></b></font>: My work, under this theme, develops: (i) sampling methods, leveraging the benefits of a full [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-49/issue-5/Integrative-methods-for-post-selection-inference-under-convex-constraints/10.1214/21-AOS2057.short">Bayesian</a>]  machinery, (ii) probabilistic [<a href="https://www.tandfonline.com/doi/full/10.1080/01621459.2022.2081575">approximation</a>] techniques that rely on convex analysis and large deviation theory, (iii) [<a href="https://academic.oup.com/biomet/advance-article-abstract/doi/10.1093/biomet/asae019/7639974">exact</a>] methods by identifying an appropriate conditioning set. 

These advances have led to a general M-estimation framework for selective inference that accommodates both likelihood-based and more general models, as developed [<a href="https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-19/issue-2/Selective-inference-using-randomized-group-lasso-estimators-for-general-models/10.1214/25-EJS2416.pdf">here</a>].

<details>
    <summary>Key papers:</summary>
    <ul class="publications-list">
       <li><b><font color=#2B0539>Snigdha Panigrahi</font></b>,  Jonathan Taylor, and Asaf Weinstein.
    <b>Integrative methods for post-selection inference under convex constraints</b>. 2021. Annals of Statistics. [<a href="https://projecteuclid.org/journals/annals-of-statistics/volume-49/issue-5/Integrative-methods-for-post-selection-inference-under-convex-constraints/10.1214/21-AOS2057.short">link</a>]  </li>
        <li><b><font color=#2B0539>Snigdha Panigrahi</font></b> and Jonathan Taylor. <b> Approximate selective inference via maximum likelihood</b>. 2022. Journal of the American Statistical Association  [<a href="https://www.tandfonline.com/doi/full/10.1080/01621459.2022.2081575">link</a>]</li>
        <li> <b><font color=#2B0539>Snigdha Panigrahi</font></b>, Kevin Fry, and Jonathan Taylor.
   <b> Exact Selective Inference with Randomization</b>. 2024. Biometrika. [<a href="https://academic.oup.com/biomet/advance-article-abstract/doi/10.1093/biomet/asae019/7639974">link</a>] </li>
        <li>Yiling Huang, Sarah Pirenne, <b> <font color=#2B0539>Snigdha Panigrahi</font></b>, and Gerda Claeskens.
   <b>Selective Inference using Randomized Group Lasso Estimators for General Models</b>. 2025.  Electronic Journal of Statistics. [<a href="https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-19/issue-2/Selective-inference-using-randomized-group-lasso-estimators-for-general-models/10.1214/25-EJS2416.pdf">link</a>]</li>
    </ul>
</details>

</div> 



































