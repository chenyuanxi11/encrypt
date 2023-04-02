### Vochant Encrypt
----
This project is an easily way to encrypt your files ( you can also decrypt them. :D). It is based on C++. Some syntaxes and functions are only support Windows, but you can modify them to make them support other systems like Linux.

Like you can use command base64 %i>%o, base64 -d %i>%o and rm %f to replace certutil -f -encode %i %o, certutil -f -decode %i %o and del /f /s /q %f.Then you have to rewrite codes of Base64 reading.

If you generated VochantEncryptedFormat file on Windows, and you want to decrypt it on Linux, don't forget convert it from CRLF to LF!

If you are using a newer version, somethings are changed. Don't be afraid, newer version can decrypt older version and convert it to newer format ( Decrypt and encrypt later :D ). (But now it only have one version: pr 0.1)

Use these command to prepare, compile, assembly and link it:
 - g++ -static cli.main.cpp -o vencrypt (GNU GCC required)
 - clang++ -static cli.main.cpp -o vencrypt (Clang required)
 - cl main.cpp (MSVC required)

Now I don't have much time to write a Chinese Edition, I will write it later.I am a Chinese student, but this project is for the world, so I wrote an English version first.

*简体中文(未完成)* | English **(Currently)**
