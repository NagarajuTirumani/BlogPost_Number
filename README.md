# Number() Method

The Number() method is used to convert the given Data into numbers. Given data must belong to legal numbers (i.e, 0-9). Let's understand with an example.

###### Input: 
   ```
        let value = "586"
	    console.log(typeof(value));
	    let result = Number(value)
 	    console.log(result)
 	    console.log(typeof(result));
   ```
###### Output:
```
      string
      586
      number
 ```
 In the above example, The type of value is a string, after the conversion of value into a number, a type is a number.
 #### For Boolean:
 In the same way, we can convert true/false boolean values to their corresponding numeric values. we can understand this through the following example.
 ###### Input:
 ```
 let value = true  // If the value is false it returns, 0 
 let result = Number(value)
 console.log(result)
 ```
 ###### Output: 
 ```
 1
 ```
 #### For Dates:
 We can also convert the date object to milliseconds since 1970 Jan 1 midnight.
 ###### Input:
 ```
 let date = new Date()
 let value = Number(date)
 console.log(value)
 ```
 ###### Output: 
 ```
 1659337663162
 ```
The above result is changed when you run in your code playground, It gives according to your current date.

If the value is can not be converted into a number(not a legal number), it returns NaN.
###### Input:
```
let value = "100a"
let result = Number(value)
console.log(result)
```
###### Output: 
```
NaN
```

You can watch more [here](https://youtu.be/zDoCinTZs0o)

also, you can read about this [here](https://www.w3schools.com/jsref/jsref_number.asp)
        
