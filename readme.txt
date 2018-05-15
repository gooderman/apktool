##align
zipalign.exe -v -p 4 input.apk output.apk

##sign
java -jar apksigner.jar sign --ks xxx.jks --ks-pass pass:xxx --ks-key-alias hsgame --key-pass pass:xxx --in input.apk --out out1.apk

##
apktool d input.apk

apktool b -o .\bbb.apk input



