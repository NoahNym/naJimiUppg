En funktion i programmering är en uppsättning instruktioner som utförs när funktionen kallas från en annan del av programmet. Funktioner används för att organisera koden, återanvända kod och göra programmet mer modulärt.

I JavaScript kan du definiera en funktion på två sätt: vanliga funktioner och arrow-funktioner.

Vanliga funktioner definieras med nyckelordet "function" följt av funktionsnamnet och dess parameterlista inom parenteser. Koden som ska utföras när funktionen kallas skrivs inom måsvingar.

function addNumbers(num1, num2) {
  return num1 + num2;
}

const addNumbers = (num1, num2) => num1 + num2;

const sum = addNumbers(5, 7); // sum kommer nu att ha värdet 12