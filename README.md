<h1>Forecasting the Behavior of an Optic Fiber using ML and Telemetry Data</h1>

<h2>Description</h2>
This project focuses on the development of a regression model for one of the optic fibers used to measure stretching and shrinking of an observation balloon's fabric. The air force has been collecting data from the observation balloon for the past year and has accumulated two types of datasets: Telemetry and FBG. The Telemetry dataset includes general operational data such as height, pitch, roll, pressure, and temperature sensors. The FBG dataset contains data from four optic fibers that measure the load on a specific spot of the balloon, but due to classified reasons, further elaboration on the location cannot be provided.

The regression model developed in this project will use the Telemetry dataset to predict the behavior of one of the four optic fibers. The focus of the project is only on one fiber, as the four fibers have a high correlation, and it is reasonable to assume that they behave similarly.

The primary motivation for this study is to replace the function of the fibers using permanently attached sensors to the balloon. This will enable the fibers to be removed from their current location and attached to different areas on the balloon. By repeating this process multiple times, a regression model for the load on the balloon at each modeled point can be developed without any further need for the fibers.

Notice - The data is not classified, but it is partially censored due to its intellectual property belonging to the Air Force.
<br />

<p align="center">
<br/>
<img src="https://cdn.mos.cms.futurecdn.net/Roy7KHigvw8auXTPM8sztG.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
<h2>Languages and Utilities Used</h2>

- <b>Python</b>



