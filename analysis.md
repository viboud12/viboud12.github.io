---
title: Image Analysis
layout: landing
description: ImageJ-based image analysis plugins for cell biologists
image: assets/images/analysis.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one" class="spotlights">
	<section>
		<a https://github.com/viboud12/Condensation_Assay class="image">
			<img src="assets/images/condensation.png" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Condensation Assay</h3>
				</header>
				<p>Originally developed by <a http://www.pnas.org/content/103/41/15097.abstract>Paul Maddox</a>, the condensation assay can be used to determine how much of a given cellular component is localized to a given structure. In its ImageJ format, the plugin first prompts the user to place a box over a given structure of interest in every frame in a time lapse movie, identifies the minimum and maximum intensity values in each box and thresholds fluorescence intensities within the identified dynamic range. This approach has been used to determine chromatin condensation state both during condensation and decondensation.</p>
				<ul class="actions">
					<li><a https://github.com/viboud12/Condensation_Assay class="button">Plugin</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a https://github.com/viboud12/CellMorph class="image">
			<img src="assets/images/CellMorph_figure.png" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>CellMorph</h3>
				</header>
				<p>Working with Mark Peifer's lab at UNC Chapel Hill, I made this ImageJ plugin to quickly measure cell size and shape in epithelial monolayers. Although this was developed to be used with images of cellularized fly embryos, this plugin could be applied to any monolayer stained for cell boundaries. Given the highly automated nature of this plugin, a version of the plugin is available to analyze entire folders of images. The analysis returns cell size information (area and perimeter) and cell shape information (circularity, aspect ratio, roundness, etc).</p>
				<ul class="actions">
					<li><a https://github.com/viboud12/CellMorph class="button">Plugin</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a https://github.com/viboud12/MeasureSpindles class="image">
			<img src="assets/images/spindle.png" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>MeasureSpindles</h3>
				</header>
				<p>Collaborating with Amy Byrnes in Kevin Slep's lab at UNC Chapel Hill, this plugin was inspired by <a https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4828689/>Rebecca Heald's lab's work</a> to automate measurements of mitotic spindle lengths and to extract spindle size and shape information out of existing data. The plugin segments spindles either based on a microtubule stain or on a microtubule stain in addition to a centrosomal stain. Once the spindle is segmented, the analysis provides several size and shape measurements including the feret's diameter, which measures the longest distance between two points in the object, as a measurement of spindle length.</p>
				<ul class="actions">
					<li><a https://github.com/viboud12/MeasureSpindles class="button">Plugin</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Sed amet aliquam</h2>
		</header>
		<p>
Methods/protocols/chapters
Ryan J., Gerhold A.R., Boudreau V., Smith L., Maddox P.S. (2017) Introduction to Modern Methods in Light Microscopy. In: Markaki Y., Harz H. (eds) Light Microscopy. Methods in Molecular Biology, vol 1563. Humana Press, New York, NY</p>
	</div>
</section>


</div>
