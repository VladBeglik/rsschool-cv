# Vlad Beglik
## Junior Front End Developer

## Contacts 
Phone: +375291472905\
Email: vladbeglik@gmail.com

## About Me

I am a hard working, honest individual. I am a good timekeeper, always willing to learn new skills. I am friendly, helpful and polite, have a good sense of humour. I am able to work independently in busy environments and also within a team setting. I am outgoing and tactful, and able to listen effectively when solving problems.

## Skills

- Html, css
- Js
- .NET
- git

## Code:
### Task
Given an array of integers, remove the smallest value. Do not mutate the original array/list. If there are multiple elements with the same value, remove the one with a lower index. If you get an empty array/list, return an empty array/list.
Don't change the order of the elements that are left.
```
function removeSmallest(numbers) {
  var smallest;
  var newNums = [];
  numbers.forEach(function(num) {
    if (smallest > num || smallest === undefined) {
      smallest = num;
    }
  });
  var index = numbers.indexOf(smallest);
  numbers.forEach(function(n, i) {
    if (i !== index) {
      newNums.push(n);
    }
  });
  return newNums;
}
```

## Languages:

- English - Intermediate
- Russian - Native