# Open PLC Editor

## Installation

Download Open PLC Editor from https://autonomylogic.com/download/

## Creating New Project using Open PLC Editor

**ON-OFF Switch** program 

![image](/Images/Image-001.png)

<p style="text-align: center; font-weight: bold;">
  Open PLC Editor App interface
</p>

### To create new ladder logic program

- **File --->  New --->  Create New POU(Program Organization Unit)**

- Change **POU Name** and select **Programming language**

![image](/Images/Image-002.png)

## Rules 

## Example 1  ON-OFF switch

#### Create Location Address for **Input Contact** 

![image](/Software/media/001.gif)


#### Create Location Address for **Output Coil** 

![image](/Images/Image-003.png)

#### Ladder logic for **ON - OFF** Switch

- First add **Power Rail** ( Vertical power rails in a ladder logic diagram represent the electrical power supply)

![image](/Software/media/002.gif)

- Place **Input Contact**

![image](/Software/media/003.gif)

- Place **Output Coil** and close power rail.

![image](/Software/media/004.gif)

## Simulation

#### First **Generate Program for Open PLC Runtime**

![image](/Software/media/005.gif)

To Start **PLC Simulation**

![image](/Software/media/006_1.gif)
<p style="text-align: center; font-weight: bold;">
  Click on Run icon
</p>

![image](/Software/media/007.gif)

To verify the **OUTPUT** Right click  **Input contact** here we give force true value because some PLC programming software don't provide toggle switch function.
