# base17
sorting
** start of script.js **

function getIndexToIns(arr,num){
arr.sort((a,b)=>a-b)
const Index=arr.findIndex((val)=>val>=num)
return Index===-1?arr.length:Index
}
console.log(getIndexToIns([1,2,3,4,5],2))

** end of script.js **

