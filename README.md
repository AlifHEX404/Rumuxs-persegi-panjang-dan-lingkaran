# Rumuxs-persegi-panjang-dan-lingkaran



                #include <iostream>
                #include<cstdlib>
                using namespace std;
                int pilihan;
                int main ()

                {system ("color e");
                    int p,l,luas,r,m,E;

                atas :
                cout<<"\n|==============================================|\n";
                cout<<"|================ ALIF MUSTAFANAH =============|\n";
                cout<<"|================= NIM 311810345 ==============|\n";
                cout<<"|============= PROGRAM MENGHITUNG LUAS ========|\n";
                cout<<"|==============================================|\n";

                cout << " \nDaftar rumus bahasa pemrograman : \n";
                cout << " \n1. Luas Persegi panjang \n2. EXIT\n3. Luas Lingkaran\n";
                cout << " \nMasukan pilihan anda (1-3 ): ";
                cout << " \n---------------------------------\n ";
                cin >> pilihan;
                    switch (pilihan ){
                        case 1:

                cout<<"masukan panjang persegi panjang : ";
                cin>>p;
                cout<<"masukan lebar persegi panjang : ";
                cin>>l;
                luas=p*l;
                cout<<"---------------------------------\n";
                cout<<"luas persegi panjang adalah "<<luas;
                       goto atas;

                        case 2:

                cout<<"|==============================================|\n";
                cout<<"|================ ALIF MUSTAFANAH =============|\n";
                cout<<"|================== TERIMAKASIH ===============|\n";
                cout<<"|============ PRESS ENTER TO EXIT =============|\n";
                cout<<"|==============================================|\n";

                return 0;

                case 3:

                    float phi=3.14,c=89.88,m,E;

                cout<<"masukan jari jari lingkaran : ";
                cin>>r;
                luas=phi*r*r;
                cout<<"--------------------------------\n";
                cout<<"luas lingkaran adalah "<<luas;
                 goto atas;

                return 0;
                        }
                }
