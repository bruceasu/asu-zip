# zip
用于解决不同类型系统，不同语言系统中，使用zip压缩时出先的文件名乱码。
1. 接收到乱码zip文件.
   `java -cp zip.jar me.asu.zip.Unzip -i <zip文件> -o <解压目录> -e <发送方系统编码>`
2. 为了避免对方收到乱码，可以这样压缩
   `java -cp zip.jar me.asu.zip.Unzip -i <待压缩目录> -o <zip文件> -e <接收方系统编码ding>`