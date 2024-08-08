# 一些工具

- `zipalign`、`apksigner` 来自 [Android SDK Build Tools](https://developer.android.com/tools/releases/build-tools)（[下载链接](https://dl.google.com/android/repository/build-tools_r34-windows.zip)）

- 如何生成同款 `freekey.keystore`：
  ```
  keytool -genkeypair -noprompt -alias freekey -dname "CN=Unknown, OU=Unknown, O=Unknown, L=Unknown, ST=Unknown, C=Unknown" -keyalg RSA -keysize 2048 -validity 999999 -keystore freekey.keystore -storepass "123456" -keypass "123456"
  ```

**请不要将这个公开密钥用作其他用途，这样做很不安全。如果需要一个密钥，请自己生成一个。**
