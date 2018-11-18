# CalculatorSederhana
https://notebooks.azure.com/rizkiar111299/libraries/Python-Beginer


def Penjumlahan():
    print "########################"
    print "#  Program Calculator  #"
    print "#     By Rizki A.R     #"
    print "########################"
    print "\n"
    print "#############"
    print "#Penjumlahan#"
    print "#############"
    nilai1 = input("Masukan Nilai Disini :")
    nilai2 = input("Masukan Nilai Disini :")
    proses = nilai1 + nilai2
    print "{} + {} = {}".format(nilai1,nilai2,proses)
def Pengurangan():
    print "########################"
    print "#  Program Calculator  #"
    print "#     By Rizki A.R     #"
    print "########################"
    print "\n"
    print "#############"
    print "#Pengurangan#"
    print "#############"
    nilai1 = input("Masukan Nilai Disini :")
    nilai2 = input("Masukan Nilai Disini :")
    proses = nilai1 - nilai2
    print "{} - {} = {}".format(nilai1,nilai2,proses)
def Perkalian():
    print "########################"
    print "#  Program Calculator  #"
    print "#     By Rizki A.R     #"
    print "########################"
    print "\n"
    print "#############"
    print "#Penjumlahan#"
    print "#############"
    nilai1 = input("Masukan Nilai Disini :")
    nilai2 = input("Masukan Nilai Disini :")
    proses = nilai1 * nilai2
    print "{} * {} = {}".format(nilai1,nilai2,proses)
def Pembagian():
    print "########################"
    print "#  Program Calculator  #"
    print "#     By Rizki A.R     #"
    print "########################"
    print "\n"
    print "#############"
    print "#Penjumlahan#"
    print "#############"
    nilai1 = input("Masukan Nilai Disini :")
    nilai2 = input("Masukan Nilai Disini :")
    proses = nilai1 + nilai2
    print "{} / {} = {}".format(nilai1,nilai2,proses)
def menu():
    print "########################"
    print "#  Program Calculator  #"
    print "#     By Rizki A.R     #"
    print "########################"
    print "\n"
    print "#################"
    print "#      MENU     #"
    print "#[1] Penjumlahan#"
    print "#[2] Pengurangan#"
    print "#[3] Perkalian  #"
    print "#[4] Pembagian  #"
    print "#################"
    pilihan = input("Masukan Number Menu :")
    if pilihan == 1:
        Penjumlahan()
    elif pilihan == 2:
        Pengurangan()
    elif pilihan == 3:
        Perkalian()
    elif pilihan == 4:
        Pembagian()
    else:
        print "Input Tidak Ada!!!"
        
print menu()
