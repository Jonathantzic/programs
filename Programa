#include <iostream>
#include <stdio.h>
#include <conio.h>
#include<string.h>
#include<stdlib.h> 
#include <cstring>
#include <sstream>
#include <cstdlib>
#include<windows.h>
#include<math.h>

using namespace std;

void suma();
void resta();
void multi();
void divi();
void par();
void conversionkm();
void palindromo();
void numroma();
void convnumalet();
void tablas();
void tablas1a10();
void tablagrafica();
void decabin();
void decahexa();
void figuras();
void movimiento();
void cajero();
void hipotenusa();

void gotoxy(int x1, int y1){
	HANDLE  hcon = GetStdHandle(STD_OUTPUT_HANDLE);
	COORD dwPos;
	dwPos.X = x1;
	dwPos.Y = y1;
	SetConsoleCursorPosition(hcon, dwPos);
}

char op;
int x=10, y=10;


void suma(){
int num1, num2, res;	
	
	cout<<"Ingrese un numero "<<endl;
	cin>>num1;
	
	cout<<"Ingrese un numero"<<endl;
	cin>>num2;
	
	res = num1 + num2;
	
	cout<<"El resultado de la suma es: "<<res<<endl;		
}

void resta(){
int num1, num2, res;	
	
	cout<<"Ingrese un numero "<<endl;
	cin>>num1;
	
	cout<<"Ingrese un numero"<<endl;
	cin>>num2;
	
	res = num1 - num2;
	
	cout<<"El resultado de la resta es: "<<res<<endl;
}

void multi(){
	int num1, num2, res;	
	
	cout<<"Ingrese un numero "<<endl;
	cin>>num1;
	
	cout<<"Ingrese un numero"<<endl;
	cin>>num2;
	
	res = num1 * num2;
	
	cout<<"El resultado de la multiplicacion es: "<<res<<endl;	
}

void divi(){
	int num1, num2, res;	
	
	cout<<"Ingrese un numero "<<endl;
	cin>>num1;
	
	cout<<"Ingrese un numero"<<endl;
	cin>>num2;
	
	res = num1 / num2;
	
	cout<<"El resultado de la divison es: "<<res<<endl;
}

void par(){
	int num;	
	
	cout<<"Ingrese un numero "<<endl;
	cin>>num;
	
	if(num%2==0){
	cout<<"El numero es par."; 
	}else{
		cout<<"El numero es impar.";
	}
}

void conversionkm(){
	int op=0; 	
    double	 n1, res;
    
    cout<<"Ingrese la cantidad que quiere convetir"<<endl;
    cin>>n1;
    
    cout<<" :.Seleccione la conversion que desea realizar.: "<<endl;
	cout<<"Op.1 Kilometros a millas. "<<endl;
	cout<<"Op.2 Kilometros a metros. "<<endl;
	cout<<"Op.3 Kilometros a pulgadas. "<<endl;	
	cout<<"Op.4 Millas a kilometros. "<<endl;
	cout<<"Op.5 Metros a kilometros. "<<endl;
	cout<<"Op.6 Pulgadas a kilometros. "<<endl;
	cout<<"Op.7 Libras a kilos. "<<endl;
	cout<<"Op.8 Kilos a libras. "<<endl;
	cin>>op;
	
switch (op){
	
	case 1:
		cout<<"Op.1 Kilometros a millas. "<<endl;
		res = n1 / 1.609;
		cout<<"La conversion es igual a: "<<res<<" millas.";
		cout<<"";
		cout<<"";
	break;
	
	case 2:
		cout<<"Op.2 Kilometros a metros. "<<endl;
		res = n1 * 1000;
		cout<<"La conversion es igual a: "<<res<<" metros.";
		cout<<"";
		cout<<"";
	break;
	
	case 3:
		cout<<"Op.3 Kilometros a pulgadas. "<<endl;	
		res = n1 * 39370;
		cout<<"La conversion es igual a: "<<res<<" pulgadas.";
		cout<<"";
		cout<<"";
	break;
	
	case 4:
		cout<<"Op.4 Millas a kilometros. "<<endl;
		res = n1 * 1.609;
		cout<<"La conversion es igual a: "<<res<<" kilometros.";
		cout<<"";
		cout<<"";
	break;
	
	case 5:
		cout<<"Op.5 Metros a kilometros. "<<endl;
		res = n1 / 0.001;
		cout<<"La conversion es igual a: "<<res<<" kilometros.";
		cout<<"";
		cout<<"";
	break;
	
	case 6:
		cout<<"Op.6 Pulgadas a kilometros. "<<endl;
		res = n1 / 39370;
		cout<<"La conversion es igual a: "<<res<<" kilometros.";
		cout<<"";
		cout<<"";
	break;
	
	case 7:
		cout<<"Op.7 Libras a kilos. "<<endl;
		res = n1 / 2.205;
		cout<<"La conversion es igual a: "<<res<<"kilos.";
		cout<<"";
		cout<<"";
	break;
	
	case 8:
		cout<<"Op.8 kilos a libras."<<endl;
		res = n1 * 2.205;
		cout<<"La conversion es igual a: "<<res<<"libras";
		cout<<"";
		cout<<"";
	break; 
}
}

