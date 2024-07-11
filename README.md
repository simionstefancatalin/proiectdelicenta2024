  Proiect de licenta Simion Stefan-Catalin 6403.pdf --- acest fișier reprezintă partea teoretică a lucrării mele de licență și include informații despre funcționalitatea sistemului și diagrama circuitului acestuia;
  Software Arduino Uno.rar --- codul sursă pentru funcționarea microcontroler-ului Arduino Uno în sistemul dezvoltat; Arduino Uno este responsabil în cadrul sistemului cu preluarea de mesaje prin UART de la Raspberry Pi Pico W, mesaje ce conțin informații despre diferiți parametri din sistem și care, prin intermediul Arduino Uno, sunt transmise pe un ecran LCD 16x2 prin protocolul I2C.
  Software Raspberry Pi Pico W.rar --- codul sursă pentru funcționarea microcontroler-ului Raspberry Pi Pico W în sistemul prezentat; Raspberry Pi Pico W este responsabil de achiziția de date de la senzorul de umiditate a solului și senzorul de nivel al apei, date ce se constituie în informații despre diferiți parametri ai umidității solului și a nivelului de apă din bazinul în care stă pompa de apă; pe baza acestor informații, tot prin Raspberry Pi Pico W, sistemul ia decizii fundamentale cu privire la punerea în funcțiune sau scoaterea din funcțiune a modulului releu cu 1 canal ce comandă pompa de apă;

  Componente hardware utilizate:
 > Breadboard;
 > Raspberry Pi Pico W;
 > Arduino Uno (rev. 3);
 > Modul releu cu 1 canal 3.3V;
 > Pompă de apă submersibilă;
 > Senzor de umiditate a solului;
 > Senzor de nivel al apei;
 > Ecran LCD 16x2 I2C;
 > Fire Dupont;
 > Modul buzzer;
 > Modul alimentare externa 3.3-5V;

  Se recomandă utilizarea Thonny IDE pe partea de MicroPython & Rapsberry Pi Pico W și Arduino IDE pe partea de C/C++ & Arduino IDE.
