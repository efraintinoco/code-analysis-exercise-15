  # Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input | Output |
| ----- | ------ |
|  {name: "Efrain", dogs: [{name: "Princess", breed: "Pomeranian", age:2}, {name: "Rocky", breed: "Boxer", age: 10}],}, "Princess"   |  {name:"Princess", breed: "Pomeranian", age: 2 }  | 
|  {name: "Brenda", dogs: [{name: "Thor", breed: "German Shepard", age:4,}, {name: "Luna", breed: "German Shepard", age: 3}], }, "Thor"     |  {name: "Thor", breed: "German Shepard", age:4 } | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>
      This function takes in two arguments, person and petName. This is a loop that iterates over properties of objects. In this case it is searching for a person name and matching it up with a pet name, when the return value is
      true then it will return the dog info.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