void palindromo(){
	
	string p;
	string pr;
	int i=0;
	
	cout<<"Ingrese palabra a verificar: ";
	cin>>p;
	
	for(i=p.size()-1; i>=0; i--){
		pr += p[i];
	}
	
	if(p==pr){
		cout<<"La palabra "<<p<<" es palindroma.";
	}else{
		cout<<"La palabra "<<p<<" no es palindroma.";
	}
}

void numroma(){
	int num, a; 

cout <<"Conversion de numeros arabigos a romanos"<<endl;
cout <<"Escribe el numero a convertir"<<endl;
cin >> a;
num=a;

while(num!=0)
{
if (num<= 3999 && num>= 1000)
{
cout << "M";
num = num -1000;
}
else if(num <1000 && num>=900)
{
cout << "CM";
num = num - 900;
}
else if(num < 900 && num>500)
{
cout << "D";
num = num - 500;
}
else if (num == 500)
{
cout << "D";
num = num -500;
}
else if (num<500 && num>= 400)
{
cout << "CD";
num = num - 400;
}
else if (num<400 && num >99)
{
cout << "C";
num = num -100;
}
else if (num< 100 && num>89)
{
cout << "XC";
num = num - 90;
}
else if (num< 90 && num>59)
{
cout << "L";
num = num - 50;
}
else if(num<60 && num >50)
{
cout << "L";
num = num - 50;
}
else if (num ==50)
{
cout << "L";
num = num -50;
}
else if(num<50 && num>39)
{
cout << "XL";
num = num - 40;
}
else if(num< 40 && num> 10)
{
cout << "X";
num = num - 10;
}
else if(num == 10)
{
cout << "X";
num = num -10;
}
else if(num==9)
{
cout << "IX";
num = num - 9;
}
else if(num<=8 && num>=6)
{
cout << "V";
num = num - 5;
}
else if (num == 5)
{
cout << "V";
num = num - 5;
}
else if (num == 4)
{
cout << "IV";
num = num - 4;
}
else if (num<= 3 && num>=1)
{
cout << "I";
num = num - 1;
}
}
}

