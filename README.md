# **ChromaTuneMl**
## A visual color gradient control system for adjusting parameters for ML LLMs.
### Here is a link to an article I wrote about the concept:<br>
<p> https://medium.com/@johnmsanti/swarming-towards-truth-adjusting-ml-and-llm-parameters-and-hyper-parameters-with-a-color-0e1b0bf638a7 </p>

## Functionality:
<p>The concept is to give the user the ability to adjust paramters for training ML models with 
  color gradient nodes which represent data points.</p>

### Possible feature:
<p>User establishes a baseline for color gradient and dynamics with a properly trained LLM
  with ChromaTuneMl running behind it.</p>

### Training a new model with the assistance of ChromaTuneMl:
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. The user adjusts parameter weights as usual with
  ChromaTuneMl running in the background.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Each each adjusment parameter for the LLM training
  is attached to a node which is adjustable in 8 directions in 3 dimentional space.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Each of the 8 directions can represent some "sub weight"
  for each parameter (depending on the type of metric for that parameter).</p>
<p><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This gives incredible control over each parameter, 
  and allows for multi dimentional algorithmic adjustment within each individual parameter 
  as oposed to linear analog +/-, as well as opens us up for Ai testing with algorithms
  which incorporate other parameter nodes.</p>

### Plain English:
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- We have a data set</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- We have parameters which adjust our outputs</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- We have outputs</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- As we adjust parameters, we get a different output.
  Either more or less correct/desirable/truthy.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Once we have performed many calculations CrhomaTuneMl 
  then designs a color gradient system for our parameter nodes</p>
