# Liquid Handling Automation with Opentrons (OT2)

## Description

This repository contains tools designed for automating wellplate setup using the Opentrons Python Protocol API. 

The Jupyter Notebook (```automation_OT2.ipynb```) and the Python script (```simulate_automation_OT2.py```) seamlessly read protocol information from the Excel template file (```OT_Template.xlsx```).

### Files
1. ```automation_OT2.ipynb``` provides an interactive environment for setting up wellplates on the Opentrons OT2. This notebook guides you through the process, leveraging the capabilities of Opentrons for precise liquid handling.

2. ```simulate_automation_OT2.py```: A standalone script that simulates the wellplate setup process. It estimates the time required for the task and provides insights into the wellplate configuration. This is a useful tool for planning and optimizing your protocols.

3. ```OT_Template.xlsx```: Serves as a template for specifying protocol information which is parsed by the aforementioned python scripts. It includes fields for volumes, concentrations, labware, and other essential details. Use this template to organize and document your experiments efficiently.

## Getting Started

1. Clone the repository to your local machine:
```bash
git clone https://github.com/ASDSE/Liquid-Handling-Automation.git
```

2. Define your lab protocol:
- Open ```OT_Template.xlsx``` and fill in the required information for your lab protocol. This includes the labware details, stock concentrations and target concentrations. 
- Save the file for future reference and documentation.

3. Launch the robot's Jupyter Notebook by either:
   - Going to the **Advanced** tab of Robot Settings and clicking **Launch Jupyter Notebook**.
   - Going directly to ```http://<robot-ip>:48888``` in your web browser (if you know your robot’s IP address).
  
4. Upload your protocol excel file and  ```automation_OT2.ipynb```.

5. Follow the instructions in the notebook to set up your wellplates.

## Requirements
- Opentrons OT-2 and Python Protocol API v2
- Jupyter Notebook
- Python 3.x