void convnumalet() {
	    int num;
    cout<<"Ingrese un numero"<<endl;
    cin>>num;
    
if((num<1)||(num>999)) cout<<"Ingrese un numero del 1 al 999."<<endl;
else{
    if(num>=900)   {cout<<"NOVECIENTOS " ;num=num-900;}
    else if(num>=800)   {cout<<"OCHOCIENTOS " ;num=num-800;}
    else if(num>=700)   {cout<<"SETECIENTOS " ;num=num-700;}
    else if(num>=600)   {cout<<"SEISCIENTOS " ;num=num-600;}
    else if(num>=500)   {cout<<"QUINIENTOS "  ;num=num-500;}
    else if(num>=400)   {cout<<"CUATROCIENTOS "   ;num=num-400;}
    else if(num>=300)   {cout<<"TRESCIENTOS " ;num=num-300;}
    else if(num>=200)   {cout<<"DOSCIENTOS "  ;num=num-200;}
    else if(num>100)    {cout<<"CIENTO "  ;num=num-100;}
    else if(num==100)  {cout<<"CIEN"     ;num=num-100;}
    if(num>90) {cout<<"NOVENTA Y "   ;num=num-90; }
    if(num==90)   {cout<<"NOVENTA"  ;num=num-90; }  
    if(num>80) {cout<<"OCHENTA Y "   ;num=num-80; }
    if(num==80)   {cout<<"OCHENTA"  ;num=num-80; }
    if(num>70) {cout<<"SETENTA Y "   ;num=num-70; }
    if(num==70)   {cout<<"SETENTA"  ;num=num-70; }
    if(num>60) {cout<<"SESENTA Y "   ;num=num-60; }
    if(num==60)   {cout<<"SESENTA"  ;num=num-60; }
    if(num>50) {cout<<"CINCUENTA Y " ;num=num-50; }
    if(num==50)   {cout<<"CINCUENTA"    ;num=num-50; }
    if(num>40) {cout<<"CUARENTA Y "  ;num=num-40; }
    if(num==40)   {cout<<"CUARENTA" ;num=num-40; }
    if(num>30) {cout<<"TREINTA Y "   ;num=num-30; }
    if(num==30)   {cout<<"TREINTA"  ;num=num-30; }
    if(num>20) {cout<<"VEINTI"       ;num=num-20; }
    if(num==20)   {cout<<"VEINTE"       ;num=num-20; }
    if(num>=16)    {cout<<"DIECI"        ;num=num-10; }
    else if(num==15)   {cout<<"QUINCE"       ;num=num-15; }
    else if(num==14)   {cout<<"CATORCE"  ;num=num-14; }
    else if(num==13)   {cout<<"TRECE"        ;num=num-13; } 
    else if(num==12)   {cout<<"DOCE"     ;num=num-12; }
    else if(num==11)   {cout<<"ONCE"     ;num=num-11; }
    else if(num==10)   {cout<<"DIEZ"     ;num=num-10; }      
    if(num==9)    {cout<<"NUEVE"        ;num=num-9;  }
    if(num==8)    {cout<<"OCHO"     ;num=num-8;  }
    if(num==7)    {cout<<"SIETE"        ;num=num-7;  }
    if(num==6)    {cout<<"SEIS"     ;num=num-6;  }
    else if(num==5)    {cout<<"CINCO"        ;num=num-5;  }
    else if(num==4)    {cout<<"CUATRO"       ;num=num-4;  }
    else if(num==3)    {cout<<"TRES"     ;num=num-3;  }
    else if(num==2)    {cout<<"DOS"      ;num=num-2;  }
    else if(num==1)    {cout<<"UNO"      ;num=num-1;  }
       
}
    cout<<endl;
    
cin.ignore();
}

void tablas(){
	int num, n;
	
	cout<<"Ingrese un numero: "<<endl;
	cin>>num;
		
	cout<<"Ingrese limite de la tabla: "<<endl;
	cin>>n;
		
    cout<<"Tabla de multiplicar del "<<num<<endl;
	
	for
	(int i=1; i<=n; i++){
		cout<<num<<" * "<<i<<" = "<<num*i<<endl;
	}
}

