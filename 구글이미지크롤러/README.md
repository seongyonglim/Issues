# Joeclinton1 의 구글 이미지 크롤러

clone 이후 아래 명령어를 치면 setup이 끝난다

```
$ cd google-images-download && python setup.py install
```

---

## 직접 원본 git으로부터 clone을 할 경우

```
git clone https://github.com/Joeclinton1/google-images-download.git
```

google_images_download\google_images_download.py 파일에서 수정해야될 사항이 있다.

```
if info is None:
    info = data[23]

# 아래와 같이 수정

if info is None:
    info = data[11]
```
