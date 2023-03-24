# food-recomendation-system
this code based on specefic Duarable package rules and also modeled after https://github.com/ShreyaGoel03
food recomendation system provides list of main food and intersts for user to choose, then based on user's choice, recommend appetizer, main food, desert and beverage
fisrt ask the user age's range, then which kind of food category like, and then which kind of intesets he likes. 
then if the user choose the proper food category based on his age, it recommends a list of food, appetizer, desert and bevarege. but if he choose not the proper food category, the system warn him to choose the food based on his age and let the user to choose again, but if the user insist on his first choice, the system goes on and print the final recommendation
the desert and bevarege recommendation are based on the interst whcih user select, and there are not always boath of them at one recommendation.
There are four main ruleset in the system which provide the recommendation list. the four ruleset are connected together and based on each other fire other rules and rulesetes. the Durable package made a big help to write rules simple and easy and use them properly.
The structure of the system is described in the two flowcharts below
<img width="376" alt="Screen Shot 1402-01-04 at 16 51 59" src="https://user-images.githubusercontent.com/85408877/227538930-c7ad3ad6-df2d-4fe3-8380-3506dcd0a5ba.png">
<img width="365" alt="Screen Shot 1402-01-04 at 16 52 05" src="https://user-images.githubusercontent.com/85408877/227539023-c04397b7-07d3-4fb4-b398-420c34dfede7.png">




The list of questions that the system asks the user and an example of the system's answer will be in the  following.


enter 1 if your age is under 10
 enter 2 if your age is between 11- 18
 enter 3 if your age is between 20-40
 enter 4 if your age is greater than 40
Enter your current age in the range of 1-4 2

Choose the best interest that suits you! Enter the index of the choice. 


Available Interests for food and dessert: 

 1. irani 
 2. kebbab 
 3. tradition 
 4. helathy food 
 5. vegan 
 6. international 
 7. fast food 
 8. sea food 
 9. kids food 
 

Enter the index of the interest that suits you! 3


Available Interests for choosing beverage and dessert s: 

 1. traditional music 
 2. hichhickes  
 3. football  
 4. design 
 5. fashion 
 6. beauty
 7. anime 
 8. Finance 
 9. Art 
 10. history

Enter the index of the interest that suits you! 5


Ana an example of system answer will be as following:
Displaying the foods and the  Activities Club! 

Fact: Choose appetizer -  salad
Fact: Choose appetizer -  mushroom soup
here 2
Fact: Choose main food -  shishlik
Fact: Choose main food -  koobideh
Fact: Choose main food -  chenjeh
Fact: Choose main food -  barg
Fact: dessert Club musical :- roasted strawberry crumble


 
