# forLoopPractice 
Code:

const resumeArray = [
{ Name: "Rixon"},
{ DOB: "16/Mar/1997"},
{ email: "Rixon@mail.com"},
{ Occupation: "Developer"},
{ Education: "Masters in Engineering"}

]
for (let i = 0; i < resumeArray.length; i++) {
  console.log("FORLOOP",Object.values(resumeArray[i]))
  for (let x in resumeArray[i]) {
  console.log("FORIN",resumeArray[i][x]);
}
}

function printFunction(obj){
  console.log("FOREACH",Object.values(obj))
}

resumeArray.forEach(printFunction)

for (const element of resumeArray) {
  console.log("For of Loop :",element);
}

Output:

![image](https://github.com/Rixonraj/forLoopPractice1/assets/85862632/4ee81694-e35b-4579-93ca-42e62bcdb38e)
