# sneaker_vision #
scrapes google images -> normalises them -> feeds into NN -> NN trains itself to classify 

***improvements made in the current version***

* making folders like alpha and beta are not required anymore
* visualises the loss function going down through the training using matplotlib
* prevention of overtraining
* simple loop mechanism to classify multiple images one after the other 

***Instructions***
 
* In sneakernet_final_package.ipynb, run cell 1 and then cell 2 
* Enter the keywords, wait for it to scrape and process the images
* Enter the number of epochs (no. of times the CNN will have to go through the whole dataset) and wait for it to train
* After training, enter the path ( or name if in the same folder of the image to be classified 
(example - enter "pig.png") 

Side note - only supports .png files as of now because I'm too lazy to make it work on .jpg

>> HMU if you face any issue(s) / have any ideas to improve this project, or if you just want to tell me how it was.


***WARNING*** - this is still a work in progress 

#### web scraping :
  * working but still stuck on the issue where I cannot get more than 20 images at once
  * Will work on a possible solution thanks to @vchrombie

#### Normalising data :
  * Works fine, converts images to 100*100 size, you can tweak it to your fancy.    
  
#### sneakernet  :
  * Still a work in progress. The model is training but isn't the most optimized thning you'll see. And it's struggling with the small 200 image dataset provided. This model is made from scratch, hoping to make it better in the coming weeks.
  
### next objective :
  
  * Make the web scraping experience better by enter "google searches" instead of shoving in URLs copied from browsers into functions
  
  * optimize the CNN by tweaking the hyperparameters and experimenting between Adam and SGD optimizer
  
  
## Final vision  :
 * Will make a nicely arranged pack where the user would just enter two keywords like "sunflower" and "banana"
 And the scraper will download 2000 images of each category and normalise them.
 Then feed them to the CNN and train it. 
 
 * The model will then be able to classify between "sunflowers" and "bananas, 
 While the user did nothing but just type in the two categories to be classified between. 
 
 It's called sneakernet because I first thought of it while browsing nike's website

