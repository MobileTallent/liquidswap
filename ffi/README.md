flutter pub get
flutter pub run ffigen:setup -I/usr/lib/llvm-10/include -L/usr/lib/llvm-10/lib

sudo port install clang-10
flutter pub run ffigen:setup -I/opt/local/libexec/llvm-10/include -L/opt/local/libexec/llvm-10/lib
