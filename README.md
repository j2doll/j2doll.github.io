# Welcome to github pages of j2doll

> *Read this in other languages: [English](English-page), :kr: [한국어](한국어-페이지)*

## English page

<!-- Who am I? -->

### Who am I?

- Hi! My alias name is j2doll. (aka Jay Two)
	- My name is Korean and it is not easy for foreigners to pronounce it. So I recommend you call me Jay Two.

- I'm a software programmer of South Korea. (South Korea is Republic of Korea.)

- I have been programming in various languages and environments for a long time.

<!-- Open Source Projects -->

### Open Source Projects

<!-- QtExcel -->

#### [QtExcel](https://github.com/QtExcel)
- QtExcel is a organization of excel(xlsx) libraries in Qt.
- I am the administrator of QtExcel.

###### [QXlsx](https://github.com/QtExcel/QXlsx)
- QXlsx is excel file(*.xlsx) reader/writer library.
- Because QtXlsx is no longer supported(2014), I created a new project that is based on QtXlsx. (2017-)
- Development language of QXlsx is C++. (with Qt)
- You don't need to use static library or dynamic shared object using QXlsx.

##### [Qxlnt](https://github.com/QtExcel/Qxlnt)
- Qxlnt is a helper project that allows xlnt to be used in Qt.
- xlnt is a excellent C++ library for using xlsx Excel files.
- I was looking for a way to make it easy to use in Qt. Of course, cmake is compatible with Qt, but it is not convenient to use. So I created Qxlnt.

##### [Qlibxlsxwriter](https://github.com/QtExcel/Qlibxlsxwriter)
- Qlibxlsxwriter is a helper project that allows libxlsxwriter to be used in Qt.
- libxlsxwriter is a C library for creating Excel XLSX files.

##### [QSimpleXlsxWriter](https://github.com/QtExcel/QSimpleXlsxWriter)
- Use SimpleXlsxWriter in Qt.
- SimpleXlsxWriter is C++ library for creating XLSX files for MS Excel 2007 and above.

<!--  ******************* -->

#### [QSLogLib](https://github.com/j2doll/QSLogLib)
- Log library for C++/Qt based on SLogLib.
- It is ported to Qt with improved devices and function.
- Standard output(console), Log File, UDP socket is supported.
- I will expand device to other types. (such as RDBMS, Serial, DDS, Bluetooth, etc)

#### [QTelnetServer](https://github.com/j2doll/QTelnetServer) 
- Telnet server 
- Seperated logic class (No elevation of account permissions required)

#### [QPing](https://github.com/j2doll/QPing)
- Ping class that is not using raw socket api

#### [wireshark-remote-command-win](https://github.com/j2doll/wireshark-remote-command-win)
- Capturing remote packet using Wireshark on Windows

