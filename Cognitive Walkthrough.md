---
layout: page
title: 'Inspection Method Report'
weight: 50
---


<center><h1> Cognitive Walkthrough Report for GrubHub </h1></center>
<br>

## Why we choose CW as our inspection method?
- Cognitive Walkthrough method is quick, easy to set in place, and convenient to conduct.
- Although Cognitive Walkthrough method seems light, it provides full and useful guidance for us  to evaluate a product. Four questions are organized and fulfills the important parts of the product, especially since it provides a clear sequence of events.
- Heuristic Evaluation Method provide ten standards to analysis each steps of a product, which means the results would be too detailed. And sometimes, you couldn’t answer some questions since they’re not obvious to find.  
- Heuristic Evaluation Method focuses more on the interface design problems, like *“Visibility of system status”, “Match between system and the real world”, “Flexibility and efficiency of use”* and *“Aesthetic and minimalist design”*. However, for our research product GrubHub we want to discuss more about the feature performances and the logic behind each step.
- The question that we are asking is relevant to the inspection and can be helpful to improve the product (from a developer point of view).

## Cognitive Walkthrough
**Task**:Search for *Pad Thai* in nearest restaurant by *distance, lowest price ($), and 3-star rating & up*.
**Users**:Not a frequent user of GrubHub, but have use the app at least once.
**Questions**:
- Q1: Does the next action makes sense to the user?
- Q2: Is the action visible?
- Q3: Will the user recognize the action as the one they need?
- Q4: Will the user understand the feedback?

<center>**Cognitive Walkthrough Table**</center>
<table>
  <tr>
    <td><b>#</b></td>
    <td><b>Steps</b></td>
    <td><b>Q1</b></td>
    <td><b>Q2</b></td>
    <td><b>Q3</b></td>
    <td><b>Q4</b></td>
    <td><b>Notes</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>Input Pad Thai in search the bar.</td>
    <td><b>Yes</b><br>
 		The search bar is visible to the user. </td>
    <td><b>Yes</b><br>
    	The keyboard becomes visible to the user when they tap in the search bar.</td>
    <td><b>Yes</b><br>
    	The search bar has text within it, indicating this as the right location to input a query.</td>
    <td><b>Yes</b><br> 
    	The results list restaurants that offer Pad Thai.</td>
    <td>I will say that if the user were to expect the results to show a comparative list of Pad Thai dishes, then they would get confused. Instead, the user is given a list of restaurants that offer the dish.  </td>
  </tr>
  <tr>
	<td>2</td>
	<td>Use the filter/refine button to <br>
		<b>1.Sort By: Distance</b> <br>
		<b>2.Ratings: ★★★ & up </b> <br>
		<b>3.Price: $ & below</b></td>
	<td><b>Yes</b><br>
		After users set their filters, and choose “Apply”, the filtered restaurants will showed in the homepage. </td>
	<td><b>Yes</b><br>
		Although “Sort By” and “Deliver my order” need users to choose in a hidden stage, all the filters choices are clearly visible.</td>
	<td><b>Yes</b><br>
		The choices in Filters have strong introductions for users to easily understand. And users could choose any one if they need.</td>
	<td><b>Yes</b><br> 
		The chosen result in “Sort By”, “Deliver my order” and “Price” will become blue;The asteroid figure would become yellow after users choose;The last three filters provide on-off button for users to choose, and once users tap, the button will become switch to blue. </td>
	<td></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Choose the nearest restaurant</td>
    <td><b>No</b><br>
 		Even though results have already sorted by distance you have to assume the first result will be the closest, whereas there is no other visual indicator acknowledging it to be the correct choice. Not very clear, and greyed out.</td>
    <td><b>No</b><br>
    	The mileage is shown in the description that follows the restaurant, but you have to compare at least one other to know that it is the shortest route</td>
    <td><b>No</b><br>
    	The results have been sorted in ascending by distance, as well as, but the user will have to verify by comparing</td>
    <td><b>Yes</b><br> 
    	Mileage is sorted in ascending order, as well as there is a visual indicator of range. Assuming the user is confident of their selection</td>
    <td>The only concern I could in this step is that there is no certain selection, as in GrubHub does not say for certain the first selection is the nearest, you are to assume or compare on your own accord, and trust that the app is functioning correctly </td>
  </tr>
  <tr>
	<td>4</td>
	<td>Select the Pad Thai dish<br>
		<b> - Scroll down the menu to find Pad Thai</b> <br></td>
	<td><b>Yes</b><br>
		The results are displayed as a list and it makes sense to ask the user to scroll it to see more options </td>
	<td><b>Yes</b><br>
		Same as Q1, all the results are displayed. In addition, a small scrolling bar is visible on the right side of the screen (indicates that there is more to see below)</td>
	<td><b>Yes</b><br>
		If they don’t see a choice that fits what they are looking for, they will definitely scroll the screen</td>
	<td><b>Yes</b><br> 
		When scrolling the screen the results are moving like expected. In addition, the scroll bar is moving giving feedback on how many results are left in the list </td>
	<td>Nothing to add or change to this step. The action is pretty standard, understandable for an unfamiliar user, and the feedback is clear and redundant.</td>
  </tr>
  <tr>
	<td>5</td>
	<td>Select the Pad Thai dish<br>
		<b> - Input pad thai into search bar</b> <br></td>
	<td><b>Yes</b><br>
		Users can input Pad Thai in search bar and a list of the results is shown, and users can choose anyone they want. </td>
	<td><b>Yes</b><br>
		The search bar is obviously visible on the page.</td>
	<td><b>Yes</b><br>
		The blank search bar with grey details “Search menu items” tells users to input dishes they want. </td>
	<td><b>Yes</b><br> 
		If the user inputs the correct dish name, they will see the results in the list. </td>
	<td></td>
  </tr>
 </table>


## Takeaways
- To standard actions such as using the search bar, as well as scrolling through results, are easy to understand by the user, but are not 100% always apparent or clear in its results
- We cannot always assume the user is always coherent with their ability to choose the correct selection, instead the application should do it’s fair share to guide them without being too overwhelming or bothersome
- Although the filters are not completely necessary, it helps the user break down selection bias by adding specifics in terms of price, reviews, and distance
- After running this test, the conclusion is that GrubHub did a pretty good job to make is search process as comprehensible as possible; almost every step did pass the cognitive walkthrough

