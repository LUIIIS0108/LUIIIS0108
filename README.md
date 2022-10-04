public class TareaPractica{
    
    public string ejercicio1(int num1, int num2, int num3){

        if(num1<num2)&(num2<num3){

		return num3+", "+num2+", "+num1;
	}
	if (num2<num1)(num1<num3){
		return num3+", "+num1+", "+num2;
	}
	if (num3<num1)(num1<num2){

		return num2+", "+num1+", "+num3;
	}
	if (num1<num3)(num3<num2){

		return num2+", "+num3+", "+num1;
	}
	if (num2<num3)(num3<num1){

		return num1+", "+num3+", "+num2;
	}
	if (num3<num2)(num2<num1){

		return num1+", "+num2+", "+num3;
	}
}
	
	public bool ejercicio2 (int A, int B, int C, double Resultado1, double Resultado2){
	
	If ((B*B)-(4*A*C))≥0){
	Resultado1 = (-B/2*A)-(Math.sqrt(B*B)-4*A*C) / 2*A)
	Resultado2 = (-B/2*A)+(Math.sqrt(B*B)-4*A*C) / 2*A)
	
	return = True;
	}
	else{
	return = False;
	}
}
	



	public bool AñoBisiesto (int Año){
	if(Año>400 & Año<500)or (Año>800 & Año<900)or (Año>1200 & Año<1300)or (Año>1600 & Año<1700)or (Año>2000 & Año<2100) {
		if(Año%4==0){
			return = True;
		}

		else{
		return = False;
		}
	}
	else{
	return = False;
	}		
}


	public string Hora (int Hora, int Minutos, int Segundos){
	
	if(Hora≥0)&(Hora≤24){

		if(Minutos≥0)&(minutos≤60){
		
			if(Segundos≥0)&(Segundos≤24){

				return "La hora es "+ Hora + ":" + Minutos + ":" + Segundos;
		

			else{
				return "El valor de los segundos no es valido";

		else{
			
			return "El valor de los Minutos no es valido";
			

	else{
		return "El valor de las horas no es valido";

	
		
}


	public string Temperaturas (int Escala, char Temperatura){
		
		if(Temperatura.equals("C")){

			TemperaturaF= ((9/5*Escala)+32);
			TemperaturaK= (Escala+273);
			return "Sus equivalentes son "+TemperaturaF+" Fahrenheit, y "+TemperaturaK+" Kelvin";
		}
		else{
		if (Temperatura.equals("F")){
			TemperaturaC= (5(Escala-32))/9);
			TemperaturaK= (5(Escala-32))/9)+273;
			return "Sus equivalentes son "+TemperaturaC+" Celsius, y "+TemperaturaK+" Kelvin";
			}
		}
		else{
		if (Temperatura.equals("K")){
			TemperaturaF= (9*(Escala-273))/5+32;
			TemperaturaC= (Escala-273);
			return "Sus equivalentes son "+TemperaturaF+" Fahrenheit, y "+TemperaturaC+" Celsius";
			}
		}
		else{

			return "La temperatura ingresada no se encuentra dentro de los parametros establecidos";
		}
			


