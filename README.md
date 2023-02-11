<h1 align="center"> Newrl </h1>

![image](https://user-images.githubusercontent.com/101149671/194660242-7679c111-df7a-49fd-b9eb-1d83cd5e010f.png)

# Newrl chain mainnet kurulum:

## Sunucumuzu güncelliyoruz:
```
sudo apt-get update && sudo apt-get upgrade
```

## Git yüklüyoruz
```
apt install git
```
## Git clone
```
 git clone https://github.com/git/git
```
## Deadsnakes repo yüklüyoruz

```
sudo apt install software-properties-common -y
```
```
sudo add-apt-repository ppa:deadsnakes/ppa
```
## Python3.9 ve pip  yüklüyoruz
```
sudo apt install python3.9
sudo apt install python3.9-venv
sudo apt install python3-venv python3-pip
```
## Kurulum
```
git clone https://github.com/newrlfoundation/newrl.git
cd newrl
scripts/install.sh mainnet
```

## Düğümü başlatıyoruz
```
apt install screen
```

```
screen -S newrl
```

```
scripts/start.sh mainnet
```
