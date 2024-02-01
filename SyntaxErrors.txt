#1) Forgetting a semicolon returns:
\FileName.cpp: In function 'type functionName()':FilePath:5:21: error: expected ';' before '}' token

#2) Misspell cout:
In function 'int main()':
C:\Users\student-win10\Documents\Untitled1.cpp:5:2: error: 'out' was not declared in this scope
  out<<"Hello World";
  ^~~
C:\Users\student-win10\Documents\Untitled1.cpp:5:2: note: suggested alternative: 'putw'
  out<<"Hello World";

#3) Delete main():
C:\Users\student-win10\Documents\Untitled1.cpp:4:5: error: expected unqualified-id before '{' token
 int {
     ^

#4) Forget a double quote:
C:\Users\student-win10\Documents\Untitled1.cpp:5:8: warning: missing terminating " character
  cout<<"Hello World;
        ^
C:\Users\student-win10\Documents\Untitled1.cpp:5:8: error: missing terminating " character
  cout<<"Hello World;
        ^~~~~~~~~~~~~
C:\Users\student-win10\Documents\Untitled1.cpp: In function 'int main()':
C:\Users\student-win10\Documents\Untitled1.cpp:6:1: error: expected primary-expression before '}' token
 }
 ^

#5) Delete #include statement:
C:\Users\student-win10\Documents\Untitled1.cpp:1:1: error: expected unqualified-id before '<' token
 <iostream>
 ^
C:\Users\student-win10\Documents\Untitled1.cpp: In function 'int main()':
C:\Users\student-win10\Documents\Untitled1.cpp:5:2: error: 'cout' was not declared in this scope
  cout<<"Hello World";
  ^~~~

#6) Remove std:: :
C:\Users\student-win10\Documents\Untitled1.cpp: In function 'int main()':
C:\Users\student-win10\Documents\Untitled1.cpp:4:2: error: 'cout' was not declared in this scope
  cout<<"Hello World";
  ^~~~
C:\Users\student-win10\Documents\Untitled1.cpp:4:2: note: suggested alternative:
In file included from C:\Users\student-win10\Documents\Untitled1.cpp:1:
C:/Program Files/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/lib/gcc/x86_64-w64-mingw32/8.1.0/include/c++/iostream:61:18: note:   'std::cout'
   extern ostream cout;  /// Linked to standard output
                  ^~~~

#7) Forget a left parenthesis:
C:\Users\student-win10\Documents\Untitled1.cpp:4:9: error: expected initializer before ')' token
 int main)

#8) Forget a brace:
C:\Users\student-win10\Documents\Untitled1.cpp: In function 'int main()':
C:\Users\student-win10\Documents\Untitled1.cpp:5:21: error: expected '}' at end of input
  cout<<"Hello World";
                     ^
C:\Users\student-win10\Documents\Untitled1.cpp:4:12: note: to match this '{'
 int main() {
            ^
