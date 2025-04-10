Laboratory Exercise #11
Exploring the Switching Behavior of a BJT Transistor

Objective: To investigate the switching characteristics of a Bipolar Junction Transistor (BJT) and understand how it can be used as an electronic switch. You will simulate a simple transistor switching circuit using Falstad's Circuit Simulator and document the findings using GitHub.

Materials:
Computer with internet access
Access to falstad.com/circuit
A GitHub account

Circuit Diagram:

![image](https://github.com/user-attachments/assets/6eea7608-5a31-482c-897b-7817678bdd82)



Procedure:

Part 1: Building the Switching Circuit

Open your web browser and navigate to falstad.com/circuit.

Delete the default circuit by selecting "File" -> "New"
Build the following circuit by dragging and dropping components from the left-hand menu: 
Voltage Source: Place a voltage source (Input) on the left side of the workspace. Set its voltage to 5V.

Resistor (Base Resistor - RB​): Place a resistor and connect it between the positive terminal of the voltage source and the base of the transistor. Set its resistance to 1kΩ.

NPN BJT: Place an NPN BJT. Connect its base to the resistor you just placed.

Resistor (Load Resistor - RC​): Place another resistor and connect it between the collector of the transistor and a new voltage source. Set its resistance to 100Ω.

Voltage Source (Collector Voltage - VCC​): Place another voltage source above the load resistor and connect its positive terminal to the resistor. Set its voltage to 5V. Connect the negative terminal of this voltage source to the negative terminal of the input voltage source (ground).

Ground: Place a ground symbol and connect it to the negative terminals of both voltage sources and the emitter of the transistor.

Indicator (LED - Optional but Recommended): Place an LED in series with the load resistor (RC​). Ensure the anode (triangle) of the LED is connected to the collector of the transistor (through RC​) and the cathode (flat line) is connected towards the VCC​ voltage source (through RC​). You might need to rotate the LED.

Part 2: Observing the Switching Action


Right-click on the base of the transistor and select "Show in Scope". Observe the waveform of the base voltage (VB​).

Similarly, observe the waveform of the collector voltage (VC​) and the base current (IB​) using the scope.

Part 3: Analyzing the Effect of Base Resistance
Stop the simulation.
Change the value of the base resistor (RB​) to 500Ω.
Run the simulation again.
Observe the waveforms of VB​, VC​, and IB​ using the scope.
Stop the simulation and change the value of the base resistor (RB​) to 2kΩ.
Run the simulation again and observe the state of the LED when the input voltage is 5V and 0V.
Observe the waveforms of VB​, VC​, and IB​ using the scope.

Submit using GitHub and NDTC Leap:
Create a new folder on your GitHub repository CPEA322 name it Laboratory Exercise 11
Inside this Folder, create a Markdown file (e.g., LabExercise11.md) and upload your Circuit Simulator File.
For each part of the procedure and for each question, document your findings in this LabExercise11.md file.
Include screenshots directly in your Markdown file to illustrate your circuit and the observed waveforms from the Falstad simulator. You can take screenshots using your operating system's tools and then drag and drop the image files into your report.md file in the GitHub editor, or use Markdown syntax to link to image files you upload.
Answer the following questions within your LabExercise11.md file, providing clear explanations and referencing your observations from the simulation and the screenshots.
Lastly, provide the GitHub link of your finished Laboratory Exercise 11 to the NDTC Leap.

Questions:
1. When the input voltage (Vin​) is 5V, what is the state of the transistor (ON or OFF)? Explain your observation based on the LED's state (if used) and the simulated collector voltage (VC​). Include a screenshot of the circuit and relevant voltage/current readings in this state. What is the approximate value of VC​ in this state?

2. When the input voltage (Vin​) is 0V, what is the state of the transistor (ON or OFF)? Explain your observation based on the LED's state (if used) and the simulated collector voltage (VC​). Include a screenshot of the circuit and relevant voltage/current readings in this state. What is the approximate value of VC​ in this state?


3. Sketch the waveforms of the base voltage (VB​) and the collector voltage (VC​) when the input voltage (Vin​) switches between 0V and 5V (draw one cycle). You can draw this on paper, take a picture, and include it in your report, or use a digital drawing tool and embed the image. Label the high and low voltage levels for both VB​ and VC​.

4. How does decreasing the base resistance (RB​) from 1kΩ to 500Ω affect the base current (IB​) when Vin​ is 5V? How does this change affect the collector voltage (VC​)? Include screenshots showing the relevant current and voltage readings for both RB​ values.

5. How does increasing the base resistance (RB​) from 1kΩ to 2kΩ affect the base current (IB​) when Vin​ is 5V? How does this change affect the collector voltage (VC​) and the state of the LED (if used)? Include screenshots showing the relevant current and voltage readings for both RB​ values.

6. Explain in your own words how a BJT can act as a switch in this circuit. What input condition turns the "switch" ON, and what input condition turns it OFF?

7. What is the purpose of the base resistor (RB​) in this switching circuit? What would happen if the base resistor was removed (replaced with a wire)? 


