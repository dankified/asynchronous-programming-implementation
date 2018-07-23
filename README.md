# Asynchronous programming exercise

## We will be working with Promises and the async/await functionality to do some asynchronous programming.

## Setup.

1. Create a new directory called ```async-implementation``` and move into it.
2. Run ```npm init -y``` in order to initialize a new node project
3. Run ```npm install axios``` in order to install axios as a dependency
4. Create an ```index.js``` file.
5. Require ```axios``` into the ```index.js``` file

## Objectives.

1. Create an ```async``` function that gets data from both ```https://www.google.com``` and ```https://www.yahoo.com``` in a sequential manner using ```await```.
2. This function should return an array that contains the ```data``` object from each response as elements.
3. Wrap your ```function``` code inside a ```try/catch``` block in order to handle errors.
4. Create a new ```async``` function that does the same thing as the previous function, but now you will handle errors for each ```function``` independently instead of wrapping all your code in a ```try/catch``` block. 
Hint: ```Promises``` returned by ```axios``` have access to a ```catch``` method that allows to handle errors independently.

## Now, if you feel lucky punk, do the same thing all over again using promises
 
