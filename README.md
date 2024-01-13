# **ChromaTuneMl**
## A visual color gradient control system for adjusting parameters for ML LLMs.
### Here is a link to an article I wrote about the concept:<br>
<p> https://medium.com/@johnmsanti/swarming-towards-truth-adjusting-ml-and-llm-parameters-and-hyper-parameters-with-a-color-0e1b0bf638a7 </p>

## Functionality:
<p>The concept is to give the user the ability to adjust paramters for training ML models with 
  color gradient nodes which represent data points.</p>

## We own https://ChromaTuneML.com
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
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Now we can watch our progress in color overlayed on our model data</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- We can look at the outputs now and adjust the color of those
  outputs which are less desirable</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- That will automatically adjust the color position of the
  paramter node</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Once we have a satisfactory sample with colors aligned, 
  We can now judge the quality of our inputs
  <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;because we have resolved our parameters and 
  outputs based on those inputs: 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;((f(x)paramter_node)(input_data_point)) = (output)
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Because we can now judge the inputs of our data set, we can now identify outliars</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- This information allows us to quickly work through the rest of the data set. And when complete, adjusting the quality factor of the outputs will auto aggregate to the parameters. This inturn will aggregate to the inputs quality score (in a color gradient. Naw we have Ai run super fast tests of adjusting parameters for the entire model, checking the outputs and readjusting the quality color of outputs which trickle back through to parameters and inputs. its 430 am, that all ihave in me for today, i must revise and cleanup this last portion of code. 
