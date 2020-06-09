# CNC-Draw


Codigo legal para controle da CNC, adicionado neste Git
https://www.instructables.com/id/Drawing-Plotter/

Ideia
https://simple-circuit.com/arduino-bipolar-stepper-motor-control/
https://create.arduino.cc/projecthub/electropeak/sd-card-module-with-arduino-how-to-read-write-data-37f390

Pinout
Arduino    Stepper shield (LM293)
  D2              Xaxis_A1
  D5              Xaxis_A2
  D6              Xaxis_A3
  D7              Xaxis_A4
  
  D16(A2)         Yaxis_A1
  D17(A3)         Yaxis_A2
  D18(A4)         Yaxis_A3
  D19(A5)         Yaxis_A4
  
Arduino    ServoMotor
  D10             PWM
  
  Arduino    Display Nokia5125
  D3              RST
  GND             CE
  D15(A1)         DC
  D9              DIN
  D8              CLK
  
  Arduino    SD Card
  D12             MISO
  D13             SCK
  D11             MOSI
  D4              CS
  
  
