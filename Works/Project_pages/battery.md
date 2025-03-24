---
layout: post
title: Efficient Battery Thermal Management Systems for EV
description: null
image: null
nav-menu: false
show_tile: false
---


<div class="box">
    <h3>Abstract</h3>
	<p>Energy and power density constitute two main performance parameters of an electric
    vehicle battery pack, representing the range and acceleration of the vehicle. This project
    focuses on improving the energy density of the battery pack for better overall performance
    of the electric vehicles; two wheelers in particular. This is achieved by improving the
    effectiveness and efficiency of the battery thermal management system for reducing the
    cell capacity degradation caused by temperature effects. An air-cooled cylindrical battery
    pack is considered for this purpose and different cell arrangements and flow patterns are
    studied for reducing the temperature variation across the cells and also the peak cell
    temperature, for minimizing the extent of degradation during charge discharge process.
    The effect of cell pack configurations and type of coolant used is also studied. The
    degradation studies are done through numerical simulations. For this, a coupled 1-D
    electrochemical and 2-D/3-D thermal model of the battery pack is used for the numerical
    simulations. This is further coupled with a capacity fade model to account for cell capacity
    degradation.</p>
</div>

<div class="box">
    <h3>Objectives</h3>
    To numerically model and design a parallel cooled air-based thermal management
    system having the following characteristics:
    <ul>
    <li>Minimum peak pack temperature</li>
    <li>Minimum cell-to-cell temperature difference</li>
    <li>Low energy requirement</li>
    </ul>
    The model should also take into account the capacity fading phenomenon during
    charge-discharge cycles.
</div>

<div class="box">
    <h3>Methodology</h3>
    The numerical model of BTMS is set up in COMSOL Multiphysics
    software. The model consists of two parts : a 1-D model of cell for simulating
    the electrochemical process and a 2-D/3-D model of battery pack with casing representing
    the BTMS for simulating the thermal and fluid flow processes.
    The 1-D and 2-D/3-D models will be coupled together by means of average heat generation
    rate and maximum cell temperature. The 1-D model will simulate the charge-discharge
    process of a cell and will provide the volume-averaged cell internal heat generation time
    profile as an output result. This data will be used in the 2-D/3-D thermal model as an
    input for heat generation source in the cell for simulating the fluid flow and thermal heat
    exchange process. The output of the 2-D/3-D model will be the temperature distribution
    in the battery pack and it will be used to calculate the maximum temperature of all the
    cells constituting the pack. This maximum cell temperature value will then be used as
    an input for the 1-D electrochemical model. Maximum temperature is being used here to
    consider the worst-case scenario of battery pack life which will provide us with the minimum
    battery pack life, giving a lower bound value. Specifically, the 2-D model will be
    utilised to analyse different cell arrangements in a full scale battery pack. The 3-D model
    will be used to analyse the effect of heat generation in busbars on the pack performance,
    when the cells are connected in different configurations. Cell temperature can affect the
    capacity degradation and the discharge process of the cell, hence it is being given as an
    input to the 1-D model. By using this coupled model, different types of cell arrangements
    will be analysed for appropriate external inlet air conditions. The aim will be to minimise the cell capacity degradation
    rate by improving the airflow pattern and hence the heat dissipation rate.
</div>

<div class="box">
    <h3>Conclusion</h3>
    A battery pack made from 26650 type of Li-ion cell performs better than that made using 18650 or 21700
    cell type in terms of capacity degradation and charge-discharge cycle time period. By arranging the cells in tapered manner, lower capacity fading, maximum cell temperature and maximum cell-to-cell temperature difference is
    obtained which enhances the pack cycle life and the performance of BTMS.
</div>

<h3>Few of the Simulation Images</h3>
<div class="box alt">
    <div class="row 50% uniform">
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Battery/2D_pack_temp_diff_comp.png %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Battery/2D_press_diff_comp.png %}" alt="" /></span></div>
        <div class="4u$"><span class="image fit"><img src="{% link assets/Project_files/Battery/Tap_temp_distri.png %}" alt="" /></span></div>
        <!-- Break -->
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Battery/Tap_vel profile.png %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Battery/4P4S_mesh.png %}" alt="" /></span></div>
        <div class="4u$"><span class="image fit"><img src="{% link assets/Project_files/Battery/4P4S_temp_distribution.png %}" alt="" /></span></div>
    </div>
</div>