# A5_Project Reflection

In the beginning we had a few different options for what the tools main focus should be, and how big of a scope of information the tool should use. Because of this uncertainty early on the focus turned naturally to the IFC, and how to extract the information we thought we might need at a later point in the process. By working with these extractions it was made clear to us that the initial idea of creating a cost estimate of the whole bulding would require much more time, and would yield a very unfinished product at the end of the semester. The scope of the tool was therefore compromised to only extract main structural beams, columns, slabs, walls and footings.

After we got a chance to look at the MOLIO JSON file, our initial idea was to create the code as a brigde that generated a direct link between the properties in the IFC model and the pricebook. If there is something that would have significantly improved our work tool it would have been to achieve this, making the whole program automated, and not user-dependent. After a while trying to figure out how to accomplish this we concluded it would be quite difficult to do so seing that the  pricebook mostly consisted of strings and not numercal values, and was written in danish. 

Talking to the representatives from Niras gave us a chance to ask questions about the usability of our tool. After a conversation it became clear to us that the tool would be somewhat useless if there was not an output that could later be made use of for other purposes than to just read. Our goal shifted from **«To quickly assess cost associated with design changes»**, to more of a economical view, where hopefully the output data could come in handy if other calculations or visualizations were to be made. It would also improve our usecase if we were able to make the worktool to visualize our csv outputs in a cool manner, for making the reading of the price data more understandable. 



## 1. Process of developing the tool
Choosing cost estimation as a usecase was not arbitrary for us, because of the fact that we already touched by this topic on our bachelor thesis that we wrote on building schools with CLT as a substitution for concrete and steel from a structural and economical perspective. Since we both are focusing our master on the subject of project management, cost as well as substitute materials for concrete will be important factors for future building and therefore a fascinating issue that might very well become important when it comes to our thesis.

As for the freedom of choice of usecases, we personally liked being free in such decicion making, because working with things we find interesting, gives us an extra incentive to create something we are proud to hand over. We think that if there are enough usecases to cover most of the focus areas the students in the class have in their curriculum, everyone might find a usecase they can be somewhat passionate about.

That being said, we would have liked to see the lectures go more in depth in how the coding works, and deeper into how the IFC relationships are tangled together. We think this might set a clearer vision for the students on what might they create as their final project. If they understand the basics of coding inside the IfcOpenshell from the beginning, they might be more inclined to use other tools (A2_FutureBim) to be even more creative in their work. 

## 2. Output of the tool
Our use case has been to give a cost estimate of the main structural elements, and this is also what our tool does. In the beginning we also included our use case to check if the cost was satisfactory regarding budget, and also included a loop to adjust BIM model, but in the final A4 assignment we left this out and updated our bpmn-diagram to only focus on the actual function of our code/work-tool. 

Our use case was initially broader than what it is now, we started with a pretty big scope just thinking about a general cost estimation in the early design process, however as the course went on we understood that we had to narrow our project down. In the final assignment we shifted our focus to main structural elements and more specific material output than what we previously envisioned us. This lead to a more precise product and less mess in our outputs, and also allowed us to complicate the work tool to a higher degree. 

## 3. Future
Both of us used OpenBIM in our bachelor thesis where we had access to BIM-models for two different building projects we were analyzing. We then had to use different softwares to do our analysis and OpenBIM made this much easier for us, so it is certainly a possibility for us to also use it in our master thesis when that time comes. 

As BIM already is a big part of the design and construction phase of buildings, we are very likely to have great use of OpenBIM and its benefits in our professional life in the next 10 years. Either as a consultant where we will provide information to the model, or on the contractor side where we will use it for visualizing and interaction between disciplines. 

