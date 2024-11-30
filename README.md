//Given a person's age, Find if they should get a during license or not.
#include <iostream>
using namespace std;

int main() {
    int age; // Use lowercase 'age' for consistent naming conventions
    cout << "Enter your age: ";
    cin >> age;

    // Check eligibility for a driving license
    if (age >= 18) {
        cout << "Eligible for a driving license." << endl;
    } else {
        cout << "Not eligible for a driving license." << endl;
    }

    return 0;
}
