Firmware modificado para pular o wizard da algar telecom por Ricardo Gauer, Risco de Brick não nos responsabilizamos

arquivos Td-vg5611 Debrand.7z

Acessar configurações, endereço 192.168.0.1/main.html

Passar o arquivo de configução para habilitar o telnet config.bin

Putty telnet 192.168.1.1:1023

Abrir o tftpd64.exe

comandos no terminal putty

tftp -g -l /var/tmp/mtd0 -r mtd0 192.168.1.2

tftp -g -l /var/tmp/mtd1 -r mtd1 192.168.1.2

tftp -g -l /var/tmp/mtd2 -r mtd2 192.168.1.2

tftp -g -l /var/tmp/mtd3 -r mtd3 192.168.1.2

tftp -g -l /var/tmp/mtd4 -r mtd4 192.168.1.2

tftp -g -l /var/tmp/mtd5 -r mtd5 192.168.1.2

cat /var/tmp/mtd0 > /dev/mtdblock0

cat /var/tmp/mtd1 > /dev/mtdblock1

cat /var/tmp/mtd2 > /dev/mtdblock2

cat /var/tmp/mtd3 > /dev/mtdblock3

cat /var/tmp/mtd4 > /dev/mtdblock4

cat /var/tmp/mtd5 > /dev/mtdblock5

caso de brick regravar eepron usando gravador CH341A e backup já modificado "Full dump 19 (no Wizzard).Bin.BIN"
