if, else if, och else är villkor som används för att utföra olika handlingar baserat på ett givet test.

if och else if fungerar som logiska test som bestämmer om en viss kod ska utföras eller inte. Om testet returnerar sant, utförs koden som är kopplad till villkoret. Annars hoppas programmet över den koden.

else fungerar som ett fall-back villkor som körs om ingen av de tidigare villkoren har uppfyllts.

const age = 25;

if (age < 18) {
  console.log("Du är inte myndig");
} else if (age < 25) {
  console.log("Du är ung vuxen");
} else {
  console.log("Du är vuxen");
}