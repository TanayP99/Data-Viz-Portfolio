# Critique by design with Tableau 

## The original Visualization and dataset 
![This is the original visualization](PROTEIN+COST.png)

The dataset consists of the following columns
1) Protein_soure - various sources of protein
2) cost_per_20_grams_of_protein_us_dollars - cost of 20 grams of the protein in USD
3) cost_per_package - cost of one package of this protein source
4) total_protein_per_package_g - total protein in one package
5) vegetarian - Boolean variable for whether this protein source is vegetarian or not
6) vegan - Boolean variable for whether this protein source is vegan or not
7) notes - any additonal information

source - https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet

## Critique of the visualization
I critqued the visualization by rating it on the below criteria out of 10 and then answering some questions 

Usefulness.  Is it useful for the intended audience?  Does it communicate valuable information? - 8

Completeness.  Does the visualization have everything necessary to make it understandable? - 6

Perceptibility.  Can the reader understand the information with minimal effort? Is the visualization type appropriate?  Does it use illogical comparisons? - 5

Truthfulness.  Is the visualization accurate, reliable and valid?  Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisions that aren't correct? - 5

Intuitiveness.  Is it easy to understand and clearly communicates the information?  If unfamiliar, does it include easy to understand instructions on how to interpret it? - 7

Aesthetics.  It is interesting / enjoyable to look at?  Is it a good example of what a beautiful data visualization might look like?  Is it somewhere in the middle - pleasing but otherwise not distracting to look at? - 3

Engagement.  Does it lead the audience to learn more about the topic?  Does it inspire the audience to talk about the data or share it with others? - 7

Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently? 

Overall, I liked the visualization because the purpose felt clear — showing the cost of 30g of protein across different sources. What immediately stood out to me was the use of images on top of each bar representing the various protein sources. However, I found these images somewhat distracting, as they didn’t add significant value to the data and purpose of the visualization; instead, they drew unnecessary attention. It took me some time to see that chicken breast is the cheapest for 30 grams of protein, maybe that could be highlighted from the rest to focus on that insight. What worked well was the ease of comparison. The chart made it simple to visualize and compare the costs across protein sources, allowing for clear differentiation to help decision making for the audience. However I did not feel the visualization is telling us a story, Is vegetarian , vegan protein more expensive ? Is meat more calorie friendly for same amount of protein? I feel that this could be highlighted better. I would definitely use colors for each category for example Meat being red , vegan green , vegetarian a shade of grey and have a legend for it


Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?

The primary audience for this visualization includes gym-goers and fitness enthusiasts who are focused on meeting their protein intake goals while being mindful of their budget. The chart effectively shows the most affordable protein sources, which can assist them in making informed purchasing decisions. However, the varying calorie content for each protein source introduces some ambiguity. While the chart displays calorie values, it may leave viewers uncertain about which option truly offers the best balance between cost of protein and caloric intake, potentially leading to confusion in determining the most suitable choice for their needs


Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here?  What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.)*
Your answer

I found this evaluation method valuable because it encouraged me to think intuitively about what aspects of the visualization work well and what could be improved. The different criteria for rating, especially "truthfulness," prompted me to consider dimensions I hadn't previously focused on, resulting in a more comprehensive and holistic assessment of the visualization. For this particular visualization, I would recommend simplifying the design by focusing solely on cost and potentially removing the calorie information from the bars, as it may introduce unnecessary complexity. Additionally, removing the food icons could make the chart cleaner and more streamlined. To enhance credibility, I’d also suggest including some context about the source of the price data, helping readers trust the information presented.

## Sketching out potential solutions 

In planning the redesign, I focused on how best to visualize the data to tell a clear, compelling story. I started by deciding to use distinct colors to represent non-vegetarian, vegetarian, and vegan protein sources, making it easy for viewers to differentiate between these categories at a glance. I also chose to switch the axes, placing cost on the x-axis, which feels more intuitive for interpreting price comparisons.
To enhance clarity, I arranged each protein source in ascending order, from the lowest-cost options at the top to the highest-cost options at the bottom. Another concept I sketched involved a direct comparison between vegetarian and non-vegetarian protein sources. The goal here is to illustrate how accessible and cost-effective it is to meet protein needs as a vegetarian compared to a non-vegetarian. By placing these two groups side by side, I hope to highlight any noticeable differences in affordability and availability of protein sources across dietary preferences.

![sketch1](protein_sketch1.jpg)

![sketch2](protein_sketch2.jpg)

## User Research and feedback through interviews

I conducted two different interviews to test out my sketches below are transcripts from the interviews

### interview 1 - 18 year old college student 

1) What do you think these sketches , visualizations are about?
   
I think it is about how effective vegetarian protein is vs non vegetarian protein
It ranks the cheapest protein sources available 

2) Who do you think the target audience is?
   
I think the target audience is vegetarians who want to hit their protein goals and find it difficult to do so 

3) Do you find the titles to be intuitive? Does it inform you about the purpose of the visualization?
   
Yes I liked the titles ,they are clear and straightforward and immediately tell me what these visualizations are about 

4) Is there anything you would change ?
   
In the sketch where you are comparing vegetarian vs non vegetarian protein instead of having to separate graphs  , I would use one graph together that it can be easily compared better

5) Do you feel that the visualizations are complete? Is there any other details you would like to see?
   
I would like to see the data a little differently - for example instead of seeing the cost of 20 gm protein for each source , I want to know how much protein is in say $5 of the source, this would help me visualize better 

6) What stands out to you?
   
It is easier to hit protein as a non vegetarian, non veg options are more cost effective 

### Interview 2 - 21 year old professional in advertising


1) What do you think these sketches , visualizations are about?

My understanding of the visualizations is that it shows different forms of protein and their prices , and categorizes the protein based on dietary preferences 

2) Who do you think the target audience is?

I think the target audience of the visualizations are people who are focused on their nutrition and looking to eat protein rich foods , maybe gym goers and fitness enthusiasts 

3) Do you find the titles to be intuitive? Does it inform you about the purpose of the visualization?

I think the titles are direct and straightforward. The title that says 'Cheapest protein based on diet' biased me to look at the cheapest but I did not want to look at that, also if you want to focus on cheapest protein based on diet maybe highlight that in your visualization 

4) Is there anything you would change ?

I would change the color for vegetarian - for me vegetarian means no egg and the color seems like it is egg. Also I would change the title for the graph as mentioned above

5) Do you feel that the visualizations are complete? Is there any other details you would like to see?

I want to know how to hit my protein goals , that is my takeaway , in this visualization I am unable to see how to hit my protein intake requirements 

6) What stands out to you?

What stands out to me is that vegetarian protein is more expensive and that meat is cheaper and it is easier for non vegetarians to hit their protein goals



