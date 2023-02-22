For- och while-loopar är två av de vanligaste looparna i programmering. De används för att upprepa en kodblock flera gånger tills ett visst villkor är uppfyllt. Skillnaden mellan dem är hur villkoret uttrycks och när de används.

En for-loop används vanligtvis när vi vet antalet iterationer som behövs för att utföra en uppgift. Syntaxen för en for-loop är som följer:

for (int i = 0; i < 5; i++) {
   System.out.println("i är nu " + i);
}

En while-loop å andra sidan används vanligtvis när vi inte vet antalet iterationer som krävs. Syntaxen för en while-loop är som följer:

int i = 0;
while (i < 5) {
   System.out.println("i är nu " + i);
   i++;
}