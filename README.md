# kubernetes-install-script
홈랩 쿠버네티스의 간편한 설치를 위한 스크립트
- 24/05/20 | Ubuntu 22.04 | arm64 환경에서 작동이 확인되었습니다.
- 일부 잘못된 부분이 있을 수 있습니다.
- init 등의 과정은 포함 되어 있지 않고, master/slave 공통 설치 파트만을 포함합니다.

install.sh 파일을 다운로드 후, 다음과 같은 과정을 거쳐야 합니다.

```
chmod +x install.sh
```

```
./install.sh
```

재부팅 후, 이용 하시면 됩니다.
