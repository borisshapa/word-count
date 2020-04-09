Word Count
----
Программа ваполняет подсчёт слов в файле, путь к которому передан первым аргументом при запускке бинарного файла.

* Программа на писана под 
  * архитектуру процессора [`x86-64`](https://www.felixcloutier.com/x86/);
  * операционную систему [`Linux`](https://www.kernel.org/doc/);
  * на ассемблере [`NASM`](https://www.nasm.us/doc/) (Установить: `sudo apt-get install nasm`).

* Компиляция программы:
  ```
  cmake .
  make
  ```

* Запуск программы:
  ```
  ./word-count <путь к фалу>
  ```
* Пример:
  ```
  In:
    ./word-count README.md
  Out:
    97
  ```
