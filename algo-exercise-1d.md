#include <iostream>

using namespace std;

struct Patient {
    int patientId;
    string patientFirstName;
    string patientLastName;
    bool diseaseOrIllness;
    char gender;
    int age;
};
    
int main()
{
    
    struct Patient patientRecord;
    
    patientRecord.patientId = 1000002;
    patientRecord.patientFirstName = "Gracia";
    patientRecord.patientLastName = "Mbuyi";
    patientRecord.diseaseOrIllness = false;
    patientRecord.gender = 'M';
    patientRecord.age = 35;
    
    cout<<"Display Patient full name: " + patientRecord.patientFirstName + ' ' + patientRecord.patientLastName;

    return 0;
}
