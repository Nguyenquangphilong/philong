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
   
    Stkv/Stbd = a;
    1+Ls = b;
    Kq = log(a)/log(b);
    
    cout<<"can so nam la: " << Kq << endl;
	
    return 0;
}
