# Mert Studio Code v2

🇬🇧 **English:**
Mert Studio Code v2 is an advanced, custom-built IDE and programming language environment named **DORUK**. Developed in C++ using the Qt framework for the graphical user interface, it provides a full-fledged editor experience tailored for the custom DORUK syntax. The engine implements custom lexing, parsing, and execution processes from scratch.

🇹🇷 **Türkçe:**
Mert Studio Code v2, **DORUK** adını verdiğimiz özel programlama dili için sıfırdan geliştirilmiş gelişmiş bir Entegre Geliştirme Ortamıdır (IDE). Grafiksel kullanıcı arayüzü C++ ve Qt framework kullanılarak inşa edilmiştir. Özel DORUK sözdizimi (syntax) için özelleştirilmiş bir editör deneyimi sunarken, arka planda lexer, parser ve çalışma zamanı (runtime) mekanizmalarını tamamen kendi motoruyla işletir.

## Features / Özellikler

- **Custom Lexer & Parser:** Full semantic understanding of the custom DORUK programming language.
- **Modern IDE Interface:** Built with Qt, featuring a minimap, syntax highlighting, and custom dialogs.
- **High Performance:** Core engine is written entirely in C++ for maximum execution speed.
- **CMake Integration:** Easily build and scale the project using standard CMake tools.

## Technologies Used / Kullanılan Teknolojiler

- **C++17 / C++20**
- **Qt6 Framework**
- **CMake**

## Building the Project / Projeyi Derleme

1. Ensure you have CMake and a compatible C++ compiler (MSVC/GCC) installed. / CMake ve uygun bir C++ derleyicisinin kurulu olduğundan emin olun.
2. Generate build files / Derleme dosyalarını oluşturun:
   ```bash
   cmake -B build
   ```
3. Build the project / Projeyi derleyin:
   ```bash
   cmake --build build --config Release
   ```
