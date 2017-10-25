# greetCostumer

Escribe una función llamada greetCustomer.

Dando un nombre, greetCustomer devuelve un saludo basado en cuántas veces ese cliente ha visitado el restaurante. Consulte el objeto customerData.


## Pseudocodigo

1. Recibir el parametro firstName 
2. Si (firstName) == unknown entonces 
	2.1 Regresar 'Welcome! Is this your first time?'
3. Si (firstName.visits == 1) entonces 
	3.1 Regresar 'Welcome back, +firstName! We're glad you liked us the first time!'
4. Si (firstName.visits > 1) entonces 
	4.1 Regresar 'Welcome back, +firstName! So glad to see you again!'
5. Fin
