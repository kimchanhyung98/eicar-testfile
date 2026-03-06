## eicar-test-files

### [EICAR 테스트 파일이란?](https://ko.wikipedia.org/wiki/EICAR_테스트_파일)

- 유럽 컴퓨터 안티바이러스 연구소(EICAR)와 컴퓨터 안티바이러스 연구 기구(CARO)에서 안티바이러스 소프트웨어 및 보안 솔루션을 테스트하기 위해 개발한 테스트 파일입니다.
- 68~128 바이트의 ASCII 텍스트로, 다양한 운영체제에서 실행 가능하며 'EICAR-STANDARD-ANTIVIRUS-TEST-FILE!' 메시지를 출력한 후 종료됩니다.

```plaintext
X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*
```

### 디렉토리 구조

테스트 파일들은 유형별로 다음과 같이 분류되어 있습니다:

- **`standard/`** - 표준 EICAR 테스트 파일 (.com, .txt)
- **`pdf/`** - Adobe Acrobat PDF 테스트 파일 (.pdf)
- **`excel/`** - Microsoft Excel 테스트 파일 (.xls, .xlsx, .xlsm, .ods, .ots)
- **`word/`** - Microsoft Word 테스트 파일 (.doc, .docm, .odt, .ott)
- **`powerpoint/`** - Microsoft PowerPoint 테스트 파일 (.ppt, .pptm, .pptx, .odp, .otp)
- **`archives/`** - ZIP 압축 파일 (.zip)

### 참고

- [eicar.org](https://www.eicar.org/download-anti-malware-testfile)
- [mattias-ohlsson/eicar-standard-antivirus-test-files](https://github.com/mattias-ohlsson/eicar-standard-antivirus-test-files)
- [csawtelle/eicar-msoffice-macro-antivirus-test-files](https://github.com/csawtelle/eicar-msoffice-macro-antivirus-test-files)
