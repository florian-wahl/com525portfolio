---
layout: page
title: 'Inspection Method Report'
weight: 50
---
<center>

<h1> Cognitive Walkthrough Report for GrubHub </h1>
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

<center>Cognitive Walkthrough Table</center> 
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
 </table>


## Takeaways
- To standard actions such as using the search bar, as well as scrolling through results, are easy to understand by the user, but are not 100% always apparent or clear in its results
- We cannot always assume the user is always coherent with their ability to choose the correct selection, instead the application should do it’s fair share to guide them without being too overwhelming or bothersome
- Although the filters are not completely necessary, it helps the user break down selection bias by adding specifics in terms of price, reviews, and distance
- After running this test, the conclusion is that GrubHub did a pretty good job to make is search process as comprehensible as possible; almost every step did pass the cognitive walkthrough