void tablas1a10(){
	    
		cout<<"Tabla del 1"<<endl;	
     	cout<<"1  *  1  =  1"<<endl;
     	cout<<"1  *  2  =  2"<<endl;
     	cout<<"1  *  3  =  3"<<endl;
     	cout<<"1  *  4  =  4"<<endl;
     	cout<<"1  *  5  =  5"<<endl;
     	cout<<"1  *  6  =  6"<<endl;
     	cout<<"1  *  7  =  7"<<endl;
     	cout<<"1  *  8  =  8"<<endl;
     	cout<<"1  *  9  =  9"<<endl;
     	cout<<"1  *  10  =  10"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 2"<<endl;	
     	cout<<"2  *  1  =  2"<<endl;
     	cout<<"2  *  2  =  4"<<endl;
     	cout<<"2  *  3  =  6"<<endl;
     	cout<<"2  *  4  =  8"<<endl;
     	cout<<"2  *  5  =  10"<<endl;
     	cout<<"2  *  6  =  12"<<endl;
     	cout<<"2  *  7  =  14"<<endl;
     	cout<<"2  *  8  =  16"<<endl;
     	cout<<"2  *  9  =  18"<<endl;
     	cout<<"2  *  10  =  20"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 3"<<endl;	
     	cout<<"3  *  1  =  3"<<endl;
     	cout<<"3  *  2  =  6"<<endl;
     	cout<<"3  *  3  =  9"<<endl;
     	cout<<"3  *  4  =  12"<<endl;
     	cout<<"3  *  5  =  15"<<endl;
     	cout<<"3  *  6  =  18"<<endl;
     	cout<<"3  *  7  =  21"<<endl;
     	cout<<"3  *  8  =  24"<<endl;
     	cout<<"3  *  9  =  27"<<endl;
     	cout<<"3  *  10  =  30"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 4"<<endl;	
     	cout<<"4  *  1  =  4"<<endl;
     	cout<<"4  *  2  =  8"<<endl;
     	cout<<"4  *  3  =  12"<<endl;
     	cout<<"4  *  4  =  16"<<endl;
     	cout<<"4  *  5  =  20"<<endl;
     	cout<<"4  *  6  =  24"<<endl;
     	cout<<"4  *  7  =  28"<<endl;
     	cout<<"4  *  8  =  32"<<endl;
     	cout<<"4  *  9  =  36"<<endl;
     	cout<<"4  *  10  =  40"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 5"<<endl;	
     	cout<<"5  *  1  =  5"<<endl;
     	cout<<"5  *  2  =  10"<<endl;
     	cout<<"5  *  3  =  15"<<endl;
     	cout<<"5  *  4  =  20"<<endl;
     	cout<<"5  *  5  =  25"<<endl;
     	cout<<"5  *  6  =  30"<<endl;
     	cout<<"5  *  7  =  35"<<endl;
     	cout<<"5  *  8  =  40"<<endl;
     	cout<<"5  *  9  =  45"<<endl;
     	cout<<"5  *  10  =  50"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 6"<<endl;	
     	cout<<"6  *  1  =  6"<<endl;
     	cout<<"6  *  2  =  12"<<endl;
     	cout<<"6  *  3  =  18"<<endl;
     	cout<<"6  *  4  =  24"<<endl;
     	cout<<"6  *  5  =  30"<<endl;
     	cout<<"6  *  6  =  36"<<endl;
     	cout<<"6  *  7  =  42"<<endl;
     	cout<<"6  *  8  =  48"<<endl;
     	cout<<"6  *  9  =  54"<<endl;
     	cout<<"6  *  10  =  60"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 7"<<endl;	
     	cout<<"7  *  1  =  7"<<endl;
     	cout<<"7  *  2  =  14"<<endl;
     	cout<<"7  *  3  =  21"<<endl;
     	cout<<"7  *  4  =  28"<<endl;
     	cout<<"7  *  5  =  35"<<endl;
     	cout<<"7  *  6  =  42"<<endl;
     	cout<<"7  *  7  =  49"<<endl;
     	cout<<"7  *  8  =  56"<<endl;
     	cout<<"7  *  9  =  63"<<endl;
     	cout<<"7  *  10  =  70"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 8"<<endl;	
     	cout<<"8  *  1  =  8"<<endl;
     	cout<<"8  *  2  =  16"<<endl;
     	cout<<"8  *  3  =  24"<<endl;
     	cout<<"8  *  4  =  32"<<endl;
     	cout<<"8  *  5  =  40"<<endl;
     	cout<<"8  *  6  =  48"<<endl;
     	cout<<"8  *  7  =  56"<<endl;
     	cout<<"8  *  8  =  64"<<endl;
     	cout<<"8  *  9  =  72"<<endl;
     	cout<<"8  *  10  =  80"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 9"<<endl;	
     	cout<<"9  *  1  =  9"<<endl;
     	cout<<"9  *  2  =  18"<<endl;
     	cout<<"9  *  3  =  27"<<endl;
     	cout<<"9  *  4  =  36"<<endl;
     	cout<<"9  *  5  =  45"<<endl;
     	cout<<"9  *  6  =  54"<<endl;
     	cout<<"9  *  7  =  63"<<endl;
     	cout<<"9  *  8  =  72"<<endl;
     	cout<<"9  *  9  =  81"<<endl;
     	cout<<"9  *  10  =  90"<<endl;
     	cout<<""<<endl;
     	
     	cout<<"Tabla del 10"<<endl;	
     	cout<<"10  *  1  =  10"<<endl;
     	cout<<"10  *  2  =  20"<<endl;
     	cout<<"10  *  3  =  30"<<endl;
     	cout<<"10  *  4  =  40"<<endl;
     	cout<<"10  *  5  =  50"<<endl;
     	cout<<"10  *  6  =  60"<<endl;
     	cout<<"10  *  7  =  70"<<endl;
     	cout<<"10  *  8  =  80"<<endl;
     	cout<<"10  *  9  =  90"<<endl;
     	cout<<"10  *  10  =  10"<<endl;
     	cout<<""<<endl;
}

