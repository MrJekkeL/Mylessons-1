var arr = [5, 4, 3, -3, -10, -1, 8, -20, 0]
function findpositiveNumbers(arr) {
    let positives = []
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] > 0) {
            positives[positives.length] = arr[i]
        }
    }
    console.log(positives)
    return positives
}
findpositiveNumbers(arr)


var arr = [5, 4, 3, 8, 0, 9, 15, 11, 19, 22, 2, 7, 25]
function filterFor(arr) {
    let limit = 10
    let numbers = []
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] >= limit) {
           numbers[numbers.length] = arr[i]
        }
    }
    console.log(numbers)
    return numbers
}
filterFor(arr)
