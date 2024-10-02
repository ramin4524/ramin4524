def giris():
    sifre = "gizli123"
    kullanici_sifre = input("Şifrenizi girin: ")

    if kullanici_sifre == sifre:
        print("Giriş başarılı!")
    else:
        print("Şifre hatalı.")
        
