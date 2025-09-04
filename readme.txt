design documents
 plan is to use qwen2 to get context from images, will have 5 different questioning prompt with seperate data, will also run a seperate object detection model over the images, and a seperate image to text reader

a central database will hold all images link, folder link, image link etc etc
image data will be loaded temporarily on memory

web server will be a flask application, main thing to run is the detection model get output and rank them
