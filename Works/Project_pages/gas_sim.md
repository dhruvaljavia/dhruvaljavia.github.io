---
layout: post
title: Simulator details, demo video and interesting results
description: null
image: null
nav-menu: false
show_tile: false
---

<div class="box">
    <h3>Simulation Program Details</h3>
    <h4><u>Project Motivation</u></h4>
    <ul>
        <li>Develope a comprehensive and an optimized 2-D gas simulation program involving fluid dynamics and chemical reactivity simulation capabilities</li>
        <li>Provide a user-friendly testbed to easily experiment with different scenarios</li>
        <li>Independently tackle a particle dynamics problem from first principles by using the knowledge of basic collision physics, vector algebra and MATLAB scripting</li>
        <li>Validate various laws and theoretical results of physics such as ideal gas law and Boltzmann speed distribution using fundamental collision dynamics of gas particles</li>
    </ul>
    <h4><u>Key features of the simulation program</u></h4>
    <ul>
        <li>Accurate elastic collision physics simulation of inter-particle and particle-wall collisions</li>
        <li>Capable of simulating the effects of gravity, heat transfer and inter/intra-species associative chemical reactions for an isolated gas system</li>
        <li>Hash grid optimization implementation for reduced number of collision checks and low simulation times</li>
        <li>Region probing capability together with a wide range of post-processed output for better analysis and validation of results</li>
        <li>Intuitive and user-friendly graphical input for specifying the location of initial particle region and walls</li>
        <li>Animation video and plot image saving features</li>
    </ul>
    <h4><u>Performance comparison of hash grid based and brute force collision checking algorithms</u></h4>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/algo_perf_1.PNG %}" alt="" /></span></div>
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/algo_perf_2.PNG %}" alt="" /></span></div>
    </div>
    <ol>
        <li>These simulations are done considering a particle diameter of 2 Angstrom in a 120x120 Angstrom box with an initial speed of 0.5 Angstrom/fs. Total time taken is 1000 fs with a timestep of 1 fs.</li>
        <li>Consider an uncertainity of +/- 1 sec. in the simulation time observation values</li>
    </ol>
    <h4><u>Future planned updates</u></h4>
    <ul>
        <li>Add inter-particle interation via Lennard-Jones potential to simulate real gas</li>
        <li>Extend the dimensions from 2-D to 3-D</li>
        <li>Translate MATLAB code to GNU Octave equivalent code for open and easy access to all</li>
        <li>Add progress bar and animation video re-play features in the GUI</li>
    </ul>
    <a href="../../assets/Project_files/Gas_sim/Gas_Sim_Notes.pdf" target="_blank">Click here to see project notes</a>
</div>

<div class="box">
    <h3>Simulator MATLAB app demonstration</h3>
    <h5>Particle-in-box gas dynamics</h5>
    <div class="sp-embed-player" data-id="cTQnhsnohWC"><script src="https://go.screenpal.com/player/appearance/cTQnhsnohWC"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQnhsnohWC?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
    <br>
    <h5>Gas flow dynamics</h5>
    <div class="sp-embed-player" data-id="cTQn1Hno1Qa"><script src="https://go.screenpal.com/player/appearance/cTQn1Hno1Qa"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQn1Hno1Qa?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
</div>

<div class="box">
    <h3>Interesting Results</h3>
    <h4><u>Free expansion of an ideal gas in a vacuum chamber</u></h4>
    <div class="sp-embed-player" data-id="cTQnlanoiqk"><script src="https://go.screenpal.com/player/appearance/cTQnlanoiqk"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQnlanoiqk?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
    <br>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/top_wall_press_plot.png %}" alt="" /></span></div>
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/particle_speed_distribution.png %}" alt="" /></span></div>
    </div>
    <hr>
    <h4><u>Free expansion of an ideal gas through a hole</u></h4>
    <div class="sp-embed-player" data-id="cTQnIfnoiO6"><script src="https://go.screenpal.com/player/appearance/cTQnIfnoiO6"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQnIfnoiO6?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
    <br>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/pressure_EXP2.png %}" alt="" /></span></div>
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/conc_EXP2.png %}" alt="" /></span></div>
    </div>
    <hr>
    <h4><u>Chemical reaction of nascent oxygen atoms at 298 K</u></h4>
    <div class="sp-embed-player" data-id="cTQnIbnoiUB"><script src="https://go.screenpal.com/player/appearance/cTQnIbnoiUB"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQnIbnoiUB?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
    <br>
    <div class="row 50% uniform">
        <div class="6u"><span class="image fit"><img src="{% link assets/Project_files/Gas_sim/species_history.png %}" alt="" /></span></div>
    </div>
    <hr>
    <h4><u>Brownian motion of a particle suspended in gas</u></h4>
    <div class="sp-embed-player" data-id="cTQXhCnoaP3"><script src="https://go.screenpal.com/player/appearance/cTQXhCnoaP3"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQXhCnoaP3?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
    <hr>
    <h4><u>Bluff body flow of an ideal gas</u></h4>
    <div class="sp-embed-player" data-id="cTQnITnoiwp"><script src="https://go.screenpal.com/player/appearance/cTQnITnoiwp"></script><iframe width="100%" height="100%" style="border:0;" scrolling="no" src="https://go.screenpal.com/player/cTQnITnoiwp?width=100%&height=100%&ff=1&title=0" allowfullscreen="true"></iframe></div>
</div>
<br>
<ul class="actions">
    <li><a href="../Projects.html" class="button">Go back</a></li>
</ul>