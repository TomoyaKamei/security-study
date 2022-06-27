# SECCON Begginer 2022

## Reversing

### Quiz
- ログ
    - ```
    ┌──(tomoya㉿tom)-[~/…/CTF/SECCON_Begginer_2022/reversing/quiz]
└─$ tar -zxvf quiz.tar.gz 
quiz

┌──(tomoya㉿tom)-[~/…/CTF/SECCON_Begginer_2022/reversing/quiz]
└─$ ./quiz               
Welcome, it's time for the binary quiz!
ようこそ、バイナリクイズの時間です!

Q1. What is the executable file's format used in Linux called?
    Linuxで使われる実行ファイルのフォーマットはなんと呼ばれますか？
    1) ELM  2) ELF  3) ELR
Answer : 2
Correct!

Q2. What is system call number 59 on 64-bit Linux?
    64bit Linuxにおけるシステムコール番号59はなんでしょうか？
    1) execve  2) folk  3) open
Answer : 1
Correct!

Q3. Which command is used to extract the readable strings contained in the file?
    ファイルに含まれる可読文字列を抽出するコマンドはどれでしょうか？
    1) file  2) strings  3) readelf
Answer : 2
Correct!

Q4. What is flag?
    フラグはなんでしょうか？
Answer : 212
flag length must be 46.
    ```
- 調査点
    - 
