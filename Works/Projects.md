---
title: Projects
layout: landing
description: 'Works from personal, academic and professional areas'
image: assets/images/projects.png
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Academic Projects</h2>
		</header>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
    <section>
        <a href="Project_pages/pack_design.html" class="image">
            <img src="{% link assets/Project_files/Pack_design/sliders.JPG %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major" style="margin:0;">
                    <h3>Macro-scale Design Aspects of EV Battery Pack</h3>
                </header>
                <p><em>Summer research internship project</em></p>
                <ul>
                    <li>Performed preliminary battery pack design calculations by initially developing a system of equations in EXCEL and later implementing it in a MATLAB app for a better GUI experience.</li>
                </ul>
                <ul class="actions">
                    <li><a href="Project_pages/pack_design.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a href="Project_pages/battery.html" class="image">
            <img src="{% link assets/Project_files/Battery/Tap_temp_distri.png %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major" style="margin:0;">
                    <h3>Efficient Battery Thermal Management Systems for EV</h3>
                </header>
                <p><em>Final year B. Tech. thesis project</em></p>
                <ul>
                    <li>The project was aimed at improving the effectiveness of the battery thermal management system by reducing the cell capacity degradation caused due to temperature effects.</li>
                    <li>Link to the published paper : <a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/est2.458" target="_blank">Design of lithium-ion battery packs for two-wheeled electric vehicles</a></li>
                </ul>
                <ul class="actions">
                    <li><a href="Project_pages/battery.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a href="Project_pages/engine.html" class="image">
            <img src="{% link assets/Project_files/Engine_analysis/inline_engine.PNG %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major" style="margin:0;">
                    <h3>Balancing Aspects of Inline and V-engines</h3>
                </header>
                <p><em>Group semester project</em></p>
                <ul>
                    <li>Performed analysis and evaluation of unbalanced force present in inline (four cylinders) and V-2 engines using ANSYS software.</li>
                    <li>See project details here : <a href="../assets/Project_files/Engine_analysis/engine_report.pdf" target="_blank">report</a></li>
                </ul> 
                <ul class="actions">
                    <li><a href="Project_pages/engine.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <img src="{% link assets/Project_files/BE_lab_project_circuit.PNG %}" alt="" data-position="center center" class="image"/>
        <div class="content">
            <div class="inner">
                <header class="major" style="margin:0;">
                    <h3>Battery Voltage Level Indicator</h3>
                </header>
                <p><em>Basic electronics lab group project</em></p>
                <ul>
                    <li>Designed and implemented a circuit consisting of two op-amps (IC UA741), two LEDs, two resistors and
                    two potentiometers capable of detecting two voltage levels of any battery connected to the circuit by
                    turning on the two LEDs one after another. The op-amps were configured as comparator in the circuit. The two potentiometers can be adjusted to set any desired levels of voltage to be detected.</li>
                    <li>See project details here : <a href="../assets/Project_files/BE_lab_project_report.pdf" target="_blank">report</a></li>
                </ul>
            </div>
        </div>
    </section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Professional Projects</h2>
		</header>
	</div>
</section>

<!-- Four -->
<section id="four" class="spotlights">
    <section>
        <a href="Project_pages/thermal_calcs.html" class="image">
            <img src="{% link assets/Project_files/Thermal_calcs/film_temp.png %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Heat Exchanger Calculators</h3>
                </header>
                <p>A variety of EXCEL-based calculators for evaluating important process parameters. Used built-in GRG nonlinear solver and VBA for automated computations.</p>
                <ul class="actions">
                    <li><a href="Project_pages/thermal_calcs.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
</section>

<!-- Five -->
<section id="five">
	<div class="inner">
		<header class="major">
			<h2>Personal/Group Projects</h2>
		</header>
	</div>
</section>

<!-- Six -->
<section id="six" class="spotlights">
    <section>
        <a href="Project_pages/gas_sim.html" class="image">
            <img src="{% link assets/Project_files/Gas_sim/collisionless_gas.png %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Gas Dynamics Simulator</h3>
                </header>
                <p>Building an ideal gas simulation in MATLAB. Its WIP, check back later!</p>
                <ul class="actions">
                    <li><a href="Project_pages/gas_sim.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a href="Project_pages/balance_bot.html" class="image">
            <img src="{% link assets/Project_files/Balance_bot/final_bot_design.jpg %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Two-wheeled Self Balancing Robot</h3>
                </header>
                <p>Being one of the four members of the team involved in the project; developed the mechanical design of the robot and modelled it in SolidWorks software, evaluated system parameters such as principal moment of inertia and located the COG of the system in SolidWorks. Contributed in writing codes for simulating the system in Octave and helped in deriving state space equations for the system. <br> 
                Source code : <a href="https://github.com/RajShah-1/Balance-Bot" target="_blank">GitHub Repository</a></p> 
                <ul class="actions">
                    <li><a href="Project_pages/balance_bot.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a href="Project_pages/agro_bot.html" class="image">
            <img src="{% link assets/Project_files/Agro_bot/agrobot.JPG %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>Agro Bot</h3>
                </header>
                <p>Conceptual robot design for agricultural activities</p> 
                <ul class="actions">
                    <li><a href="Project_pages/agro_bot.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
    <section>
        <a href="Project_pages/ar_bot.html" class="image">
            <img src="{% link assets/Project_files/AR_robot/ARbot.PNG %}" alt="" data-position="center center" />
        </a>
        <div class="content">
            <div class="inner">
                <header class="major">
                    <h3>AR Robot</h3>
                </header>
                <p>Made a virtual robot in Unity3D controlled by ultrosonic sensor interfaced with Arduino Uno and keyboard keys</p> 
                <ul class="actions">
                    <li><a href="Project_pages/ar_bot.html" class="button">See more</a></li>
                </ul>
            </div>
        </div>
    </section>
</section>

<!-- Seven -->
<section id="seven">
    <div class="inner">
        <ul class="actions">
            <li><a href="/dhruvaljavia.github.io/" class="button">Go back</a></li>
        </ul>
    </div>
</section>

