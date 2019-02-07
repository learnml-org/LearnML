# LearnML
머신러닝 학습자를 위한 시각화 프로그램

## 특징
- 여러 플랫폼에서 사용할 수 있습니다.
- 확장을 통해 프로그램의 기능을 무한 확장할 수 있습니다.

## 문서
[이곳](https://github.com/learnml-org/LearnML/wiki)에서 확인할 수 있습니다.

## 다운로드
[이곳](https://github.com/learnml-org/LearnML_CIS/releases)에서 다운로드 할 수 있습니다.

## 빌드
### 준비물
- C++17 이상을 지원하는 컴파일러
- Git
- CMake
- Makefile 또는 Visual Studio

### 1. 소스 코드 다운로드
```
$ git clone -b stable https://github.com/learnml-org/LearnML.git
```
위 명령어를 이용해 안정화 된 가장 최신 버전의 소스 코드를 다운로드 할 수 있습니다.

만약 안정화 여부에 관계 없이 가장 최신 버전의 소스 코드를 다운로드 받고 싶다면 `-b stable`을 `-b pre-release`로 변경하시고, 개발중인 소스 코드를 다운로드 받고 싶다면 삭제하면 됩니다.

### 2. 외부 모듈 다운로드
```
$ cd LearnML
$ git submodule update --init --recursive
```

### 3. 컴파일 준비
```
$ cmake CMakeLists.txt
```

### 4. 컴파일
```
$ make
```
만약 cmake 명령어를 실행한 후 Makefile이 아닌 Visual Studio 솔루션 파일이 만들어졌다면 Visual Studio를 통해 컴파일 해야 합니다.

## 외부 모듈
- [LearnML CIS](https://github.com/learnml-org/LearnML_CIS) (GPLv2 라이선스)
- [LearnML Core](https://github.com/learnml-org/LearnML_Core) (GPLv2 라이선스)
- [LearnML EDK](https://github.com/learnml-org/LearnML_EDK) (MIT 라이선스)
- [LearnML LE](https://github.com/learnml-org/LearnML_LE) (MIT 라이선스)
- [LearnML PAE](https://github.com/learnml-org/LearnML_PAE) (MIT 라이선스)