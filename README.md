#include <iostream>
#include <cstdlib>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <conio.h>
#include <iomanip>



using namespace std;



int main()
{
    const int DAYS = 7;
    const int MAX = 12;

    char star[DAYS][MAX] = {
        "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"
    };
    for (int j = 0; j < DAYS; j++) {
        cout << star[j] << endl;
    }


    return 0;
}
