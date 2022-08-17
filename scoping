
// This is the global scope. When we refer to the variable chris we are refering to the Chris below.

let chris = "Chris Hemsworth";

const printScripts = function() {
  // This is the functional scope. When we refer to the variable chris we are refering to the Chris below.
  let chris = "The PA";
  console.log("Who is Chris? Chris is", chris);
};

// this console log is in the global scope
console.log("Who is Chris? Chris is", chris);

//this console log will be in the function scope
printScripts();

// Will the functional scope mutate the global scope after it is called?
// Do you expect this to say the PA or Chris Hemsworth?
console.log("Who is Chris? Chris is", chris);

