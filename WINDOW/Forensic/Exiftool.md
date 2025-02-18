# [ExifTool]

## 설명
ExifTool은 메타데이터를 읽고, 작성하고, 수정할 수 있는 도구입니다. 이미지, 비디오, 오디오, 문서 파일 등의 메타데이터를 분석하는 데 사용됩니다.

## 설치 영역
`/usr/local/bin/exiftool`

## 사용처
- 디지털 포렌식에서 이미지 및 문서 파일의 메타데이터 분석
- 사진 및 미디어 파일의 메타데이터 편집 및 삭제
- 자동화된 파일 태깅 및 정리 스크립트 구현

## 설치(접속) 방법
### MacOS (homebrew로 설치하는 경우)
- 터미널에 다음 명령어를 입력하여 설치합니다. 
```bash
brew install exiftool
```
### Linux (패키지 매니저를 사용하는 경우)
- 터미널에 다음 명령어를 입력하여 설치합니다. 
```bash
sudo apt install libimage-exiftool-perl  # Ubuntu/Debian
sudo dnf install perl-Image-ExifTool     # Fedora
```
### Windows (Standalone 버전 다운로드)
- ExifTool 공식 다운로드에서 다운로드 후 실행

**ExifTool 실행:**
   - cmd, iterm2, cli 등에서 `exiftool file`을  실행합니다.

## 접속 화면
![ExifTool 실행](https://github.com/user-attachments/assets/82493f3f-b8f7-46b2-b5c6-225a434cb6a2)



## 주의 사항
- 일부 파일 형식에서는 메타데이터 수정이 제한될 수 있음
- 원본 파일을 보호하기 위해 백업 옵션(-overwrite_original)을 주의해서 사용할 것

## 관련 URL
[관련 문서 링크](https://exiftool.org/)
