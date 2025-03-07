# ABAQUS Export Scripting

## Overview
This repository provides **Python scripts** for **automating post-processing in ABAQUS**. The scripts demonstrate how to **export results from ODB files**, including stress-strain data, contour plots, and animations. The automation improves efficiency in **finite element analysis (FEA)** workflows by eliminating manual extraction and enabling batch processing.

## Features
• Extract **stress-strain data** from selected elements  
• Automate **contour plot generation** for stress/strain fields  
• Save **result animations** for presentations and reports  
• Export data in **text format** for further post-processing in MATLAB or Python  
• Loop through multiple elements for batch processing  

## Requirements
To use these scripts, you need:  
• **ABAQUS** (Tested on ABAQUS 6.X and later)  
• **Python 2.7+** (ABAQUS' built-in Python interpreter)  
• **A text editor** with Python syntax highlighting (e.g., **Sublime Text, VS Code**)  

## Getting Started
1. Clone this repository:  
   ```sh
   git clone https://github.com/ArashJenab/ABAQUS-ODB-Export-Scripting.git
   cd ABAQUS-ODB-Export-Scripting
   ```
2. Open ABAQUS and navigate to **Run Script** in the menu.  
3. Load and execute `export_results.py`.  
4. Modify parameters such as **element selection**, **stress components**, or **animation settings** as needed.  

## Related Resources
🔹 **Part 1 of this Tutorial:** [https://youtu.be/a5hT9oSPJKQ](https://youtu.be/a5hT9oSPJKQ)  
🔹 **Part 2 of this Tutorial:** [https://youtu.be/v_dt2LDFOPY](https://youtu.be/v_dt2LDFOPY)  
🔹 **How to Link ABAQUS with MATLAB:** [https://www.youtube.com/watch?v=JqrUrbQ31iU](https://www.youtube.com/watch?v=JqrUrbQ31iU)  
🔹 **Simple Disk Compression Test Scripting Tutorial:** [https://www.youtube.com/watch?v=dKXgYoe3UPo](https://www.youtube.com/watch?v=dKXgYoe3UPo)  
🔹 **ABAQUS FEA Playlist:** [https://youtube.com/playlist?list=PLEY0rvSAS8TSKlZw1qO3t7euKSF3NfbVQ](https://youtube.com/playlist?list=PLEY0rvSAS8TSKlZw1qO3t7euKSF3NfbVQ)  

## Contact
For questions or discussions, feel free to reach out:  
**Website:** [www.arashjenab.com](http://www.arashjenab.com) | [www.jenab.ca](http://www.jenab.ca)  
**LinkedIn:** [/ajenab](https://ca.linkedin.com/in/ajenab/)  

## License
This repository is provided under the **MIT License** – feel free to use and modify it.