#### [Population of South Korea](https://github.com/j2doll/Population-of-South-Korea)
- It is a site that graphs the population of South Korea(Republic of Korea).
- [https://j2doll.github.io/Population-of-South-Korea/](https://j2doll.github.io/Population-of-South-Korea/)

#### [json-downloader](https://github.com/j2doll/json-downloader)
- File Downloader for Windows Console(Terminal) using json download data.

#### [Responsive QML HMIs with Scaling](https://github.com/j2doll/responsive-qml-hmis-with-scaling)
- Copyright (C) 2015 Burkhard Stubert, Embedded Use (DBA), Germany All rights reserved.
- The HMIs of in-vehicle infotainment systems, TVs, phones and many other systems must adapt to different screen resolutions and formats. This adaptation should happen with as little duplicate effort as possible. The simplest way of doing this for QML HMIs is to scale the values of all x, y, width, height, margin and border properties in proportion to a reference resolution. Based on the HMI of a music player, I’ll show you how to do this by changing only the screen width and height.

#### [crl.Qt](https://github.com/j2doll/crl.Qt)
- Concurrency Runtime Library for Telegram Desktop
- This project uses Qt 5. (2018)

#### [jcon-cpp.Qt](https://github.com/j2doll/jcon-cpp.Qt)
- Set Qt project to [jcon](https://github.com/joncol/jcon-cpp) project
	- JCON-CPP is a portable C++ JSON RPC 2.0 library that depends on Qt.
- This project uses Qt 5. (2018)

#### [XMLDOMReader](https://github.com/j2doll/XMLDOMReader)
- XML DOM reader for Qt5

<!-- 	Lazy Projects -->

#### Lazy Projects
- [test-ccspriterx](https://github.com/j2doll/test-ccspriterx) is test code for CCSpriterX & Brash Monkey Spriter SCML.
- [Implicit sharing iterator problem of Qt](https://gist.github.com/j2doll/bb11c0c8d3d0ddd4066df151fb2dc12a) is a unique sample of Qt. It describe implicit sharing of Qt.
- [lmc-clone](https://github.com/j2doll/lmc-clone) is a lan messenger, instant messaging client. It based on lmc of sourceforge.
- [CStdString](https://github.com/j2doll/CStdString) is a string class for Windows compiler(Visual C++, Borlan C++, etc.) gcc(g++) is not supported. Original source code is come from [codeproject.](https://www.codeproject.com/Articles/1146/CString-clone-Using-Standard-C) Now some code not works.
- [Box2D Lite](https://github.com/j2doll/qbox2dl) : Now some code not works. I suggest to use new QML sample of github.
- [Benchmark performance of in-memory SQLITE on Qt](https://github.com/j2doll/benchmark-qt-sqlite-inmemory) You can fork current project to you, then test your own hardware, OS and Qt etc.
- [test-pnarallax-node](https://github.com/j2doll/test-pnarallax-node)

<!--  	freeware -->

#### Freeware

> My freeware is mostly made to Korean. I am going to translate in English someday.

- ConverT : It converts the time UTC, Local time, Epoch. (Korean local time is KST that is GMT+9h.) [Download](https://j2doll.github.io/files/ConverT.7z)
- TC-1 : It converts the time from seconds to date and time. [Download](https://j2doll.github.io/files/TC-1.zip)
- DisplayVersionOnDesktop : display current Windows detailed version string on desktop. [Download](https://j2doll.github.io/files/DisplayVersionOnDesktop.zip)
- ConvertU : convert plain text to UTF-8 & URl-encoded string. Very simple! [Download](https://j2doll.github.io/files/ConvertU.zip)
- IEBNTracker : A program that allows you to preview and test how to work with the Web using Internet Explorer. It traces BeforeNavigate envent and shows RL, PostData, Headers, TargerFrame. [Download](https://j2doll.github.io/files/IEBNTracker.zip)
- TinyTimeSync : NTP(SNTP) client program for Windows. [Download](https://j2doll.github.io/files/TinyTimeSyncNT.zip)
- litococlock : It's a clock program that is made in LittleWitch(Japan). Translate menu language to English. [Download](https://j2doll.github.io/files/litoco.zip)
- URLDownload : Translate menu language to Korean. Code from [codeproject](http://www.codeproject.com/KB/IP/urldownload.aspx). [Download](https://j2doll.github.io/files/URLDownload.zip)

<!--  	gitlab -->

#### Test code from books

- See [gitlab](https://gitlab.com/users/j2doll/projects) repo.

<!--  Commercial Projects  -->

### Commercial Projects

#### Defense Weapon System Project

##### Tactical Data Link System
- Tactical Data Link Software : C++, Qt, Linux, Network(ethernet), Etc.

##### Naval Landing Ship Command & Control Support System
- Tatical Server : C++, Visual Studio, Network(ethernet), Serial(RS-232 etc), Etc.

#### Vibration foundation project using construction software component(CAD) 
- C++, OpenGL, Visual Studio, Codejock Lib

#### Integrated business of telegram service of Korean major telegram company 
- C++, Visual Studio, Tuxedo, CCT Lib

#### Multimedia DRM(Digital Right Management) System 
- C++, Directshow(Filter), Cypher Algorithm

#### Old MSN Messenger Encryption Server 
- Proxy network programming, C++ Builer, MSNP(MSN Protocol, old protocol)

#### Exif(picture data) Viewer 
- C++, ActiveX(COM), Visual Studio

#### PDB(Protein DB) Viewer (prototype project)
- C++, Visual Studio, OpenGL

<!-- ******************** -->

## 한국어 페이지

### 누구냐고요?

- 안녕하세요! 깃허브에서 제 별칭은 Jay Two 입니다. 

- 대한민국의 소프트웨어 프로그래머입니다.

- 다양한 언어와 환경에서 여러가지 프로그래밍을 해왔습니다.

### 오픈 소스 프로젝트

<!-- QtExcel -->

#### [QtExcel](https://github.com/QtExcel)
- QtExcel는 Qt용 엑셀(xlsx) 라이브러리들의 그룹입니다.
- 저는 QtExcel의 관리자입니다.

##### [QXlsx](https://github.com/QtExcel/QXlsx)
- QXlsx는 엑셀 파일(*.xlsx)을 읽고 쓰는 라이브러리입니다.
- QtXlsx가 더이상 지원되지 않기 때문에(2014), QtXlsx에 기반한 새로운 프로젝트를 만들었습니다. (2017-)
- QXlsx는 개발언어로 C++를 사용합니다. (Qt 사용)
- QXlsx는 정적 또는 동적 라이브러리를 사용하지 않아도 되도록 제작되었습니다.

##### [Qxlnt](https://github.com/QtExcel/Qxlnt)
- Qxlnt는 xlnt가 Qt에서 사용될 수있게 해주는 도우미 프로젝트입니다.
- xlnt는 xlsx Excel 파일을 사용하기에 훌륭한 C++ 라이브러리입니다. :+1:
- xlnt를 Qt에서 사용하기 쉬운 방법을 찾고 있었습니다. 물론 cmake는 Qt와 호환되지만 사용하기가 쉽지 않습니다. 그래서 Qxlnt를 만들었습니다.

##### [Qlibxlsxwriter](https://github.com/QtExcel/Qlibxlsxwriter)
- Qlibxlsxwriter는 libxlsxwriter를 Qt에서 사용할 수 있는 도우미 프로젝트입니다.
- libxlsxwriter는 Excel XLSX 파일을 만들기위한 C 라이브러리 입니다.

##### [QSimpleXlsxWriter](https://github.com/QtExcel/QSimpleXlsxWriter)
- Use SimpleXlsxWriter in Qt.
- SimpleXlsxWriter is C++ library for creating XLSX files for MS Excel 2007 and above.

<!-- 그외 -->

#### [QSLogLib](https://github.com/j2doll/QSLogLib)
- SLogLib를 기반한 로그 라이브러리. (C++/Qt)
- 향상된 디바이스와 기능으로 포틍을 수행하였습니다.
- 표준 출력(console), 로그 파일, Udp 소켓이 지원됩니다.
- 다른 종류의 디바이스로 확장 예정입니다. (관계형 데이터베이스, 시리얼, DDS, 블루투스 등)

#### [QTelnetServer](https://github.com/j2doll/QTelnetServer)
- 텔넷 서버
- 로직 클래스가 분리되어 있음

#### [QPing](https://github.com/j2doll/QPing)
- 핑 클래스
- 로 소켓 함수를 사용하지 않음 (계정 권한의 상승이 필요 없음)

#### [wireshark-remote-command-win](https://github.com/j2doll/wireshark-remote-command-win)
- 와이어샤크를 이용하여 윈도우즈에서 원격으로 패킷 캡춰

#### [대한민국 인구](https://github.com/j2doll/Population-of-South-Korea)
- 대한민국의 인구를 그래프로 보여주는 싸이트입니다.
- [https://j2doll.github.io/Population-of-South-Korea/](https://j2doll.github.io/Population-of-South-Korea/)

#### [json-downloader](https://github.com/j2doll/json-downloader)
- json 정보 기반 파일 다운로더 (윈도우즈 콘솔용)

#### [확장성 있는 반응형 QML HMI](https://github.com/j2doll/responsive-qml-hmis-with-scaling)
- Burkhard Stubert 작성
- 차량용 인포테인먼트 시스템, TV, 휴대폰 및 기타 여러 시스템의 HMI는 다양한 화면 해상도 및 형식에 적응해야 합니다. 이 적응은 최대한 적은 중복 노력으로 이루어져야 합니다. QML HMI에서이 작업을 수행하는 가장 간단한 방법은 참조 해상도에 비례하여 모든 x, y, width, height, margin 및 border 속성의 값을 크기 조정하는 것입니다. 음악 플레이어의 HMI를 기반으로, 화면 너비와 높이 만 변경하여이 작업을 수행하는 방법을 보여 드리겠습니다.

#### [crl.Qt](https://github.com/j2doll/crl.Qt)
- 텔레그램 데스크탑용 동시성 런타임 라이브러리
- 이 프로젝트는 Qt 5를 사용합니다. (2018)

#### [jcon-cpp.Qt](https://github.com/j2doll/jcon-cpp.Qt)
- [jcon](https://github.com/joncol/jcon-cpp) 프로젝트에 Qt 프로젝트 추가
	- JCON-CPP는 C++ JSON RPC 2.0 라이브러리
- 이 프로젝트는 Qt 5를 사용합니다. (2018)

#### [XMLDOMReader](https://github.com/j2doll/XMLDOMReader)
- Qt5용 XML DOM reader

#### [Offset of struct](https://github.com/j2doll/offset-of-struct.kr)
- 구조체 멤버의 오프셋 얻기

#### 게으른 프로젝트
- [test-ccspriterx](https://github.com/j2doll/test-ccspriterx)는 Brash Monkey Spriter SCML를 사용하는 CCSpriterX를 테스트하는 코드입니다.
- [Qt의 암묵적 공유 반복자 문제](https://gist.github.com/j2doll/bb11c0c8d3d0ddd4066df151fb2dc12a) 는 독특한 Qt 예제입니다. Qt의 반복자(iterator)가 명시적이지 않은 처리를 암묵적으로 어떻게 처리하는 설명해 주는 좋은 예제입니다.
- [lmc-clone](https://github.com/j2doll/lmc-clone)는 랜 메신저입니다. sourceforge의 lmc를 기반으로 제작되었습니다.
- [CStdString](https://github.com/j2doll/CStdString)는 윈도우즈 컴파일러를 지원하는 문자열 클래스입니다.(Visual C++, Borlan C++ 등) gcc(g++)는 지원하지 않습니다. 원본 소스코드는  [codeproject](https://www.codeproject.com/Articles/1146/CString-clone-Using-Standard-C)가 출처입니다. 현재 일부 코드는 작동되지 않는 부분도 있습니다.
- [Box2D Lite](https://github.com/j2doll/qbox2dl) : 일부 코드가 작동되지 않음. 이 예제보다는 깃허브에 있는 QML 예제를 추전합니다.
- [Qt에서 인-메모리 SQLITE의 성능 테스트](https://github.com/j2doll/benchmark-qt-sqlite-inmemory) 이 프로젝트를 포크하여 여러분의 하드웨어/OS에서 성능을 테스트하실 수 있습니다.
- [test-pnarallax-node](https://github.com/j2doll/test-pnarallax-node)
- [Wireshark로 내가 만든 프로토콜 분석하기](https://github.com/j2doll/wireshark-dissector-lua.kr) 토스트에서 제작한 테스트 코드 (wireshark + lua)

#### 한글화 작업
- 저스트 닥스 한글화(작업중) [템플릿] [https://github.com/j2doll/just-the-docs.kr](https://github.com/j2doll/just-the-docs.kr)
- (Unofficial Korean branch) 개발자 및 infradev에 무료 등급이 제공되는 SaaS, PaaS 및 IaaS 허용 목록 [https://github.com/j2doll/free-for-dev.kr](https://github.com/j2doll/free-for-dev.kr)
- :construction: 피쉬 쉘(Fish Shell) 문서 한글화 작업 [https://j2doll.github.io/fish-shell-docs-kor/](https://j2doll.github.io/fish-shell-docs-kor/)
- 큐트 포 파이썬(Qt For Python) 문서 한글화 작업 [https://j2doll.github.io/Qt-for-Python-Docs-Kor/](https://j2doll.github.io/Qt-for-Python-Docs-Kor/)
- QML 글 [https://j2doll.github.io/qml-article/](https://j2doll.github.io/qml-article/)
- :construction: 무료 개발환경 [https://github.com/j2doll/free-for-dev.kr](https://github.com/j2doll/free-for-dev.kr)
- [Qt Android] Google Play의 향후 요구 사항을 준수하는 방법 (2019)  [https://github.com/j2doll/comply-upcoming-requirements-google-play-2019-kr](https://github.com/j2doll/comply-upcoming-requirements-google-play-2019-kr)

#### 프리웨어
- XlsxFactory : 엑셀(*.xlsx) 뷰어 [https://j2doll.tistory.com/654](https://j2doll.tistory.com/654)
- ConverT : UTC, Local time, Epoch 간의 시간을 변경. (대한민국의 local time은 KST이며, GMT보다 +9h이 차이납니다.) [Download](https://j2doll.github.io/files/ConverT.7z)
- TC-1 : 초에서 날자/시간으로 변경. [Download](https://j2doll.github.io/files/TC-1.zip)
- DisplayVersionOnDesktop : 윈도의 상세 버전을 데스크탑에 표시. [Download](https://j2doll.github.io/files/DisplayVersionOnDesktop.zip)
- ConvertU : 문자열을 UTF-8과 URL 인코딩을 함께 적용하여 변환합니다. 아주 간단함! [Download](https://j2doll.github.io/files/ConvertU.zip)
- IEBNTracker : A program that allows you to preview and test how to work with the Web using Internet Explorer. 인터넷 탐색기의 BeforeNavigate 이벤트를 추적하는 프로그램. RL, PostData, Headers, TargerFrame 등을 보여줍니다. [Download](https://j2doll.github.io/files/IEBNTracker.zip)
- TinyTimeSync : NTP(SNTP) 클라이언트 프로그램 (윈도우). [Download](https://j2doll.github.io/files/TinyTimeSyncNT.zip)
- litococlock : LittleWitch(일본)사의 시계 프로그램입니다. 메뉴 영문화 작업을 수행하였음. [Download](https://j2doll.github.io/files/litoco.zip)
- URLDownload : 메뉴 한글화 작업을 수행하였음. 코드는 [codeproject](http://www.codeproject.com/KB/IP/urldownload.aspx) [Download](https://j2doll.github.io/files/URLDownload.zip)

#### 서적의 테스트 코드
- [gitlab](https://gitlab.com/users/j2doll/projects) 저장소를 보세요.

<!-- ********* 상업용 프로젝트 ********** -->
### 상업용 프로젝트

#### 국방 무기체계 프로젝트

##### 전술 데이터링크 체계
- Tactical Data Link Software : C++, Qt, Linux, Network(ethernet), Etc.

##### 해군 상륙함 지휘지원체계
- Tatical Server : C++, Visual Studio, Network(ethernet), Serial(RS-232 etc), Etc.

#### 건설 컴포넌트(CAD)를 이용한 진동 기초 프로젝트
- C++, OpenGL, Visual Studio, Codejock Lib

#### 통신회사의 전보 통합 프로젝트
- C++, Visual Studio, Tuxedo, CCT Lib

#### 멀티미디어 DRM(Digital Right Management) 체계
- C++, Directshow(필터), 암호화 알고리즘

#### 구형 MSN 메신저 암호화 서버
- 프록시 네트워크 프로그래밍, C++ Builer, MSNP(구형 MSN 프로토콜)

#### Exif(사진 자료) 뷰어
- C++, ActiveX(COM), Visual Studio

#### PDB(단백질 데이터베이스) 뷰어 (프로토타입 프로젝트)
- C++, Visual Studio, OpenGL

