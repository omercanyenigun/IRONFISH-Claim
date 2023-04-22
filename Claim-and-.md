ıronfish Mainnet Node Kurulumu


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

```python
screen -S ironfish
```

```python
ironfish start
```

CTRL-A+C

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
  
  
  

