1. Przejdź do katalogu projektu za pomocą polecenia
cd cmake_template

2. Edytuj plik CMakeLists.txt edytorem nano (lub innym, np. vim)
nano CMakeLists.txt

3. W linii zawierającej polecenie set( PROJECT_NAME CMake_Template ) zamiast CMake_Template wpisz swoją nazwę projektu (np. projekt_1). Następnie wyjdź z edytora nano za pomocą kolejno Ctrl-O a następnie Ctrl-X.

4. Teraz za pomocą cmake wygenerujemy pliki potrzebne do zbudowania projektu
cmake ./

5. Na koniec, budujemy projekt za pomocą polecenia
make

6. Uruchom skompilowany program za pomocą polecenia
./projekt_1
