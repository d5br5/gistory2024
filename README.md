## 소개

`.git` 폴더의 내부를 분석할 때 도움을 주는 도구입니다.

## 설치

설치된 python version : 3.12.4

gistory2024를 설치하고자 하는 폴더로 이동하여, 본 레포지토리를 clone합니다.

```bash
git clone https://github.com/d5br5/gistory2024.git
```

## 사용방법

1. 분석할 `.git` 폴더가 있는 디렉토리로 이동합니다.
2. 다음 명령어를 입력합니다.

```bash
# python3 [gistory2024설치경로]/main.py .git
# 절대경로, 상대경로 모두 가능합니다.
python3 ../gistory2024/main.py .git
```

3. 웹 브라우저에서 `localhost:8805` 에 접속합니다.

## 특이사항

원래 소스코드는 생활코딩 이고잉님이 제작해주셨습니다.

원본 레포지토리 링크 : [https://github.com/egoing/gistory](https://github.com/egoing/gistory)

마지막 업데이트일로부터 7년이 흘러, 최신 python 버전과 호환이 되지 않는 현상이 발생하고 있었습니다.

현재 레포는, 최신 파이썬 버전에서도 동작하도록 업데이트된 버전입니다.

[분석 도구 사용 방법 영상 (이고잉님 유튜브)](https://www.youtube.com/watch?v=KyGfapLpWhY)

## TBD

pip install이 가능하도록 수정 예정입니다.
