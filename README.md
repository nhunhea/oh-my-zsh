# oh-my-zsh
## 1. Shell dan ZSH
**Shell** adalah program bawaan dari sistem operasi yang menyediakan komunikasi antara pengguna dan sistem operasi \(kernel komputer\).
**Zsh* adalah salah satu shell UNIX yang populer, memiliki fitur interaktif dan scripting shell. Merupakan versi dari Bourne Shell yang diupgrade dengan fitur-fitur seperti fitur bash, ksh, dan tcsh.

## 2. Cara Instalasi Zsh
Di MAC Zsh sudah ter-install secara otomatis
```
Default
```
## 3. OhMyZsh
adalah suatu framework komunitas open source yang berguna untuk konfigurasi ZSH. Ohmyzsh menyediakan fitur-fitur seperti tema, plugins, dan banyak hal lagi yang akan membuatmu terkejut "Oh My ZSH!"
## 4. Cara Instalasi OhMyZsh
Cara Instalasi OhMyZsh yaitu ketik kode berikut di terminal
```
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
## 5. Cara Mengganti Tema Zsh
buka website
```
https://ohmyz.sh
```
klik **Theme** --> kemudian pilih tema yang diinginkan, ingat nama tema tersebut.

Kemudian buka terminal, masuk ke direktory home, kemudian
```
nano ~/.zshrc
```
Lalu pada baris
```
ZSH_THEME="nama tema"
```
Ganti nama tema sesua yang disukai kemudian simpan.
Misal 
```
ZSH_THEME="bira"
```
Lalu load zsh dengan cara
```
source .zshrc
```
## 6. Fitur Zsh
### Auto-correct
pada zsh terdapat auto-correct
![auto-correct](https://qph.ec.quoracdn.net/main-qimg-d45a5c5abf52584a62a147e4df0bbd82.webp "Logo Title Text 1")

### Auto-complete
pada zsh terdapat auto-complete dengan cara tekan tombol **tab**

### Expand Variable
ketik
``` 
$ Path
```
kemudian tekan **tab**
maka akan menghasilkan 
```
/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
```
 ### Extended gobbling
 ```
 evania@Evanias-MacBook-Air ~
╰─$ ls *(                                                                   1 ↵
%  -- device files
)  -- end of qualifiers
*  -- executable plain files
+  -- + command name
-  -- follow symlinks toggle
.  -- plain files
/  -- directories
:  -- modifier
=  -- sockets
@  -- symbolic links
A  -- group-readable
D  -- glob dots
E  -- group-executable
F  -- non-empty directories
 ```

 ### Autopush Command
 autopushd command pada zsh membuat 
 ```
 cd
 ```
 bisa langsung kembali ke direktori sebelumnya

 ### Tema
 zsh menyediakan berbagai tema yang bisa diubah oleh pengguna

 ### Alias 
 menyediakan perintah yang lebih singkat. Contoh :
 ```
ls -liah Menjadi ls -ll
 ```
