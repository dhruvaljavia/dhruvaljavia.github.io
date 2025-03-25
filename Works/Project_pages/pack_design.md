---
layout: post
title: Macro-scale Design Aspects of EV Battery Pack
description: null
image: null
nav-menu: false
show_tile: false
---

<div class="box">
    <h3>Abstract</h3>
	<p>The performance of electric vehicles mainly depends on the performance of the battery. Hence, it becomes important to carefully design an EV battery pack and analyse its performance based on critical parameters such as vehicle range offered and heat generation. Further, some of the micro and macro parameters such as cell electrode thickness, active material particle size, cell voltage, cell capacity, cell weight, etc. can also be optimised to further improve the performance of a battery pack. Additionally, better thermal management systems can be devised to increase the life of the battery pack.
    In this project, literature review has been carried to understand various aspects of li-ion cell; it’s construction, working principle and manufacturing; and also, what are the principal subsystems associated with a battery pack installed in an EV and their basic functions and workings. Recent advances and developments concerning EV battery pack have also been reviewed. Thereafter, preliminary battery pack calculations have been performed by developing a system of design equations and implementing it in a MATLAB app for a better GUI experience. For obtaining performance data for different cell parameter values, a 1-D li-ion cell model was developed in COMSOL and its behaviour was observed by varying parameters such electrode thickness and active particle size, for a given current profile as input. A MATLAB code was written for creating the data for current profile and was then saved as an EXCEL file; which was later imported in the COMSOL cell model.</p>
</div>

<div class="box">
    <h3>Conclusion</h3>
    <p>Three different types of li-ion cell were used for calculating various vehicle and battery pack parameters. It was observed that 18650 cell type required the maximum no. of cells (300) while 26650 cell type the least (200). Although, it was seen that the battery pack weight was highest for 26650 (18.6 Kg) and for 18650 it was least (14.85 Kg). The pack heat generation for 26650 was the least (593.75 W), while for 18650 it was maximum (892.69 W). As far as vehicle range is concerned, it was almost same for the three types of cells; being 100.73 Km for 18650 and 99.53 Km for 26650 and 98.44 Km for 21700. The values of pack heat generation, total no. of cells required and pack weight for 21700 cell type was in between those of 18650 and 26650. Considering all these data, it can be concluded that 26650 is the most suitable cell type for constructing a battery pack.</p>
    <p> Also, from the MATLAB app developed using the design equations, the following trend in the results was observed by varying the parameter sliders provided in the app : </p>
    <span class="image fit"><img src="{% link assets/Project_files/Pack_design/MATLAB_app_results.PNG %}" alt=""/></span>
</div>

<h3>Some of the MATLAB app and EXCEL Screenshots</h3>
<div class="box alt">
    <div class="row 50% uniform">
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/EV_calc_screenshot.png %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/App_code_view.png %}" alt="" /></span></div>
        <div class="4u$"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/App_design_view.png %}" alt="" /></span></div>
        <!-- Break -->
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/app_compiler.JPG %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/app_in_action.JPG %}" alt="" /></span></div>
        <div class="4u$"><span class="image fit"><img src="{% link assets/Project_files/Pack_design/sliders.JPG %}" alt="" /></span></div>
    </div>
</div>

<ul class="actions">
    <li><a href="../Projects.html" class="button">Go back</a></li>
</ul>