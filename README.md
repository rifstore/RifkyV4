## INSTALL SCRIPT
```
apt update -y && apt upgrade -y && apt install -y &&  wget -q https://raw.githubusercontent.com/rifstore/RifkyV4/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/rifstore/RifkyV4/main/update.sh && bash update.sh
```

## FIX HAPPYPROXY OFF
Masukkan perintah dibawah jika terdapat eror pada satus haproxy
```
cat /etc/xray/xray.key /etc/xray/xray.crt > /etc/haproxy/hap.pem && systemctl restart haproxy
```
