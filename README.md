# bot-telegram-arduino-php
Mengendalikan Lampu Led dengan arduino dan php 


Untuk mengkonfigurasi port computer silahkan buka dulu portnya

$port= new-Object System.IO.Ports.SerialPort COM3

kemudian 

$port.open()
$port.WriteLine("some string")
$port.ReadLine()
$port.Close()
