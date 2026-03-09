2. Identify which class method is called What is the output of the program? Why are the two lines different?
outpunya adalah 
Vehicle is moving
Car is moving

line pertama memanggil method pada Vehicle
line kedua memanggil method pada Car


Dua barisnya berbeda karena biarpun kedua objek di deklarasikan sebagai Vehicle, tapi baris kedua menunjuk kepada objek Car. Jadi v1.move(); memanggil method pada Vehicle, tetapi v2.move(); memanggil method override pada Car.
