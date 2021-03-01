# SOURCE-CODE-PERTEMUSN-4
print ("pilih fungsi perhitungan yang ada di bawah") 
print ("1. faktorial") 
print ("2.sisa hasil bagi") 
print ("3.bilangan pangkat 3") 
pilihan = int(input("masukkan pilihan anda")) 
if pilihan == 1:     
   x = int(input("masukkan angka yang akan difaktorial"))     
   def faktorial (x):         
      if x == 0:             
        return 1         
      else:            
        return x*faktorial(x-1)     
   print(x ,"faktorialnya adalah",faktorial (x)) 
elif pilihan == 2:     
    x = int(input("masukkan angka yang akan dibagi"))     
    y = int(input("masukkan angka pembagi"))     
    def sisahasilbagi (x):         
      if x == 0:             
        return 1         
      else:             
        return x%y     
    print("sisa hasil bagi adalah",sisahasilbagi (x)) 
elif pilihan == 3:     
    x = int(input("masukkan angka yang akan di pangkat3"))     
    def pangkat3 (x):         
    if x == 0:             
      return 1         
    else:             
      return x*x*x     
   print("hasil bilangan pangkat 3 adalah",pangkat3 (x)) 
   else:     
    print("pilihan yang anda mau tidak terdaftar")
