# MyCoCreation
co-creation 'draw with AI' scenario

## to do list
 - Modify findarea() over the bound of canvas
 - loading bar
 - make VAE model transtion
 - make <div> during sketchRNN operation
 
## p.draw()
{

 if{ //drawing
  if //draw prev strokes
  
  if //has_started
  else //draw new line
 }
 
 else{ //above the paper
  if //just_finished_line - simplify line, save to strokes, encode sketchRNN start
  
  if //draw prev strokes during sketchRNN operation
  
  if{ //make&draw sketchRNN model here
   if //after drawing model end, stroke to raw()
   else //draw m,odel line here
  }
 
 }
 
}
