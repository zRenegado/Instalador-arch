<H1 align=center>Instalador-arch</H1>

---
Script para instalação do Arch Linux: criptografado, lvm em SSD.
Faça backup de todos seus dados e arquivos antes de fazer o uso/teste de qualquer arquivo deste repositório.

---


[Este projeto é um fork parcial do amigo André Luis](https://github.com/andreluizs/dotfiles/blob/master/.scripts/arch/install.sh)
---
## Forma de uso

Baixe a iso do [Arch Linux](https://www.archlinux.org), coloque-a em um pendrive e inicie a maquina.

Uma vez com a maquina conectada na internet faça:

	pacman -Sy git
	cd /tmp
	git clone https://github.com/zRenegado/Instalador-arch.git
	cd Instalador-arch

Agora realize as devidas mudanças no script: Apartir da linha 31 altere os dados de usuario, usando o seu editor de texto preferido, agora inicie o script e aproveite ;). para a senha de criptografia leia o proximo topico

	sh instalador_arch.sh
---
## Senha de criptografia
- Tamanho da senha 1-63 caracteries (podendo ser: letras, numeros e carcteries especiais)
- Não existe, senhas inquebraveis mais você pode tentar ao maximo inibir que obtenham a sua senha, dicas :
	- [Como escolher senhas seguras - Mozilla](https://support.mozilla.org/pt-BR/kb/como-escolher-senhas-seguras)
	- [Dicas de Senhas - Sefanet](http://www.sefanet.pr.gov.br/sefanetv2/segSefanet/DicasSenhas.asp)
	- [Senhas mais seguras e facies de lembrar - Dicas do Greb](http://www.dicasdogreb.com.br/crie-senhas-mais-seguras-e-faceis-de-lembrar)
- Ficou com dúvida do poder da sua senha? [Teste aqui, uma parecida por segurança](https://howsecureismypassword.net)
---
## Adivertência

- Para hd, não se faz necessario o uso do parametro discards e o peridico fstrim.
- O projeto esta em alfa, portanto aguarde ate que todo o script esteja funcional, para efitar ficar com um instalação parcial.
- Use por sua conta e risco.
---
## Referência

- [Solid State Drive - Wiki Arch Linux](https://wiki.archlinux.org/index.php/Solid_State_Drive)
- [Disk encryption -Wiki Arch Linux](https://wiki.archlinux.org/index.php/Disk_encryption)
- [How to properly activate TRIM for your SSD on Linux: fstrim, lvm and dm-crypt](http://blog.neutrino.es/2013/howto-properly-activate-trim-for-your-ssd-on-linux-fstrim-lvm-and-dmcrypt)
- [Arch Linux - SSD Trim on encrypted LVM volumes](http://ggarcia.me/2016/10/11/arch-linux-ssd-trim.html)
- [Installing (encrypted) Arch Linux on an Apple MacBook Pro](https://0xadada.pub/2016/03/05/install-encrypted-arch-linux-on-apple-macbook-pro)
- [ArchLinux Installation Guide on Encrypted SSD](https://danynativel.com/2017/01/29/archlinux-installation-guide-on-encrypted-ssd-2017/)
---
<p align=center>zRenegado />MIT © 2018<p>
