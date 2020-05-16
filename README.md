# JavaScript-Tip-Calculator
tip calculator using javascript

function tipCalculator(total = undefined, tipPercent = .2) { // .2 is the temp percentage (20%)
    tip = total * tipPercent
    totalTip = (total + tip) - total
    return 'Your 20% tip amount is $' + totalTip
}

let finalTip = tipCalculator(100)
console.log(finalTip)
