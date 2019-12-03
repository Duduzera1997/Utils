# Utilidades para Desenvolvimento Mobile

**Executar Emulador sem necessidade de abrir o Android Studio:**

***Windows:*** 

```shell
"C:\Users\$USERNAME$\AppData\Local\Android\Sdk\tools\emulator.exe" -no-snapshot -avd $DEVICE_NAME$
```

|$USERNAME$|$DEVICE_NAME$|
|----------|-------------|
|Nome do usuário do Windows|Nome do Dispositivo, Ex: Nexus_5X_API_29|


***Linux:***

```shell
/home/$USERNAME$/Android/Sdk/tools/emulator -no-snapshot -avd $DEVICE_NAME$
```

|$USERNAME$|$DEVICE_NAME$|
|----------|-------------|
|Nome do usuário do Linux|Nome do Dispositivo, Ex: Nexus_5_API_25|

***MacOS:***

```shell
/Library/Android/sdk/emulator/emulator -no-snapshot -avd $DEVICE_NAME$
```

$DEVICE_NAME$|
-------------|
|Nome do Dispositivo, Ex: Nexus_5_API_25|


### Comandos

****Executar evento de Balançar o aparelho quando conectado via USB (" Open Developer Menu"):****

```shell
adb shell input keyevent 82 
```

****Verificar Logs da camada nativa no RN e no JS:****

```shell
adb logcat *:E ReactNative:E ReactNativeJS:E
```
