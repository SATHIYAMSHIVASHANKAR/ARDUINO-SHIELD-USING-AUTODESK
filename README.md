# ARDUINO-SHIELD-USING-AUTODESK
DEVEOPING AN ARDUNIO SHIELD USING IC MAX7219 USING AUTODESK - EAGLE
***
step 1: In Autodesk Eagle, create a new project under the project sector. Name the file as Arduino Shield. Now under Arduino Shield create a Schematic file.
***
step 2: Allocate nessasary grid lines value in the grid section such that the editor page comes with the sutable grid lines
***
step 3: Using Add components tool, take the required parts and place it in the schematic with refernce to the circuit diagram. 
***
step 4: In order to reduce the complexcity in wire connection, introduce bus connection using Bus tool.
***
step 5: In Bus connection, it is mandatory to give Alias name and the Specification. Through this we can connet the Net (wire) conection at ease.
***
step 6: Now connect the components in the schematic using Net tool. 
***
step 7: Refer the data sheet to allocate the values to the components by using Value tool.
***
step 8 Its is mandatory to create a Net class for the ciruit made in Schematic. Create two net classes, name them as Power and MAX7219 NET and add the nessasary values to the Member section. Enter the respective terms to Default and Power sections.
***
step 9: To frame the entire circuit, select a Frame of your choice in Add components tool, place it around the circuit in schematic.
***
step 10: Now create a board, Delete the board lines which defaultly appears when creating the board. This is done because Arduino itself is a board, such that the components can be moved into the board (Arduino).
***
step 11: Move the components into the board and route the components using Air Routeing tool. The routing will be a bit complicated such that use both top as well as bottom layer for routing. Usage of Via tool is Mandatory to skip the part of intersection with wire.
***
step 12: Select Polygon tool and extend its strech to the entire board except Real Time Clock (rtc) and the Crystal component. Name it as Ground. Now by appling Ratsnest tool, the polygon (ground) gets activated.
***
step 13: Change the layer to Bottom. extend the Polygon all over the board, and to acitvate it apply Ratsnets tool as followed in step 12.
***
step 14: To give the name to board use Name tool. Enter the appropriate name and place it on the board with the Name Layer activated.
***
step 15: If required drill four holes in corner using Hole tool. By accessing Manufacturing tool we will get to know about the completed Audrino Board.
***
