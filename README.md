このソフトウェアは、 Apache 2.0ライセンスで配布されている製作物が含まれています。<br>
FireStorageにアップロードする
```python
from upander import FireStorage
response = FireStorage.Poster("123.txt").run()
print(response.dl_file_name(), response.dl_url())
```
ファイルなうにアップロードする
```python
from upander import ファイルなう
response = ファイルなう.Poster("123.txt").run()
print(response.dl_file_name(), response.dl_url())
```
