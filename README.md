//ACTIVITY#4 DATASTR
//Junio,James Carl S.
//BSIT-2J

#include <iostream>
using namespace std;
//FOR LOOP
int main() {
     cout << "GET READY" << endl;

    for (int i = 10; i >= 1; i--) {
        cout << i << endl;
    }

    cout << "Happy Teacher's Day!" << endl;

    return 0;
}

#include <iostream>
using namespace std;
//WHILE LOOP

int main() {
     string sagot;
     while(sagot != "yes" ){
     cout << "Makaka pasa po ba kami mam?" << endl;
     getline(cin,sagot);
     
     if(sagot =="yes" ){
     cout << "Thankyou Mam ❤" << endl;
     
     }else{
     cout << "Ipasamo na po kami please \n" << endl;
     }
       
     }
             
    return 0;
}



#include <iostream>
using namespace std;
//DO WHILE LOOP
int main() {
     
     float i;
     
     do{
     cout << "Give me 1.00 grades" << endl;
     cin >> i;
     cout << "You have entered" << i<< endl;
     }
     while(i!=1.00);
     cout << "Thankyou" << endl;
     
     
    return 0;
}
