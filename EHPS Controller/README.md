# UFTD_Portfolio
<h1 align="center">Electric-hydraulic power steering pump controller</h1>

<p align="left">Electric-hydraulic power steering pump controller. <br>Initially created for my car in order to use the full potential of the pump. It is built on the basis of ESP32. Configuration is performed via the website provided by ESP in access point mode. It includes a CAN transceiver, an optional bus terminator, and an input for an additional analog sensor. By default, the controller checks the current voltage of the car and whether the alternator is working properly (light), and simply will not start the pump if the voltage is too low or the engine is not running. Thresholds can be set via the settings page. The pump itself can be operated in two modes - manual and automatic. Manual mode determines the support power in the range of 0-100%. Automatic mode regulates the pump power depending on the vehicle speed read on the basis of impulses from the sensor in the gearbox.</p>

<div align="center">
  <img height="200" src="https://github.com/MayysterUFTD/UFTD_Portfolio/blob/main/EHPS%20Controller/IMG20240716121002.jpg"  />
</div>

###
###