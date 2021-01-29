# MiniNa: Post-"TestWorld" ready to be used with or without PreGenerated Keys !
* now you can use MiniNa with or without pregenerated keys !
* MiniNa is a deps Mina Protocol installer , made for Noobs by Noobs
What the script do:
[![minina-1.png](https://i.postimg.cc/26zbRF57/minina-1.png)]

Usage:
* First download it ```wget https://raw.githubusercontent.com/AkiAfroo/MiniNa/main/minina.sh```
* Second: chmod +x minina.sh 
* third:  bash minina.sh
* the script will try to install dialog , zip , unzip if are not installed in your system before launch the menu.
* Fresh install after menu pop up: select with mouse or moving with arrows and using spacebar
* options : ```1,2,3,4,5,7,8```
[![minina-1.png](https://i.postimg.cc/26zbRF57/minina-1.png)]

Backup:
* you can backup your wallet >> option 6
[![MININA2-1-BACKUP.png](https://i.postimg.cc/NFCSmw52/MININA2-1-BACKUP.png)](https://postimg.cc/p58sM4QP)


Removing Mina from your system
* ~/.coda-config , keys folder and .mina-env are exclude >> option 9
[![ksnip-20210103-151257.png](https://i.postimg.cc/PJ7VNzRm/ksnip-20210103-151257.png)](https://postimg.cc/1Vprj6Pt)

Removing temp directories and coda-config
* when the daemon stuck sometimes a good option is clean tmp mina folders and ~/.coda-config folder
[![ksnip-20210103-151323.png](https://i.postimg.cc/SK4TXKDt/ksnip-20210103-151323.png)](https://postimg.cc/v4PLkGRW)

Notes
* the script will detect if a wallet is storage in ~/keys folder to avoid overwrite the current ones if you select option 5 my mistake.

* now after is installed run ```coda``` in your terminal or ```coda version``` to check the installation is OK.
* Have fun !
