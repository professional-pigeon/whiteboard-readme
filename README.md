const deDuper = function(arrayDupe) {
	singlesArray = [];
  arrayDupe.forEach(element => {
  if (singlesArray.includes(element) === false) {
      singlesArray.push(element);
    }
  });
  return singlesArray;
};

console.log(deDuper(["this", "array", "has", "this", "array", "has", "no", "no", "dupes"]));

const deDuperRecurs = function(dupeArray) {
	return function (counter) {
  if (counter === 0) {
    return array
  }
  element = dupeArray.shift()
  if (dupeArray.includes(element) === false) {
  	dupeArray.push(element)
    }
    counter --
    return deDuperRecurs(dupeArray)(counter)
  }
}

array =  [7, 9, "hi", 12, "hi", 7, 53]
console.log(deDuperRecurs(array)(array.length))

const filterThemDupers = function(dupeArray) {
  dupeArray.filter ((element, index) => dupeArray.includes(element) 
} //incomplete

