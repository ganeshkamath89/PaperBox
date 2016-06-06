# PaperBox
Solving the Box City problem using Paper.js

Labelling problem with minimal line overlap for N cities depicted by points in a Box.

Step 1: Create a test dataset comprising of list of cities each having latitude, longitude, name and description

For example, i am using file from: http://www.downloadexcelfiles.com/wo_en/download-list-latitudelongitude-cities-india#.V07TVfl97IU

Step 2: Draw the cities as points

Step 3: Create a dummy layout function that randomly generates box shapes just outside the map (x, y, width, height)

. Map one box for each box render the name and description of the city.

. Connect the boxes (labels) to the cities via Straight lines

Step 4: Modify the layout to roughly miniize overlap and distance

+++++++++++++

Constraints:

. Avoid crossing over of lines

. Avoid overlap among labels

. All labels must have either consistent width or height (width - ones on the left and right; height - ones on the top and bottom)

Ensure that outer edges are alligned
. Reduce the number of labels if you want

Do it for first N non overlapping points
