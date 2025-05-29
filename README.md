#include <iostream>
using namespace std;

int main() 
{
    double N1, N2, N3;
    double P;

    cout << "Ingrese la primera nota: ";
    cin >> N1;
    cout << "Ingrese la segunda nota: ";
    cin >> N2;
    cout << "Ingrese la tercera nota: ";
    cin >> N3;

    P = (N1 + N2 + N3) / 3.0;

    cout << "Promedio: " << P << endl;

    if (P >= 70.0) {
        cout << "El alumno APRUEBA el curso." << endl;
    } else {
        cout << "El alumno REPRUEBA el curso." << endl;
    }

    return 0;
}
