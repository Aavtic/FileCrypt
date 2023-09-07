# FileCrypt  <a href="https://instagram.com/aadish_mg"><img alt="Gitter" src="https://camo.githubusercontent.com/0b67f2eb691b83144519058d27f3ae6104f24a760db25d4a0566c7c40f53731f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f727573742d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d72757374266c6f676f436f6c6f723d7768697465"></a>




## A program completely written in Rust to encrypt and decrypt files using a provided key.

<p align="center">
    <b align="center">Encrypt & Decrypt files with blazingly fast Rust</b>
  <p align="center">
  </p>
</p>


### socials

<a href="https://instagram.com/aadish_mg"><img alt="Gitter" src="https://camo.githubusercontent.com/7a705494c370a8412797521701153d2873fb39109edf80afc408efd0927ae2d0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f496e7374616772616d2d2532334534343035462e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d496e7374616772616d266c6f676f436f6c6f723d7768697465"></a>



https://github.com/Aavtic/FileCrypt/assets/89965681/ec881c68-a247-4c2f-992f-f67f6298b967



### Installation & Setup

Install [Rust](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwig24CWxJiBAxWNUGwGHWsPBiYQFnoECBMQAQ&url=https%3A%2F%2Fwww.rust-lang.org%2Ftools%2Finstall&usg=AOvVaw3Icgu945TtBSmUIPVgdOzY&opi=89978449) & Cargo package manager 

1. Clone the repo
```bash
git clone https://github.com/Aavtic/FileCrypt.git
```
2. Build the executable using cargo build in the cloned directory

```bash
cargo build
```
Done!
The executable will be in ```./FileCrypt/target/debug/filecrypt```

### Usage 

Run the executable in the directory you have the files to encrypt, so that you don't have to specify full filepath.

## Encrypt files

1. On Linux
```bash
./filecrypt -e <file-to-encrypt> -k <key> -o <output-file>
```
2. On Windows
```bash
.\filecrypt -e <file-to-encrypt> -k <key> -o <output-file>
```

## Decrypt files

1. On Linux
```bash
./filecrypt -d <file-to-decrypt> -k <key> -o <output-file>
```
2. On Windows
```bash
.\filecrypt -d <file-to-decrypt> -k <key> -o <output-file>
```

### Optional Argument ```--no-backup```

When you normally encrypt files using filecrypt, it stores a backup of the password in ```./.filecrypt/.filecrypt.json``` file. It will store them in the directory that you run this software. So Its recommended to create a directory to encrypt files from it so all the passwords will be stored in ```./.filecrypt/.filecrypt.json``` file in that directory.

If you wish to not save the password then you can use the ```--no-backup``` argument while encrypting the file. 
```bash 
./filecrypt -e <file-to-encrypt> -k <key> -o <output-file> --no-backup
```
## Downloads

### Linux 
### Download an ```ELF 64-bit LSB pie executable, x86-64```
[Download](https://github.com/Aavtic/FileCrypt/releases/download/download/filecrypt.elf)
### Windows
### Download a .exe file
[Download](https://github.com/Aavtic/FileCrypt/releases/download/download/filecrypt.exe)




