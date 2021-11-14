# FreeCodeCamp3


41  function chainToSwitch(val) {
  let answer = "";
  // Only change code below this line
  switch(val){
    case "bob" :
    return "Marley";
    break;
    case 42 :
    return "The Answer";
    break;
    case 1:
    return "There is no #1";
    break;
    case 99:
    return "Missed me by this much!";
    break;
    case 7:
    return "Ate Nine";
    default: return ""
  }

  // Only change code above this line
  return answer;
}

chainToSwitch(7);

 
 42   function isLess(a, b) {
  // Only change code below this line
  return a < b;
  
  // Only change code above this line
}

isLess(10, 15);


43  // Setup
function abTest(a, b) {
  // Only change code below this line
  if (a < 0 || b < 0){
    return undefined;
  }
  // Only change code above this line
    return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));

}

abTest(2,2); 


44 let count = 0;

function cc(card) {
  // Only change code below this line
  switch (card) {
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
      count++;
      break;
    case 10:
    case "J":
    case "Q":
    case "K":
    case "A":
      count--;
      break;
  }
  if (count > 0) {
    return count + " Bet";
  } else {
    return count + " Hold";
  }
  // Only change code above this line
}

cc(2); cc(3); cc(7); cc('K'); cc('A')


45   const myDog = {
  // Only change code below this line
  name: "",
"legs" : 1,
"tails": 1,
"friends" : [ ]


  // Only change code above this line
};

46  // Setup
const testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line
const hatValue = testObj.hat;      // Change this line
const shirtValue = testObj.shirt;    // Change this line


47// Setup
const testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line
const entreeValue = testObj["an entree"];   // Change this line
const drinkValue = testObj["the drink"];    // Change this line

48// Setup
const testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line
const playerNumber = 16;  // Change this line
const player = testObj[playerNumber];   // Change this line



49 // Setup
const myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
   myDog.name = "Happy Coder"
// Only change code below this line



50 const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
 
 myDog["bark"] = "Гав";


51  // Setup
const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};
  delete myDog["tails"]
// Only change code below this line


52  // Setup
function phoneticLookup(val) {
  let result = "";

  // Only change code below this line
 const lookup = {
   
     "alpha":"Adams",
      
    "bravo": "Boston",
      
     "charlie": "Chicago",
     
     "delta":"Denver",
      
   "echo":"Easy",
      
    "foxtrot": "Frank"
  }

   result = lookup[val];
  

  // Only change code above this line
  return result;
}

phoneticLookup("charlie");



53  function checkObj(obj, checkProp) {
  // Only change code below this line
 if(obj.hasOwnProperty(checkProp) === true){
   return obj[checkProp]
 } else{
   return "Not Found"
 }




  return "Change Me!";
  
  // Only change code above this line
}


54   const myMusic = 
[
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
{
"artist":"",
 "title":"",
  "release_year": 1925,
 "formats":["1","2"]
}
];


55   const myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

const gloveBoxContents = myStorage.car.inside["glove box"];



56   const myPlants = [
  {
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }
];

const secondTree = myPlants[1].list[1];




57  // Setup
const myArray = [];

// Only change code below this line
let i = 0;

while (i <= 5) {
  myArray.unshift(i);
  i++;
}


58 // Setup
const myArray = [];

// Only change code below this line
for(let i = 1; i<6;i++){
  myArray.push(i)
}


59 // Setup
const myArray = [];

// Only change code below this line
for(let i = 1; i<=9;i+=2){
  myArray.push(i)
}

60  // Setup
const myArray = [];

// Only change code below this line
for(let i = 9; i>=1; i -= 2){
  myArray.push(i)
}
