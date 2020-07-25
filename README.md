### NPDVs
Script para automatização de tarefas. 
Possue algumas configurações em suas variáveis para uso em desktop em diferentes resoluções de telas.  
RES = Resolução de vídeo  
PDVS_IPS = Finais dos IPs que deseja que o comando seja execultado simultaneamente.  
OS PRINCIPAIS FICAM NAS PRIMEIRAS LINHAS.  
  

By: Nilsonlinux


Comando para instalação (Termux)
```bash
pkg update && pkg install sshpass wget git && apt install openssh && wget https://raw.githubusercontent.com/nilsonlinux/npdvs/master/npdvs.sh && chmod +x npdvs.sh && clear && ./npdvs.sh
```
Comando para instalação no desktop (Debian based)
```bash
sudo apt install rdesktop sshpass wget git && wget https://raw.githubusercontent.com/nilsonlinux/npdvs/master/npdvs.sh && chmod +x npdvs.sh && clear && ./npdvs.sh
```

## Após a instalação, utilize o comando 
```bash
./npdvs.sh
```