void tablagrafica(){
int n1, n2, n3, r1, r2, r3, res;	
	
	cout<<"Ingrese el multiplicando"<<endl;
	cin>>n1;
	 
	cout<<"Ingrese el decimal del multiplicador"<<endl;
	cin>>n2;
	
	cout<<"Ingrese la unidad del multiplicador"<<endl;
	cin>>n3;
	
	r1 = n1 * n2;
	r2 = n1 * n3;
	r3 = r1 * 10;
	res = r2 + r3;
	
	cout<<"El resultado de la suma es: "<<endl;
	cout<<""<<endl;
	cout<<" "<<n1<<endl;
	cout<<"X"<<n2<<n3<<endl;
	cout<<"-----"<<endl;	
    cout<<" "<<r2<<endl;
    cout<<r1<<endl;
	cout<<"-------"<<endl;
	cout<<res<<endl;
	
}

void decabin() {
	int num;
	string bin = "";
	  
	cout<<"Ingrese un numero decimal."<<endl;
	cin>>num;
	
	if(num>0){
	while (num>0){
	if(num%2==0){
		bin = "0"+bin;
	}else{ bin ="1"+bin; }	
	num = (int)num/2; }
	}else if(num==0){
		bin = "0";
	}else{
		bin = "No se puede realizar la conversion. Ingrese solo numeros positivos";
	} cout<<"El resultado de la conversion es: "<<bin<<endl;
}

void decahexa(){
	int digitoex[20];
    int dec, resi, resul, i = 0;

    cout << "Ingrese un numero decimal" << endl;
    cin >> dec;

    do
    {
        resi = dec % 16;
        resul = dec / 16;
        digitoex[i] = resi;
        dec = resul;
        i++;
    } while (resul > 15);

    digitoex[i] = resul;

    cout << "El equivalente en hexadecimal es: ";

    for (int j = i; j >= 0; j--)
    {
        if (digitoex[j] == 10)
        {
            cout << "A";
        }
        else if (digitoex[j] == 11)
        {
            cout << "B";
        }
        else if (digitoex[j] == 12)
        {
            cout << "C";
        }
        else if (digitoex[j] == 13)
        {
            cout << "D";
        }
        else if (digitoex[j] == 14)
        {
            cout << "E";
        }
        else if (digitoex[j] == 15)
        {
            cout << "F";
        }
        else
        {
            cout << digitoex[j];
        }   
    }
	
}

void figuras() {
    int op;
    cout<<"ingrese la opcion: \n";
    cout<<"1.trigulo \n";
    cout<<"2.cuadrado \n";
    cout<<"3.rectangulo \n";
	cin>>op;
    switch(op){
        case 1:{
            cout<<"      / \\ \n";
            cout<<"     /   \\ \n";
            cout<<"    /     \\ \n";
            cout<<"   /       \\ \n"   ;
            cout<<"  /_________\\ \n\n";
            break;
        }
        case 2:{
            cout<<"* * * * * * \n";
            cout<<"*         * \n";
            cout<<"*         * \n";
            cout<<"*         * \n";
            cout<<"*         * \n";
            cout<<"* * * * * * \n\n";           
            break;
        }
        case 3:{
            cout<<"* * * * * * * * \n";
            cout<<"*             * \n";
            cout<<"*             * \n";
            cout<<"*             * \n";
            cout<<"* * * * * * * * \n\n";
            break;
        }

    }
    }

	

