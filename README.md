# safesign OAB

Arquivo binário .deb para instalação da certificação digital (token GD Buriti) no repositório Debian Bullseye (11) com as dependências corrigidas, de modo que não há a necessidade de instação de nenhuma que já não esteja no Debian Bullseye.
Funciona também da mesma forma em distros baseadas em Debian como Ubuntu e Mint, embora recomendemos fortemente o uso do Debian.
Instalação de dependencias.
No terminal, insira o comando:

$sudo apt-get install libccid -y && sudo apt-get install pcscd -y


Na página em que o arquivo foi extraído, digite no terminal:

$ sudo dpkg -i safesign.deb

Por fim, agradecemos imensamente aos amigos da LibreCode Coop e à Comunidade Debian, sem a ajuda de vocês, os advogados do Brasil continuariam presos para sempre.
