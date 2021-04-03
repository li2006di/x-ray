# 备份xray

## Advance
**install & Upgrade Xray-core and geodata with <code>User=root</code>, which will overwrite <code>User</code> in existing service files**
```
# bash -c "$(curl -L https://raw.githubusercontent.com/man2018/x-ray/main/xray-install.sh)" @ install -u root
```
 
 **Install & Upgrade Xray-core without geodata**
 ```
 # bash -c "$(curl -L https://raw.githubusercontent.com/man2018/x-ray/main/xray-install.sh)" @ install --without-geodata
 ```
 
 ***Remove Xray, include json and logs***
 ```
 # bash -c "$(curl -L https://raw.githubusercontent.com/man2018/x-ray/main/xray-install.sh)" @ remove --purge
 ```


