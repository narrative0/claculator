const age = 96
function calculateKrAge(ageOfForeigner){
    return ageOfForeigner + 2
}

const krAge = calculateKrAge(age)

console.log(krAge)


const claculator = {
    add: function (a, b) {
        return a + b
        
    },
    minus: function(a, b) {
        return a - b

    },
    multiplied: function(a, b) {
        return a * b

    },
    divided: function(a, b) {
        return a / b

    },
    squared: function(a, b) {
        return a ** b

    }
    
}

const addResult = claculator.add(5, 4)
const minusResult = claculator.minus(addResult, 4)
const multipliedResult = claculator.multiplied(10, minusResult)
const dividedResult = claculator.divided(multipliedResult, 4)
const squaredResult = claculator.squared(minusResult, addResult)

