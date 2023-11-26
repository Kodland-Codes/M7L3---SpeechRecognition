# M7L3 SpeechRecognition Kütüphanesi

## GitBash İndirmek
1- Bu Github deposunu local'e yani bilgisayarınıza indirebilmek için Git Bash programına ihtiyahıcınız var.
Bu linke tıklayarak indirebilirsiniz:
#### Windows kullananlar için:
https://git-scm.com/download/win linkini açıp `Click here to download` linkine tıklayın.
#### MacOS kullananlar için:
https://git-scm.com/download/mac linkini açıp `Click here to download` linkine tıklayın.
#### Linux/Unix kullananlar için:
https://git-scm.com/download/linux linkini açıp `Click here to download` linkine tıklayın.

Bilgisayarınıza kurarken çıkan pencerelerin hepsine `Next` diyerek devam edin.
## Projenizi kaydetmek istediğiniz klasöre gitmek:
1-GitBash terminalinde projenizi kaydetmek istediğiniz yere gidiniz
İşinize yarayan komutlar
`cd <klasör_ismi>` sizi klasörün içine alacak
`ls` Bulunduğunuz klasörün içindeki dosyları gösterecek 
`pwd` Bulunduğunuz klasörün adresi
`mkdir <klasör_ismi>` Yeni bir klasör oluşturmak

Önreğin, ben masaüstünde kaydetmek için bu komutları kullandım:
```
cd ~
cd Desktop
mkdir Bitirme_Projesi
cd Bitirme_Projesi
```

## Github deposunu localinize indirmek

Projeyi kaydetmek istediğiniz klasörün içindeyseniz, aşağıdaki komutu Gitbash terminaline girerek bu github deposunu bilgisayarınıza indirebilirsiniz:
```
git clone https://github.com/Kodland-Codes/M7L3---SpeechRecognition.git
```

## Sanal ortamı aktifleştirmek ve kütüphaneleri indirmek

Projenizi VSCode'da açınız ve terminalde aşağıdaki komutu giriniz:

`NOT: bilgisayarı kapatıp açtığınz zaman da bu komutu her zaman girmeniz gerekiyor`

### Mac kullananlar için: 
```
source venv/bin/activate
pip install -r requirements.txt
```

### Windows kullananlar için: 
PowerShell'i yönetici olarak çalıştırıp bu komutu girip entere tıklayınız:
```
set-executionpolicy remotesigned
```
Size onaylamanız için bir soru soracak, büyük `A` harfini yazıp enter'e tıklayın.

Şimdi VSCode terminalinde bunları yazıp enter'e tıklayın

```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```


## Projeyi çalıştırmak
### Yöntem 1: VSCode terminalinden
NOT: VScode terminalinde projenin klasöründe olduğunuzdan ve doğru sanal ortamı kullandığınızdan emin olunuz.
Bu konmutu VSCode terminalinde yazarak projeyi çalıştırabilirsiniz:
```
python speech.py
```

### Yöntem 2: VScode çalıştır butonundan
Eğer bu yöntemi kullanmak istiyorsanız VSCode'da kullandığınız İnterpreter'ın VENV (Sanal ortamımızın ismi) olması gerekiyor
1- `CTRL + SHIFT + P`'ye tıklayınız
2- Python Select Interpreter'e tıklayınız
3- VENV adındaki sanal ortamı seçiniz



