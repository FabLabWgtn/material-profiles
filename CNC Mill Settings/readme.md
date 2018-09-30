Feed and speed settings from Vectric Vcarve9 & Fusion360  
For use with the Roland MDX-40A, Shopbot & MDX-540  

## Install Guide  


__Vcarve9 manual install - Windows 7/8/10__  
Locate your local tool database folder:   
`C:\ProgramData\Vetric\VCarve Pro\V9.0\ToolDatabase\`  
Save the [Mill Bits - Fab Lab Wgtn.tool](https://github.com/FabLabWgtn/material-profiles/blob/master/CNC%20Mill%20Settings/Mill%20Bits%20-%20Fab%20Lab%20Wgtn.tool?raw=true) in the ToolDatabase folder.  
Open VCarve and Import the new settings: `Toolpaths -> Tool Database -> Import`  

__Vcarve9 lab install - Windows 10__   
Download [Mill Bits - Fab Lab Wgtn.tool](https://github.com/FabLabWgtn/material-profiles/blob/master/CNC%20Mill%20Settings/Mill%20Bits%20-%20Fab%20Lab%20Wgtn.tool?raw=true)  
Move and rename to `C:\ProgramData\Vetric\VCarve Pro\V9.0\ToolDatabase\tools.tool_db`  
On login script checks to see if local git repo is up to date and re-runs as required.  

__Fusion360 manual install - Windows 10__  
Save the [Fusion360 - Fab Lab Wgtn.tools](https://github.com/FabLabWgtn/material-profiles/blob/master/CNC%20Mill%20Settings/Fusion360%20-%20Fab%20Lab%20Wgtn.tools?raw=true) library.  
Open Fusion360 and import the library: `Manage -> Tool Library -> Import tool library`    
