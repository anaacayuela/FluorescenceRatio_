# FluorescenceRatio_

The plugin helps you to obtain a ratio of the fluorescence intensity observed at a particular zone of the cell respect other areas. The plugin takes into account the amount of fluorescence spread in the different parts of the cell and the fuorescence apported by the background. For a better use of this plugin, you shall follow the next steps:

•STEP 1. It is better to try to analyze the maximal projection of the image channel you select using ImageJ/Fiji -> ZProject... tool (ImageJ/Fiji -> Stacks -> ZProject... -> Max Intensity) althought this step is not essential, you can start analyzing whichever image type you desire. 

•STEP 2. Select Fuorescence Ratio plugin (ImageJ/Fiji ->Plugings -> Fuorescence Ratio) and then click “Initialize” button.

•STEP 3. At this point, you should select the counter type. It is recommended to start with “Type Bg” counter to mark the background by clicking with the mouse several times over the image background (outside cell structure).

•STEP 4. Click “Type R1” counter to mark the area to analyze or measure. (*)IMPORTANT: the circles must be INSIDE the cell structure.

•STEP 5. Click “Type R2” counter to select the zone in the cell respect to which R1 will be compared.

•STEP 6. Click “Measure Cell” button. In this step, you will obtain the ratio measure of the fluorescence signal in R1 zone respect to R2 area.

•STEP 7. Repeat these previous steps as many measurements as you need. (The data will be saved by the program). Once you finish, click on “Final Measure” btton. The data corresponding to the “Ratio” from all measurements will appear in a new window called "Results" and they can be exported for further analysis.


Note: the size/area of the circles can be adjusted by using the “Larger” (bigger size) or “Smaller” (smaller size) buttoms. If you want to delete the last circle made, you should press on “Delete” button. Moreover, if you need to delete every circle made, you shall press on "Reset" button. 

