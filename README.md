# safesign OAB

Arquivo binário .deb para instalação da certificação digital (token GD Buriti) no repositório Debian Buster (11) com as dependências corrigidas, de modo que não há a necessidade de instação de nenhuma nenhuma que já não esteja no Debian Bullseye.
Instalação de dependencias.
No terminal, insira o comando:

$sudo apt-get install libccid -y && sudo apt-get install pcscd -y


Na página em que o arquivo foi extraído, digite no terminal:

$ sudo dpkg -i safesign.deb
