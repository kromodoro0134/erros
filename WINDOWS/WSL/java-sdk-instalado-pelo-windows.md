### Caso o JavaSDK tenho sido instalado pelo WINDOWS e precise instaciar pelo WLS

[jdk-18_windows-x64_bin.msi](https://download.oracle.com/java/18/latest/jdk-18_windows-x64_bin.msi)

#### Criar variável JAVA_HOME

```
export JAVA_HOME=/usr/lib/jvm/java-[VERSAO]-openjdk-amd64

# Add JAVA bin directory to the PATH variable
export PATH=$PATH:$JAVA_HOME/bin
```
