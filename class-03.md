# Class 03 reading notes

## lists and keys

1. .map() returns a new array.
2. To look through an array and display a value you would have to make then You would have to embedd an expression.
3. Each list item needs a unique key.
4. Keys are helpful because they can help your react but dont get passed into your components. You can pass them as props but it won't change their value.

## The Spread Operator

1. Spread Operators are the ability to expand an object into a list of arguemnt by using "...arr"
2. Spread Operators can copy an array, Use math functions, combine objects, add an item to a list, etc. 
3. Idk how to create an example here but you declare an array with some values then another and then set a new variable using {...hello,...world} and this will combine a hello array and world array and their contents.
4. you would do it the same way, set an array and then declare a variable with whatever. You would then declare a new a variable saying = [this, that, ...newItem].
5. Same thing as 4 except using curlys than brackets. Set two variables with objects then declare a new variable and say {...One,...Two}.

## Video

1. He maps through his array in state and sends passes information as props to his Person.js.
2. He is creating a passing in object to loop through array in state to find a certain person, create a new array and modify it by adding a count to it.
3. Passing it as props in a render return, like...
ex: Person name={this.state.name}/>
This will then pass name in state to another component as props so it can be called upon in Person as this.props.name.
4. This.props.whatever.. I spoke about it above.
