# calculator
kodi asrulebs kalkulatoris funqcias magram aketebs martiv magalitebs mxolod ori cvladis dajameba gamokleba gamravleba an da gayofa sheudzlia datanili aqvs komentarebi rogorc cpp komentarebi aseve javadoc komentarebi aseve aqvs logirebis ori shetyobineba ERROR da INFO.


#include<iostream>

using namespace std;

/**
 * main part calculator
 *@author nika
 *
 */
double calculate(double num , char x, double num1){  // mtavari funqcia kalkulatori itvlis jams, sxvaobas ,namravls da gayofas
    double num2;
    string error = "ERROR! wrong char";
    if (x == '+') 
    {
        num2 = num + num1;
    }
    elif(x == '-')
    {
        num2 = num - num1;
    }
    elif(x == '*' )
    {
        num2 = num * num1;
    }
    elif(x == '/')
    {
        num2 = num / num1;
    }
    else{
        return error;
    }
    return num2;
}
int main()
{
    string info = "INFO: program end well with no problems"
    cout << "calculator";
    double num;
    char x;
    double num1;
    double num3;
    cin << num << x << num1 ;   // momxmarebels sheyavs magaliti
    num3 = calculate(num, x , num1)
    cout << num3 << endl << info << endl ; //gamoaqvs pirdapiri pasuxi
}
