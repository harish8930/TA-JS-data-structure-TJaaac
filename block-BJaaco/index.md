function revert(inputarray) {
    return  inputarray.reverse();
  }


function arrayToObj(inputArray) {
    const obj = {};
    for (let i = 0; i < inputArray.length; i++) {
      obj[i] = inputArray[i];
    }
    return obj;
  }
  
