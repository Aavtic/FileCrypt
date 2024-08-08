# FileCrypt



## A program completely written in Rust to encrypt and decrypt files using a provided key.

<p align="center">
    <b align="center">Encrypt & Decrypt files with blazingly fast Rust</b>
  <p align="center">
  </p>
</p>


### socials


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

## Linux 
### Download an ```ELF 64-bit LSB pie executable, x86-64```
[Download](https://github.com/Aavtic/FileCrypt/releases/download/download/filecrypt.elf)
## Windows
[Download](https://github.com/Aavtic/FileCrypt/releases/download/download/filecrypt.exe)