void movimiento(){
	
		while(op!='z'){
		system("cls");
		gotoxy(x,y);
		
		op=getch();
		switch(op){
			case 'w': y--; break;
			case 's': y++; break;
			case 'a': x--; break;
			case 'd': x++; break;
		}
		
	
}
}

void cajero(){
		int a = 1000, op;
	float extra, sal = 0, retiro, s, n;
	
	cout<<"Bienvenido al Cajero."<<endl;
	cout<<"1. Ingresar dinero en cuenta."<<endl;
	cout<<"2. Retirar dinero de la cuenta."<<endl;
	cout<<"3. Salir."<<endl;
	cin>>op;
	
	switch(op){
		case 1:
			cout<<"Ingrese la cantidad de dinero a ingresar: "<<endl;
			cin>>extra;
			sal = a + extra;
			cout<<"Dinero en cuenta: "<<sal;		
			break;
			
		case 2:
			cout<<"Ingrese la cantidad de dinero a retirar: "<<endl;
			cin>>retiro;
			if(retiro>a){
				cout<<"No tiene esa cantidad de dinero"<<endl;
			}else{
				sal = a-retiro;
				cout<<"Dinero en cuenta: "<<sal;
			}
		break;	
		case 3:
		break;
		}	
}

void hipotenusa(){
	
	int co, ca;
	float h;
	
	cout<<"Digite el cateto opuesto: "<<endl;
	cin>>co;
	
	cout<<"Digite el cateto adyacente: "<<endl;
	cin>>ca;
	
	h = sqrt (pow(co,2)+pow(ca,2));
	
	cout<<"La hipotenusa es igual a :"<<h<<endl;
}

