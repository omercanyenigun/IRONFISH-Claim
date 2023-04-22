## Ironfish Mainnet Node Kurulumu


![alt text](https://i.hizliresim.com/3zs1d10.png)

```python
apt-get update && sudo apt upgrade -y
```

```python
sudo curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```

```python
sudo apt-get install -y nodejs
```

```python
npm install -g ironfish 
```

```python
ironfish mainnet
```

```python
ironfish version
```
Mainnet versiyonunuz 1.0.1 olmalı


```python
screen -S ironfish
```

```python
ironfish start
```

ironfish status


Nodunuz senkronizasyon olmalı.

![alt text](https://i.hizliresim.com/fkf1sxu.png)


CTRL-A+C ile yeni screen sayfasında rescan ile blokları tarayın

```python
ironfish wallet:rescan
```

```python
ironfish wallet:import --name <nickname>
```

Koddan sonra spending keyinici yani KYC zamanı ironfish wallet:export <nickname> ile almış olduğunuz key.
  
```python
ironfish wallet:use <nickname>
```
  
Kodu ile cüzdanınızı varsayılan yapın
  
```python  
ironfish wallet:balances
```
  
Token Gönderimi
  
ironfish wallet:send --memo <memoadresiniz>
  
<memoadresiniz> olan yere Kucoin'deki memo adresinizi yazın. Sonra adres isteyecek orayada Kucoin'deki yatırma adresini yazın. Miktarı ve fee'yi belirleyip gönderin. (gönderim 5-10dk sürebilir)
  
![alt text](https://i.hizliresim.com/57t0hyu.png)
  
  
  
  

