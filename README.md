Algoritmo joshua












	Definir num1 , num2 , opc , res Como Real
 
	escribir "Mi Calcuadora  ";
 
    escribir "Por favor ingresa el primer número:";
    
    leer num1;
    
    escribir "Por favor ingresa el segundo número:";
    
    leer num2;
    
    
    escribir "Por favor ingrese la operación que desea realizar. Elija una de las siguientes opciones:";
    
    escribir "1: Para sumar";
    
    escribir "2: Para restar.";
    
    escribir "3: Para multiplicar.";
    
    escribir "4: Para dividir.";
    
    escribir "5: Para elevar a una potencia.";
	escribir "6:para  funcion";
	Escribir "7:seno ";
    leer opc;
    Segun opc Hacer
        1:
            res<-num1+num2;
        2:
            res<- num1-num2;
        3:
            res<-num1*num2;
        4:
            res<-num1/num2;
        5: 
            res<-num1^num2;
			
	    6:  res<- trunc (num1 + num2 );
			
		7:  res<- sen(num1*num2);
			
			
        De Otro Modo:
            escribir "La opción seleccionada no es valida.";
			
    Fin Segun
    Borrar Pantalla
	Definir OPCIONES Como Caracter
	OPCIONES <- "N"
	Mientras OPCIONES   == "N" Hacer
		Escribir "Tienes que escribir la S "
		
		Escribir " ¿ deseas seguir ejecutandolo el programa ? [N/S]:"
		Leer OPCIONES
	FinMientras
	Escribir "Presione una tecla para iniciar el lanzamiento!"
    Esperar Tecla
    
    
    Definir cohete Como Caracter
    dimension cohete[9]
    cohete[1]<-"   /|\   "
    cohete[2]<-"   |B|   "
    cohete[3]<-"   |O|   "
    cohete[4]<-"   |M|   "
    cohete[5]<-"   |B|   "
    cohete[6]<-"  //|\\  "
    cohete[7]<-" ******* "
    cohete[8]<-"* * * * *"
 
    Definir i Como real
	Definir j Como Real
    
    Para i<-1 hasta 11 Hacer
        Borrar Pantalla
        Para j<-1 hasta 15 Hacer
            Escribir ""
        FinPara
        Para j<-1 hasta 6 Hacer
            Escribir cohete[j]
        FinPara
        Escribir ""
        Escribir "Lanzamiento en ",11-i
        Esperar 1 Segundo
    FinPara
    
    Para i<-1 hasta 15 Hacer
        Borrar Pantalla
        Para j<-i hasta 15 Hacer
            Escribir ""
        FinPara
        Para j<-1 hasta 8 Hacer
            Escribir cohete[j]
        FinPara
        si i>1 Entonces
            Escribir " * * * * "
        finsi
        Esperar 1/i Segundo
		
        Borrar Pantalla
        
        Esperar .2 Segundos
    FinPara
	escribir "El resultado final es: ",res,".";
	
	Escribir "                    x"
	Escribir "                   XX"
	Escribir "                 XXXXXX"
	Escribir "               XXXXXXXXXX"
	Escribir "             XXXXXXXXXXXXXX"
    Escribir "           XXXXXXXXXXXXXXXXXX"
	Escribir "         XXXXXXXXXXXXXXXXXXXXXX"
	Escribir "       XXXXXXXXXXXXXXXXXXXXXXXXXX"
	Escribir "     XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
	
	
	
FinAlgoritmo
