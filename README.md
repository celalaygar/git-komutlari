## GIT KOMUTLARI

#### KULLANICI BILGILERI
``` 
  git config --global user.name "kullanıcı adı"
  git config --global user.email "e-posta"
  git config --list           # Calisma ve kullanici bilgilerini göster
``` 
#### YEREL DEPO 
``` 
  git add <DOSYA(LAR)>        # Yeni ve degismis dosyalari guncellenecekler listesine ekle
  git add .                   # Yeni ve degismis dosyalarin tumunu guncellenecekler listesine ekle
  git add -u                  # Silinmis ve degistirilmis dosyalari guncellenecekler listesine ekle
  git rm <DOSYA(LAR)>         # Calisma agacında ve dizinde dosyalari kaldir
  git rm -f                   # Calisma agacında ve dizinde dosyalari zorla kaldir
  git commit -m 'not'         # Değisiklikleri depoya kaydet
  git commit -a -m "not"      # Tum değisiklikleri depoya kaydet
  cat .gitignore              # Dosyayi depoya ekleme
  git rm --cached <DOSYA>     # Dosyayi takip etmeyi birak
  git diff                    # Degisiklikler arasindaki farklari goster
  git diff --cached           # Listeye Eklenen Değişiklikler Arasındaki Farkları Göster
  git status                  # Calisma agacindaki durumu goster
  git log                     # Islem gunlugunu goster 
``` 
#### UZAK DEPO 
``` 
  git clone <ADRES>           # Uzaktaki depoyu klonla
  git pull                    # Depodaki son degisiklikleri al
  git push                    # Yereldeki degisiklikleri uzak depoda uygula (origin master)komutuda eklenebilir
``` 
#### DAL (BRANCH) KOMUTLARI 
``` 
  git branch <DAL ADI>        # Dal olustur
  git branch                  # Dallari goster
  git checkout <DAL ADI>      # Calisilan dali degistir    
  git merge <DAL ADI>         # Dallari birlestir
  git branch -d <DAL ADI>     # Dal sil
``` 
#### DIGER KOMUTLAR 
```  
  git --version               # Git versiyon numarasını  göster
  git --help                  # Git yardım sayfasını göster 
  git remote -v               # Uzak depo adresini ver
  git log --since=<LIMIT>     # Iki zaman araligindaki commitleri goster
  git shortlog -s             # Commit yapanlarin isim ve commit sayilarini goster
  git shortlog -e             # Commit yapanlarin isim ve E-postalarini goster
  git shortlog -n             # Commit yapanlari commit sayisina gore sirala 
  git reset -- hard HEAD      # Son yapılan degisiklikleri iptal ederek HEAD geri don
  git checkout -- <DOSYA>     # Sadece bir dosyayi depodaki haline geri getir
  git revert HEAD             # Son yapilan commiti geri al
  git stash save              # Commit yapilmamis degisiklikleri kaydet
  git stash pop               # Commit yapilmamis degisikliklere geri don
  git stash list              # Commit yapilmamis degisiklikleri listele
  git stash drop              # Commit yapilmamis degisiklikleri kaldır
  git grep                    # Mevcut dal icersinde kelime veya ifade arama
  gitk                        # Git gorsellestirme programi
``` 
#### NOTLAR
``` 
  1- <DOSYA(LAR)>  yazili bolumlerde islem yapilan oge veya ogeler yazilacaktir.
  2- Git ontanımlı olarak depo isimlerini origin olarak atar.
``` 
#### KAYNAKCA
``` 
  [1] http://www.kernel.org/pub/software/scm/git/docs/
  [2] http://git-scm.com/book
``` 
