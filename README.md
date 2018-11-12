# Phillies-Question

This code is meant to give the user an idea of how much a qualifying offer (like a franchise tag in NFL) is going to cost the franchise.
I wrote this code in python (Not my strongest language) because number 1 in the questionaire was python. 
Here is the algorithm.

Algorithm:
  make an array with all of the data. Sort it from greatest to least then take the top 25 numbers and put it into a new array. 
    Arrays.sort(arr, Collections.reverseOrder());  //use something like this (java)
  
  Then take the average of the new array resulting in the average of the highest top 25 salaries which would be the new guys salary.
    for loop through the array adding each value to the next then dividing by 25
  
  If the guy accepts the contract then *return the average as the value of his one year contract.
  If the guy denies it then *return "contract denied player going to sign with another team, you will recieve a draft pick"
  
  However I feel like the hardest part of the code was not the algorithm but simply pulling the data from the URL and parsing it.
  In a real life situation if the data was already in a data base that was accessible then the code would not be very difficult. 
  Nevertheless here is the code, I hope you like my attempt. 
