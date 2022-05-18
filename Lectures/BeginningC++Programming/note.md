# Beginning C++ Programming From Beginner To Beyond

## Section1. Introduction

## Section2. Installation and Setup

## Section3. Curriculum Overview

## Section4. Getting Started
### **Lecture27**
    - main関数は、C++におけるエントリポイントである。
    - coutは、コンソールへの出力で、cinはコンソールへの入力を表すストリームオブジェクトである。

    ```cpp
    #include <iostream>

    int main()
    {
        int favorite_num;

        std::cout << "Enter your favorite number between 1 and 100: ";
        std::cin >> favorite_num;
        std:cout << "Your favorite number is" << favorite_num << std::endl;

        return 0;
    }
    
    ```
### Lecture29
    - コンパイラエラーとは、コンパイル時に発生した構文エラーやセマンティックエラーを指す。

### Lecture30
    - コンパイラ警告とは、コンパイラが検知した潜在的な問題を指す。

### Lecture31
    - リンカエラーは、オブジェクトファイルを結合する時に発生するエラーである。


### Lecture32
    - ランタイムエラーは、プログラム作成時に予見出来ず、実行時に発生するエラーである。

### Lecture33
    - ロジックエラーは、プログラマが生み出したバグで構文上は問題ないが、動作が要件を満たさないエラーを指す。

## Section5. Structure of a C++ Program

### Lecture37
    - 識別子は、プログラマによって名づけられた名前で、キーワードとは異なる。
    ```cpp
    #include <iostream>

    int main()
    {
        int favorite_num;

        std::cout << "Enter your favorite number between 1 and 100: ";
        std::cin >> favorite_num;
        std:cout << "Your favorite number is" << favorite_num << std::endl;

        return 0;
    }
    
    ```

### Lecture38
    - プリプロセッサディレクティブは、#で始まるシンタックスである。
    - プリプロセッサディレクティブは、プリプロセッサによって処理され、そのあとにコンパイラが起動する。
    - プリプロセッサディレクティブの例としては、以下が挙げられる。
        - e.g. #include, #if, #elif, #else, #endif, #ifdef, #ifndef, 

### Lecture39
    - C++におけるコメントは、//または/**/を使用出来る。

### Lecture40
    - main関数は二つのバージョンがある。
        - int main() {return 0;}
        - int main(int argc, char *argv[]){return 0;}

## Sectionx. xxxx
### Lecture999
    - xxx
    ```cpp
    
    ```