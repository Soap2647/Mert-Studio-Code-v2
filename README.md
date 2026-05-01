# Mert Studio Code v2

Mert Studio Code v2 is an advanced, custom-built IDE and programming language environment named **DORUK**. Developed in C++ using the Qt framework for the graphical user interface, it provides a full-fledged editor experience tailored for the custom DORUK syntax. The engine implements custom lexing, parsing, and execution processes from scratch.

## Features
- **Custom Lexer & Parser:** Full semantic understanding of the custom DORUK programming language.
- **Modern IDE Interface:** Built with Qt, featuring a minimap, syntax highlighting, and custom dialogs.
- **High Performance:** Core engine is written entirely in C++ for maximum execution speed.
- **CMake Integration:** Easily build and scale the project using standard CMake tools.

## Technologies Used
- **C++17 / C++20**
- **Qt6 Framework**
- **CMake**

## Building the Project
1. Ensure you have CMake and a compatible C++ compiler (MSVC/GCC) installed.
2. Generate build files:
   ```bash
   cmake -B build
   ```
3. Build the project:
   ```bash
   cmake --build build --config Release
   ```

---

# Mert Studio Code v2

Mert Studio Code v2, **DORUK** adını verdiğimiz özel programlama dili için sıfırdan geliştirilmiş gelişmiş bir Entegre Geliştirme Ortamıdır (IDE). Grafiksel kullanıcı arayüzü C++ ve Qt framework kullanılarak inşa edilmiştir. Özel DORUK sözdizimi (syntax) için özelleştirilmiş bir editör deneyimi sunarken, arka planda lexer, parser ve çalışma zamanı (runtime) mekanizmalarını tamamen kendi motoruyla işletir.

## Özellikler
- **Özel Lexer & Parser:** Özel DORUK programlama dilini anlamsal olarak tamamen çözümleme.
- **Modern IDE Arayüzü:** Qt ile oluşturulmuş minimap, sözdizimi renklendirmesi (syntax highlighting) ve özel iletişim kutuları içeren modern arayüz.
- **Yüksek Performans:** Çekirdek motor, maksimum çalışma hızı için tamamen C++ ile yazılmıştır.
- **CMake Entegrasyonu:** Standart CMake araçlarını kullanarak projeyi kolayca derleme ve ölçeklendirme.

## Kullanılan Teknolojiler
- **C++17 / C++20**
- **Qt6 Framework**
- **CMake**

## Projeyi Derleme
1. CMake ve uyumlu bir C++ derleyicisinin (MSVC/GCC) kurulu olduğundan emin olun.
2. Derleme dosyalarını oluşturun:
   ```bash
   cmake -B build
   ```
3. Projeyi derleyin:
   ```bash
   cmake --build build --config Release
   ```
