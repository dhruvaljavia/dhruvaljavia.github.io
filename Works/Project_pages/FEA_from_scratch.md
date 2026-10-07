---
layout: post
title: Project details & progress update
description: null
image: null
nav-menu: false
show_tile: false
---

<div class="box">
    <h4><u>Primary Project Objectives</u></h4>
    <ul>
        <li>Develope a comprehensive and an optimized FEA program for heat transfer simulations in MATLAB from scratch; allowing conduction, convection and thermal expansion analysis in solids interacting with a chemically reacting/inert gas mixture as a heat source</li>
        <li>Validate the MATLAB model experimentally via a custom 3D printed test rig having IR temperature sensor and laser-cut Aluminum plate, using LabVIEW for data acquisition</li>
        <li>Benchmark the performance of MATLAB model against COMSOL Multiphysics simulations</li>  
        <li>Use Projection-based Model Order Reduction technique to optimize MATLAB model</li>
        <li>Perform topology/shape/parametric optimization of plate geometry to enhance heat transfer rates</li>
    </ul>
    <h4><u>Secondary Project Objectives</u></h4>
    <ul>
        <li>Try using the developed MATLAB program to simulate and analyse a complex system, such as a brick stack in a thermal energy storage system</li>
    </ul>
    <a href="../../assets/Project_files/FEA_from_scratch/FEA_sim_notes.pdf" target="_blank">Click here to see project notes</a>
</div>

<div class="box">
    <h3>Some encouraging results so far</h3>
    <h4>Temperature distribution in Al 5052 plate using MATLAB program (left), and comparing it against COMSOL result (right)</h4>
    <ul>
        <li>Initial temperature of plate is 25 degC, and convective cooling occurs in the bottom region of plate with a heat transfer coefficient of 50 W/m2/K and a constant cooling medium temperature of 0 degC</li>
        <li>Temperature distribution is shown at 180 sec., calculating it by considering a timestep of 5 sec. using implicit Euler method</li>
        <li>Relative error in the temperature values at the two corners obtained using MATLAB and COMSOL is less than 5%</li>
    </ul>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/FEA_from_scratch/temp_dist.png %}" alt="" /></span></div>
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/FEA_from_scratch/comsol_validation.PNG %}" alt="" /></span></div>
    </div>
    <br>
    <br>
    <h4>Edge labelling the plate geometry (for specifying boundary conditions)(left), and a mesh showing nodes subjected to convective cooling (right)</h4>
    <ul>
        <li>CAD model of plate is made in Onshape and imported in MATLAB as an STL file</li>
        <li>The region of convective cooling represents the conditions in the test rig</li>
    </ul>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/FEA_from_scratch/edge_labels.png %}" alt="" /></span></div>
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/FEA_from_scratch/mesh.png %}" alt="" /></span></div>
    </div>
</div>

<div class="box">
    <h3>Simulation Animation and Test Rig Setup</h3>
    <h4>Cooling of a metal plate immersed partially in a cold bath</h4>
    <div class="sp-embed-player" data-id="cO6i10nxdP3" data-aspect-ratio="1.865854" data-padding-top="53.594771%" style="position:relative;width:100%;padding-top:53.594771%;height:0;"><script src="https://go.screenpal.com/consumption/player_appearance/cO6i10nxdP3/1.865854"></script><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;"  scrolling="no" src="https://go.screenpal.com/player/cO6i10nxdP3?ff=1&ahc=1&dcc=1&tl=1&bg=transparent&share=1&download=1&embed=1&cl=1" allow="fullscreen *;" allowfullscreen></iframe></div>
    <br>
    <h4>Test Rig</h4>
    <div class="row 100% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/FEA_from_scratch/test_rig.jpg %}" alt="" /></span></div>
    </div>
</div>
<br>
<ul class="actions">
    <li><a href="../Projects.html" class="button">Go back</a></li>
</ul>