---
layout: post
title: Two-wheeled Self Balancing Robot
description: null
image: null
nav-menu: false
show_tile: false
---

<div class="box">
    <h3>Abstract</h3>
	<p>The balance bot system is based on the classic inverted pendulum problem in the field of control engineering. The robot is characterised by its ability to balance on its two wheels and be manoeuvred with the help of a remote control. LQR (Linear Quadratic Regulator) is used as the controller to impart stability to the system.</p>
</div>

<div class="box">
    <h3>Technologies and Devices used to build the robot</h3>
    <h4><em>Technologies</em></h4>
    <ul>
    <li>LQR (Linear Quadratic Regulator) controller is implemented for controlling the system; which is inherently unstable but controllable. The controller gives a negative feedback to the system and tries to bring it to the specified setpoint, which here is bot’s balanced and steady vertical position.</li>
    <li>Complimentary filter for filtering out the noisy inclination readings from the gyroscope and accelerometer and then fusing them for achieving the best and near true values.</li>
    <li>Timer interrupts for coordinating various processes at the same rate.</li>
    <li>I2C and UART communication protocols</li>
    </ul>
    <h4><em>Devices</em></h4>
    <ul>
    <li>Arduino Mega microcontroller as the “brain” of the bot.</li>
    <li>GY87 IMU sensor containing a gyroscope and accelerometer to measure inclination of the bot. I2C communication protocol is implemented for its communication with the microcontroller.</li>
    <li>Xbee modules (TX & RX) for establishing communication between the bot and the remote. UART communication protocol is used for the same.</li>
    <li>DC geared motor is used along with a quadrature encoder to measure the speed and direction of rotation.</li>
    <li>L298D motor driver for controlling the speed and direction of the two motors.</li>
    </ul>
</div>

<h3>Bot & arena images, system testing video</h3>
<div class="box alt">
    <div class="row 50% uniform">
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Balance_bot/BalanceBot.jpg %}" alt="" /></span></div>
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Balance_bot/final_bot_design.jpg %}" alt="" /></span></div>
        <div class="4u$"><span class="image fit"><img src="{% link assets/Project_files/Balance_bot/BP_1452_Arena.png %}" alt="" /></span></div>
        <!-- Break -->
        <div class="4u"><span class="image fit"><img src="{% link assets/Project_files/Balance_bot/IMG_20201130_175530.jpg %}" alt="" /></span></div>
    </div>
</div>
<video width="320" height="240" controls preload="none"><source src="../../assets/Project_files/Balance_bot/testing.mp4" type="video/mp4"> Error playing video </video>
<br>
<ul class="actions">
    <li><a href="../Projects.html" class="button">Go back</a></li>
</ul>