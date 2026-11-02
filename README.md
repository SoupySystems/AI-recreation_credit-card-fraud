# AI-recreation_credit-card-fraud

**AI**: Google's Antigravity IDE with Gemini 3.8 Flash (High)

| Prompts |
| ------------ |
| Use pandas, seaborn, and matplotlib. You will be creating a python/jupyter notebook for an EDA. For the univariate analysis, visualize class distribution, used pin number distribution, repeat retailer distribution, online order distribution, distribution of 'ratio_to_median_purchase_price', and distribution of 'distance_from_home'.For the bivariate analysis compare fraudulent and not fraudulent for the all the visulizations. Visualize the number and percent of transactions where a pin was vs wasn't used, the number and percent of transactions where chip was and wasn't used, the number and percent of transactions done through online orders, and a scatter plot that compares the distance from last transaction versus the ratio to median purchase price.|
|For the visualizations for the distibutions of ratio_to_median_purchase_price and distance_from_home, only include the rull range histogram. Separate the number and percent bar graphs into their own graphs such that each graph can be standalone.|
| Keep the barplots you just separated as the output of one shared cell.|
|Remove the stats under each of the graphs in the univariate analysis. Remove the contingency tables from  the sections in the bivariate analysis. Remove the scatter plot summary statistics from below the scatterplot in the bivariate analysis section.|

<br>
<br>

This helped me to get the base of the project done incredibly fast. In my first prompt I got an output that included everything I needed to recreate the EDA. After that, all I had to do was take things away to match it. On a side note, when asking the AI to make edits to the project, I think it took longer than it would have if I just did it myself.

After my first prompt, I check the AI's output to make sure everything I told it to do was included and to inspect anything else it included that I did not specify. AI will generally work beyond the precise meaning of your prompt to create something that it thinks is likely desirable by the user. In my case, I did not specify precisely what I wanted in my visualizations, so the AI added a lot more details than I was expecting. It also included a lot more discriptions and descriptive statistics because I didn't tell it not to. This is where we have to be careful when using AI as it'll likely include things we weren't thinking about. Sometimes it'll give us exactly what we want, but that may not always be the case.

For tasks like this project, AI is generally correct as long as it starts from the correct place. In my recreation, I checked the beginning of the project to ensure that the AI properly imported and formatted the data correctly. If it hadn't, the entire project would likely be messed up.

The most important things we need to validate from AI is any new information it gives us or research we ask from it. This is where most of the errors can occur as it depends on both the AI and the source the AI is getting its information. If either one is wrong, then the correctness of the output will be impacted. Also, when it gathers information for us, this becomes our a base for building more knowledge and its very critical that we are starting correctly.

<br>
<br>

<!-- In order to use this properly, you have to be able to understand what infomation you need from a dataset.  -->
To use AI, you have to be able to either state exactly what you want in the output or clearly explain the goal and intentions of the the task. Someone using AI to generate analysis or reports without proper understanding of data science might not know what analysis features are actually needed to answer their question. This could result in them using graphs and analysis that might be helpful for their question but has holes in it if taken as a complete answer. In the credit card fraud example, someone without proper understanding of data science might forgo investigating which attributes are of their personal interest based on their association with fraud. This could lead to models or visualizations that don't optimally align with the goal or aren't ideal given the goal of the investigation/project. 


