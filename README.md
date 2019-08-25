# Utilidades para Desenvolvimento React Native.

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
