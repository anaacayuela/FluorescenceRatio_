# FluorescenceRatio_

The plugin helps you to obtain a ratio of the fluorescence intensity observed at a particular zone of the cell respect other areas. The plugin takes into account the amount of fluorescence spread in the different parts of the cell and the fuorescence apported by the background. To achive a correct installation and launching, you should download the one single JAR file [FluorescenceRatio_.jar](https://github.com/anaacayuela/FluorescenceRatio_/releases/download/1.0/FluorescenceRatio_.jar) and place it into the "plugins" folder of ImageJ/Fiji. For a better use of this plugin, you shall follow the next steps:

## •STEP 1. 
It is better to try to analyze the maximal projection of the image channel you select using ImageJ/Fiji -> ZProject... tool (ImageJ/Fiji -> Stacks -> ZProject... -> Max Intensity) althought this step is not essential, you can start analyzing whichever image type you desire. 

![stepf1](https://user-images.githubusercontent.com/54528366/65419677-7b819680-ddff-11e9-940d-df166a4be066.png)
![droppedImage](https://user-images.githubusercontent.com/54528366/65419572-3cebdc00-ddff-11e9-96d6-c4100de74715.jpg)

## •STEP 2.
Select Fuorescence Ratio plugin (ImageJ/Fiji ->Plugings -> Fuorescence Ratio) and then click “Initialize” button.

![stepf1](https://user-images.githubusercontent.com/54528366/65419802-c26f8c00-ddff-11e9-80c3-1602ac97e13b.png)
![stepf2 1](https://user-images.githubusercontent.com/54528366/65419937-1bd7bb00-de00-11e9-9cab-c1d721c3e6c4.png)

## •STEP 3. 
At this point, you should select the counter type. It is recommended to start with “Type Bg” counter to mark the background by clicking with the mouse several times over the image background (outside cell structure).

![stepf3](https://user-images.githubusercontent.com/54528366/65420050-796c0780-de00-11e9-8097-b5bf0b46fc60.png)
![stepf3 1](https://user-images.githubusercontent.com/54528366/65420002-4de91d00-de00-11e9-987f-f6bef94896de.jpg)

## •STEP 4.
Click “Type R1” counter to mark the area to analyze or measure. (*)IMPORTANT: the circles must be INSIDE the cell structure.

![stepf4](https://user-images.githubusercontent.com/54528366/65420217-e089bc00-de00-11e9-9ec1-ebb9b4a3975c.png)
![stepf5](https://user-images.githubusercontent.com/54528366/65420316-1e86e000-de01-11e9-9653-0f97288c21d2.jpg)

## •STEP 5.
Click “Type R2” counter to select the zone in the cell respect to which R1 will be compared.4

![stepfff5](https://user-images.githubusercontent.com/54528366/65420434-71f92e00-de01-11e9-8cf5-10a607fa647d.png)
![droppedImage_7](https://user-images.githubusercontent.com/54528366/65420480-8e956600-de01-11e9-8d4c-85b7c423fb45.jpg)

## •STEP 6.
Click “Measure Cell” button. In this step, you will obtain the ratio measure of the fluorescence signal in R1 zone respect to R2 area.

![stepf6](https://user-images.githubusercontent.com/54528366/65420618-eb911c00-de01-11e9-8653-48113a3971ad.png)
![droppedImage_9](https://user-images.githubusercontent.com/54528366/65420650-0368a000-de02-11e9-9b16-1ec800cb66b2.jpg)

## •STEP 7.
Repeat these previous steps as many measurements as you need. (The data will be saved by the program). Once you finish, click on “Final Measure” btton. The data corresponding to the “Ratio” from all measurements will appear in a new window called "Results" and they can be exported for further analysis.


Note: the size/area of the circles can be adjusted by using the “Larger” (bigger size) or “Smaller” (smaller size) buttoms. If you want to delete the last circle made, you should press on “Delete” button. Moreover, if you need to delete every circle made, you shall press on "Reset" button. 

