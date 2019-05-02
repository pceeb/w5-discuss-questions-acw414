## This questions are due next discussion section (Week6).

1. Describe the Biology of your project? (one paragraph max).  

This project will use environmental DNA (eDNA) data collected by researchers, which will be in the form of gene sequences.
All species that move through the world shed bits of their DNA through their hair, scales, and bodily fluids, in the same way humans shed skin cells. These fragments of DNA remain in the environment, acting as identifiers for all species who have passed through. Researchers can then take samples from the water or soil and extract this eDNA data. This allows for people to study the distribution, interactions, and population dynamics of many different species at once without ever needing to come in direct contact with them. This project will assist in this remote form of researching by using the species lists generated from eDNA sequence analysis and determining whether there is any correlation between the traits of species discovered in a particular area. Our project will use eDNA collected from water samples, and will therefore involve data analysis to do with marine species.

2. Describe the kind of data that you think you will be handling (one paragraph max).  

We are still in the planning stages of our project and are not sure whether we will stick with using FishBase data or another online database. Currently we think that we will collaborate with other groups using FishBase, and so our input data will not be raw eDNA data. Another group will take the raw eDNA sequences and match them to those on FishBase and produce a table of different species that lists their name, specific FishBase codes, and then differernt morphological and behavioural traits in different collumns.  This table will be the data we will then work with. 

3. What would you like to do with that data? (one paragraph max).  

We are not sure what direction our project will head in yet, but we know we will focus on one or two specific traits. We will extract the collumns pertaining to those traits, and cluster the data into appropriate groups. For instance, if we analysed the preferred depths of different species we could cluster them into groups of 0-15 metres, 15-30 metres, 30-45 metres etc. We want to visually represent the data, and so would use the clusters to make graphs using R. 

4. What will be the output? (one paragraph max).  

The output would be a graph, or several graphs, pertaining to our chosen trait. The graphs would contain the clusters we generated, and could also be grouped based on the location the samples were taken from. If we focus on preferred depths, we could create a graph to visually map the number of species that dominate the different levels of the ocean. We were also thinking of mapping the distribution of species by overlaying their different geographic dstributions in different colours on a single map. However, we need to fully understand what trait/area we will be focusing on before making any final decisions.

5. Is there any computational tool, package, etc. you would like to use? What would you do with that? For instance, you could mention shell scripts with `sed` or `awk` and will change the format of a table by replacing `,` with tabs. 
Also, you could mention tools that we haven’t seen in class yet but you herd that may be useful for your project. 
For instance, you could say 
***I will use the package “GenomeGraphs” implement in the R software to visualize genome data***. (a few sentences max).  

I will need to use grep to exctract particular collumns from our data tables and will then put them into appropriately formatted tables using sed. We may need to change commas, semicolons, or full stops, but do not know yet because we havent seen the actual data. We will then need to cluster the data, but I am not too sure how we can do that (I'm sure there are lots of tutorials out there though!). We will finally then use R to create our visual representations. We may use R for the whole program, or may start with Python and move onto R just for the last bit. 

6. What is your biggest concern regarding your project? (a few sentences max).

My biggest concern is I am not too familiar with clustering, but my partner Joshi says he has some experience in creating clusters. I am also unsure of how to work with R, but I know that we will be doing more with it in the next few weeks in lecture.
