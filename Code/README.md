# node-red

Files for the user-interface / electronics of the motorised system.

**node-red-flow.json** gives the entire 'flow' json for the user interface. Once Node-RED (https://nodered.org/) is installed,
the flow can be loaded by selecting `import` from the menu, and providing this `.json` file. 

This also requires the following nodes to be installed: 
  * node-red-dashboard (https://flows.nodered.org/node/node-red-dashboard), 
  * node-red-node-serialport (https://flows.nodered.org/node/node-red-node-serialport)
