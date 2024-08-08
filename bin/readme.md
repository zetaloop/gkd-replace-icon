# How to get the `freekey.keystore`

`keytool -genkeypair -noprompt -alias freekey -dname "CN=Unknown, OU=Unknown, O=Unknown, L=Unknown, ST=Unknown, C=Unknown" -keyalg RSA -keysize 2048 -validity 999999 -keystore freekey.keystore -storepass "123456" -keypass "123456"`
