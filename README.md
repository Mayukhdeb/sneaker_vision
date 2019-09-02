# sneaker_vision #
scrapes google images -> normalises them -> feeds into NN -> NN trains itself to classify 

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

