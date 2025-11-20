# JinGyu Blog

## 로컬에서 확인하기

### 방법 1: 간단한 HTTP 서버 사용 (권장)

이미 빌드된 `_site` 폴더를 사용하여 로컬에서 확인할 수 있습니다:

```bash
# 실행 스크립트 사용
./serve.sh

# 또는 직접 실행
cd _site
python3 -m http.server 4000
```

그 다음 브라우저에서 `http://localhost:4000`을 열어주세요.

### 방법 2: Jekyll 서버 사용

Jekyll을 설치하고 로컬 서버를 실행하려면:

```bash
# 의존성 설치
bundle install

# 로컬 서버 실행
bundle exec jekyll serve
```

브라우저에서 `http://localhost:4000`을 열어주세요.

**참고**: Jekyll 3.2.1은 오래된 버전이므로 최신 macOS에서는 설치 시 문제가 발생할 수 있습니다. 이 경우 방법 1을 사용하거나, Jekyll을 최신 버전으로 업그레이드하는 것을 권장합니다.