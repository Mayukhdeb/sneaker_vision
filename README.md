# sneaker_vision #
scrapes google images -> normalises them -> feeds into NN -> NN trains itself to classify 

***WARNING*** - this is still a work in progress 

#### web scraping :
  * working but still stuck in the issue where I cannot get more than 20 images at once
  * Will work on a possible solution thanks to @vchrombie

#### Normalising data :
  * works fine, converts images to 100*100 size, you can tweak it to your fancy.    
  
#### sneakernet  :
  * still a work in progress. The model is training but isn't the most optimized thn=ing you'll see. And it's struggling with the small 200 image dataset provided. 
  
#### next objective :
  
  * make the web scraping experience better by enter "google searches" instead of shoving in URLs copied from browsers into functions
  
  * optimize the CNN by tweaking the hyperparameters and experimenting between Adam and SGD optimizer
  
  
## Final vision  :
 * Will make a nicely arranged pack where the user would just enter two keyowrds like "sunflower" and "banana"
 And the scraper will download 2000 images of each category and normalise them.
 Then feed them to the CNN and train it. 
 
 * The model will then be able to classify between "sunflowers" and "bananas, 
 While the user did nothing but just type in the two categories to be classified between. 
 
 its called sneakernet because I firth thought of it while brosing nike's website

