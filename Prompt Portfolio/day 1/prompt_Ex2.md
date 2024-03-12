
### Prompt Portfolio Template

#### Prompt ID:
`Prompt-AA-12`

#### Description:
`This document helps to leverage Chain of thought prompting technique to improve chatbot experience`

#### Use Case:
`Logic Assistant to provide psuedocode for solving problem`

#### Prompt:
`
Provide logic to solve number of zeroes in array
A: Go through each value in array and each time check of value equal to zero , if yes then increase the counter value. 
Return the counter at the end of the array

Provide logic to solve longest distance between 2 points in 2D array
A:
`

#### Expected Libraries/Frameworks:
`NA`

#### Parameters:
`temperature=0.7 ,max_tokens=256,top_p=1,frequency_penalty=0,presence_penalty=0`

#### Sample Output:
`For finding the number of zeroes in an array:

Initialize a counter variable to 0.
Iterate through each element in the array.
For each element, check if it is equal to zero.
If the element is zero, increment the counter by 1.
After iterating through all elements, return the counter value as the number of zeroes in the array.
For finding the longest distance between two points in a 2D array:

Iterate through each pair of points in the 2D array, computing the distance between them using a distance formula (e.g., Euclidean distance for 2D space).
Keep track of the maximum distance encountered during the iteration.
After iterating through all pairs of points, return the maximum distance as the longest distance between two points in the 2D array.
`

#### Adjustments:
`[Any modifications based on testing]`

#### Ethical Note:
`[Any ethical considerations or adjustments]`

#### Version:
`[Version number and date]`
