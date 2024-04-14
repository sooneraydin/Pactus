
<h1 align="center"> Pactus Mainnet</h1>

<div align="center">

![image](https://github.com/0xSocrates/Testnet-Rehberler/assets/108215275/fc854b16-a554-419c-afbf-f99de720060a)

#  | [Twitter](https://twitter.com/pactuschain/) | [Discord](https://discord.gg/zdX6wNUFvg) | [Website](https://pactus.org/) | [Github](https://github.com/pactus-project) |

</div>


### Port kontrol
```
lsof -i -P -n | grep LISTEN
```

<h1 align="center">Kurulum</h1>

```console
sudo apt update -y && sudo apt upgrade -y
sudo apt install screen

curl --proto '=https' --tlsv1.2 -sSL  https://github.com/pactus-project/pactus/releases/download/v1.0.0/pactus_downloader.sh | sh

cd pactus-cli_1.0.0

### 12 kelimenizi alın ve şifrenizi yedekleyin.
./pactus-daemon init -w ~/pactus --testnet
# 7 sayısına enter diyin - çıktıyı yedekleyin

screen -S pactus
./pactus-daemon start -w ~/pactus
```
### sync olmasını bekleyin
explorer: https://explorer.codeblocklabs.com/pactus/validator.php

- Sync olduktan sonra 1. validatör adresine token isteyin.

- reward adreslerinin ilkinde kazançlar zamanla gorulmeye baslanıcak ve artıcak

- Bu aşamada bu adresinize otomatik `delege` edilecek ve `discord=validatör` bağlantısı yapılacak




