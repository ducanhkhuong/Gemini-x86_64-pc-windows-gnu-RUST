
### Rust Language : [Linux]--->[Windows]
## 1. Cài đặt Rust cho target x86_64-pc-windows-gnu
```
rustup target add x86_64-pc-windows-gnu
```

## 2.Cài đặt toolchain MinGW-w64
Ubuntu Linux
```
sudo apt install mingw-w64

```
## 3.Sửa apikey in src/main.rs
```
Vào trang web : https://ai.google.dev/ để tạo API key Gemini
index row:54 ( key=APIKEYGEMINI )
APIKEYGEMINI : thay bằng key của bạn 
```
## 4.Build Rust project cho môi trường Windows

```
cargo build --release --target x86_64-pc-windows-gnu
```
## 5.Copy file release sang môi trường Windows

```
cp /AIBOX-x86_64-pc-windows-gnu-RUST/target/x86_64-pc-windows-gnu/release/Gemini.exe /mnt/c
```

## 6.About
```
Author : ducanhkhuong
Email  : duca3774@gmail.com
```
## 7.Demo AIBOX
![image](https://github.com/user-attachments/assets/a13d1fe3-2611-4cc8-9aa4-5733b91d0592)


