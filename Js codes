// in most of the interview question they tend to ask Fibonacci Numbers, which there are multiple ways to create 
//Below method i have created using Array

function Fibonacci(number) {
  var i = 3;
  var arr = [1, 2];
  if (number) {
    if (number > 2) {
      while (i <= number) {
        sum = arr[arr.length - 1] + arr[arr.length - 2];
        arr.push(sum);
        i++;
      }
      return arr;
    }
    if (number == 1) {
      return 1;
    }
    if (number == 2) {
      return arr;
    }
  } else {
    return "NaN";
  }
}
 
