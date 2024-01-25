#include <iostream>
#include <cstdlib>
#include <unistd.h>

void typeText(const std::strings test) {
for (char c : text ) {
  std::cout << c << std:: flush ;
  usleep(100000);
}
}
void clearScreen(){
#ifdef _WIN32
system ("cls");
#else

system ("clear);
#endif
}
int main() {

std::string name;
std::string umurStr;

std::cout "Masukkan nama Anda:";
std::getline (std:: cin, nama);

std:cout "Masukkan umur Anda:";
std::getline (std:: cin, umurStr);

int umur = std:: stoi(umurStr);
clearScreen();

Happy Birthday 

L
