#include <iostream>
#include <math.h>
using namespace std;

int main()
{
    double Stbd, Stkv, Kq, Ls; a; b;

    cout << "Nhap so tien gui: ";
    cin >> Stbd;

    cout << "Nhap so tien ky vong: ";
    cin >> Stkv;

    cout << "Nhap lai suat theo nam: ";
    cin >> Ls;
   
    a=Stkv/Stbd;
    b=1+Ls;
    Kq = log(a)/log(b);
    
    cout<<"can so nam la: " << Kq << endl;
	
    return 0;
}
