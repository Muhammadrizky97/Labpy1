# Labpy1

Program mencari bilangan terbesar dari 3 buah bilangan 

Alur algoritmanya adalah dengan medefinisikan perulangan dengan mengetik (def pengulangan():)

begini contoh programnya

def pengulangan():
    print ('Masukkan 3 bilangan yang diinginkan!')
    a=int(input('Bilangan Pertama : '))
    b=int(input('Bilangan Kedua   : '))
    c=int(input('Bilangan Ketiga  : '))

    if a>b:
        if a>c:
            print ('Bilangan terbesarnya adalah :',a)
        else:
            print ('Bilangan terbesarnya adalah :',c)
    else:
        if b>c:
            print ('Bilangan terbesarnya adalah :',b)
        else:
            print ('Bilangan terbesarnya adalah :',c)

    print ('')
    print ('Ingin coba lagi? (Y/T)')
    x=input()
    if x=='Y':
        return pengulangan()
    if x=='T':
        print('Terimakasih telah menggunakan program ini.')

pengulangan()


begini lah programnya,di program ini sudah terlihat alurnya gimana
sekian dan terimakasih
![ssprogram1](https://user-images.githubusercontent.com/43899133/52514547-5875ee00-2c45-11e9-9489-4281cfc79df1.jpg)



Ini screenshot hasil program tersebut


