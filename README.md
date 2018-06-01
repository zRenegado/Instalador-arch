## Instalador-arch
Script para instalação do Arch Linux: criptografado, lvm em sdd

[Este projeto é um fork parcial do amigo André Luis](https://github.com/andreluizs/dotfiles/blob/master/.scripts/arch/install.sh)

## Forma de uso

Baixe a iso do [Arch Linux](https://www.archlinux.org), coloque-a em um pendrive e inicie a maquina. Recomendo que leia o script e faça a aleração de usuario, 
senha e verifique as paritções, pois a senha de criptografia não pode ser trocada no sistema, verificar o tamanho das partições o script esta configurado para 
oucupar todo o hd ou sdd. 

Uma vez com a maquina conectada na internet faça:

	pacman -Sy git
	cd /tmp
	git clone https://github.com/zRenegado/Instalador-arch.git
	cd Instalador-arch
	
Agora realize as devidas mudanças no script, usando o seu editor de texto preferido, agora inicie o script e proveite ;).
	
	sh instalador_arch.sh

Adivertência

- Para hd, não se faz necessario o uso do parametro discards e o peridico fstrim.[Dúvidas](https://wiki.archlinux.org/index.php/Solid_State_Drive)
- O projeto esta em alfa, portanto aguarde ate que todo o script esteja funcional, para efitar ficar com um instalação parcial.
- Use por sua conta e risco.
