このソフトウェアは、 Apache 2.0ライセンスで配布されている製作物が含まれています。
FireStorageにアップロードする
```
from uploader import FireStorage
response = FireStorage.Poster("123.txt").run()
print(response.dl_file_name(), response.dl_url())
```
ファイルなうにアップロードする
```
from uploader import ファイルなう
response = ファイルなう.Poster("123.txt").run()
print(response.dl_file_name(), response.dl_url())
```