int main() {
	int opmenu;
	cout<<""<<endl;
	cout<<"Por favor seleccione la opcion del numero que desea digitar, ingresando su numeral";
	cout<<endl;
	cout<<"1. Suma"<<endl;
	cout<<"2. Resta"<<endl;
	cout<<"3. Multiplicacion"<<endl;
	cout<<"4. Division"<<endl;
	cout<<"5. Par o impar"<<endl;
	cout<<"6. Conversion de unidades de medida"<<endl;
	cout<<"7. Palindromo"<<endl;
	cout<<"8. Conversion de numeros arabigos a romanos"<<endl;
	cout<<"9. Conversion de numeros a letras"<<endl;
	cout<<"10. Tabla de multiplicar"<<endl;
	cout<<"11. Tabla de multiplicar del 1 al 10"<<endl;
	cout<<"12. Tabla de multiplicar grafica"<<endl;
	cout<<"13. Conversion de numeros decimales a binario"<<endl;
	cout<<"14. Conversion de numeros decimales a hexadecimales"<<endl;
	cout<<"15. Figuras geometricas basicas"<<endl;
	cout<<"16. Movimiento"<<endl;
	cout<<"17. Cajero automatico"<<endl;
	cout<<"18. Hipotenusa"<<endl;
	
	
	cin>>opmenu;
	system ("cls"); 
	switch (opmenu){
case 1:
			int r1, opc1;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc1;
			system("cls");

			if(opc1 == 1)
			{
			cout<<"suma"<<endl;
			cout<<""<<endl;
			suma();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r1;
			system ("cls");
			switch (r1){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 2:
			int r2, opc2;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc2;
			system("cls");

			if(opc2 == 1)
			{
			cout<<"resta"<<endl;
			cout<<""<<endl;
			resta();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r2;
			system ("cls");
			switch (r2){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 3:
			int r3, opc3;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc3;
			system("cls");

			if(opc3 == 1)
			{
			cout<<"multiplicacion"<<endl;
			cout<<""<<endl;
			multi();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r3;
			system ("cls");
			switch (r3){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 4:
			int r4, opc4;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc4;
			system("cls");

			if(opc4 == 1)
			{
			cout<<"Division"<<endl;
			cout<<""<<endl;
			divi();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r4;
			system ("cls");
			switch (r4){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 5:
			int r5, opc5;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc5;
			system("cls");

			if(opc5 == 1)
			{
			cout<<"par o impar"<<endl;
			cout<<""<<endl;
			par();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r5;
			system ("cls");
			switch (r5){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 6:
			int r6, opc6;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc6;
			system("cls");

			if(opc6 == 1)
			{
			cout<<"conversion de unidades de medida"<<endl;
			cout<<""<<endl;
			conversionkm();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r6;
			system ("cls");
			switch (r6){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 7:
			int r7, opc7;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc7;
			system("cls");

			if(opc7 == 1)
			{
			cout<<"palindromo"<<endl;
			cout<<""<<endl;
			palindromo();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r7;
			system ("cls");
			switch (r7){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 8:
			int r8, opc8;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc8;
			system("cls");

			if(opc8 == 1)
			{
			cout<<"conversion de numeros arabigos a romanos"<<endl;
			cout<<""<<endl;
			numroma();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r8;
			system ("cls");
			switch (r8){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 9:
			int r9, opc9;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc9;
			system("cls");

			if(opc9 == 1)
			{
			cout<<"conversion de numeros a letras"<<endl;
			cout<<""<<endl;
			convnumalet();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r9;
			system ("cls");
			switch (r9){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 10:
			int r10, opc10;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc10;
			system("cls");

			if(opc10 == 1)
			{
			cout<<"tabla de multiplicar"<<endl;
			cout<<""<<endl;
			tablas();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r10;
			system ("cls");
			switch (r10){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 11:
			int r11, opc11;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc11;
			system("cls");

			if(opc11 == 1)
			{
			cout<<"Tablas de multiplicar del 1 al 10"<<endl;
			cout<<""<<endl;
			tablas1a10();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r11;
			system ("cls");
			switch (r11){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 12:
			int r12, opc12;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc12;
			system("cls");

			if(opc12 == 1)
			{
			cout<<"Tabla de multiplicar grafica"<<endl;
			cout<<""<<endl;
			tablagrafica();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r12;
			system ("cls");
			switch (r12){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 13:
			int r13, opc13;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc13;
			system("cls");

			if(opc13 == 1)
			{
			cout<<"conversion de numeros decimales a binario"<<endl;
			cout<<""<<endl;
			decabin();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r13;
			system ("cls");
			switch (r13){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 14:
			int r14, opc14;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc14;
			system("cls");

			if(opc14 == 1)
			{
			cout<<"conversion de numeros decimales a hexadecimales"<<endl;
			cout<<""<<endl;
			decahexa();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r14;
			system ("cls");
			switch (r14){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 15:
			int r15, opc15;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc15;
			system("cls");

			if(opc15 == 1)
			{
			cout<<"figuras geometricas basicas"<<endl;
			cout<<""<<endl;
			figuras();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r15;
			system ("cls");
			switch (r15){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 16:
			int r16, opc16;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc16;
			system("cls");

			if(opc16 == 1)
			{
			cout<<"movimiento"<<endl;
			cout<<""<<endl;
			movimiento();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r16;
			system ("cls");
			switch (r16){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 17:
			int r17, opc17;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc17;
			system("cls");

			if(opc17 == 1)
			{
			cout<<"cajeto automatico"<<endl;
			cout<<""<<endl;
			cajero();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r17;
			system ("cls");
			switch (r17){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;

case 18:
			int r18, opc18;
			
			cout<<"Presione 1 Para iniciar"<<endl;
			cin>>opc18;
			system("cls");

			if(opc18 == 1)
			{
			cout<<"hipotenusa"<<endl;
			cout<<""<<endl;
			hipotenusa();
			cout<<""<<endl;
			cout<<"Presiones 1 para regresar y 0 para finalizar"<<endl;
			cin>>r18;
			system ("cls");
			switch (r18){
			case 1:
            main();
			break;
			case 0:
			return 0;
			break;
			}
}break;


}
}
