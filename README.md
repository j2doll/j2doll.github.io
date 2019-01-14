# Welcome to github pages of j2doll (aka Jay two)

> *Read this in other languages: [English](README.md), :kr: [한국어](README.ko.md)*

## Who am I?
- Hi! My alias name is j2doll. (aka Jay Two)
	- My name is Korean and it is not easy for foreigners to pronounce it. So I recommend you call me Jay Two.
- I'm a software programmer of South Korea. (South Korea is Republic of Korea.)
- I have been programming in various languages and environments for a long time.

## Contact
- :octocat: [https://github.com/j2doll](https://github.com/j2doll)
- :mailbox_with_mail:  [https://github.com/j2doll/discussion/issues](https://github.com/j2doll/discussion/issues)
- :page_with_curl: Blog(Korean) [https://j2doll.tistory.com](https://j2doll.tistory.com)
- My native language is not English and my English is not fluent. Please, use easy English. :-)

## Open Source Projects

### [QtExcel](https://github.com/QtExcel)
- QtExcel is a organization of excel(xlsx) libraries in Qt.

#### [QXlsx](https://github.com/QtExcel/QXlsx)
- QXlsx is excel file(*.xlsx) reader/writer library.
- Because QtXlsx is no longer supported(2014), I created a new project that is based on QtXlsx. (2017-)
- Development language of QXlsx is C++. (with Qt)
- You don't need to use static library or dynamic shared object using QXlsx.

#### [Qxlnt](https://github.com/QtExcel/Qxlnt)
- Qxlnt is a helper project that allows xlnt to be used in Qt.
- xlnt is a excellent C++ library for using xlsx Excel files.
- I was looking for a way to make it easy to use in Qt. Of course, cmake is compatible with Qt, but it is not convenient to use. So I created Qxlnt.

#### [Qlibxlsxwriter](https://github.com/QtExcel/Qlibxlsxwriter)
- Qlibxlsxwriter is a helper project that allows libxlsxwriter to be used in Qt.
- libxlsxwriter is a C library for creating Excel XLSX files.

#### [QSimpleXlsxWriter](https://github.com/QtExcel/QSimpleXlsxWriter)
- Use SimpleXlsxWriter in Qt.
- SimpleXlsxWriter is C++ library for creating XLSX files for MS Excel 2007 and above.

### [QSLogLib](https://github.com/j2doll/QSLogLib)
- Log library for C++/Qt based on SLogLib.
- It is ported to Qt with improved devices and function.
- Standard output(console), Log File, UDP socket is supported.
- I will expand device to other types. (such as RDBMS, Serial, DDS, Bluetooth, etc)

### [QTelnetServer](https://github.com/j2doll/QTelnetServer) 
- Telnet server 
- Seperated logic class (No elevation of account permissions required)

### [QPing](https://github.com/j2doll/QPing)
- Ping class that is not using raw socket api

### [wireshark-remote-command-win](https://github.com/j2doll/wireshark-remote-command-win)
- Capturing remote packet using Wireshark on Windows

### [Population of South Korea](https://github.com/j2doll/Population-of-South-Korea)
- It is a site that graphs the population of South Korea(Republic of Korea).
- [https://j2doll.github.io/Population-of-South-Korea/](https://j2doll.github.io/Population-of-South-Korea/)

### [json-downloader](https://github.com/j2doll/json-downloader)
- File Downloader for Windows Console(Terminal) using json download data.

### [Responsive QML HMIs with Scaling](https://github.com/j2doll/responsive-qml-hmis-with-scaling)
- Copyright (C) 2015 Burkhard Stubert, Embedded Use (DBA), Germany All rights reserved.
- The HMIs of in-vehicle infotainment systems, TVs, phones and many other systems must adapt to different screen resolutions and formats. This adaptation should happen with as little duplicate effort as possible. The simplest way of doing this for QML HMIs is to scale the values of all x, y, width, height, margin and border properties in proportion to a reference resolution. Based on the HMI of a music player, I’ll show you how to do this by changing only the screen width and height.

## [crl.Qt](https://github.com/j2doll/crl.Qt)
- Concurrency Runtime Library for Telegram Desktop
- This project uses Qt 5. (2018)

## [jcon-cpp.Qt](https://github.com/j2doll/jcon-cpp.Qt)
- Set Qt project to [jcon](https://github.com/joncol/jcon-cpp) project
	- JCON-CPP is a portable C++ JSON RPC 2.0 library that depends on Qt.
- This project uses Qt 5. (2018)

### Lazy Projects
- [test-ccspriterx](https://github.com/j2doll/test-ccspriterx) is test code for CCSpriterX & Brash Monkey Spriter SCML.
- [Implicit sharing iterator problem of Qt](https://gist.github.com/j2doll/bb11c0c8d3d0ddd4066df151fb2dc12a) is a unique sample of Qt. It describe implicit sharing of Qt.
- [lmc-clone](https://github.com/j2doll/lmc-clone) is a lan messenger, instant messaging client. It based on lmc of sourceforge.
- [CStdString](https://github.com/j2doll/CStdString) is a string class for Windows compiler(Visual C++, Borlan C++, etc.) gcc(g++) is not supported. Original source code is come from [codeproject.](https://www.codeproject.com/Articles/1146/CString-clone-Using-Standard-C) Now some code not works.
- [Box2D Lite](https://github.com/j2doll/qbox2dl) : Now some code not works. I suggest to use new QML sample of github.
- [Benchmark performance of in-memory SQLITE on Qt](https://github.com/j2doll/benchmark-qt-sqlite-inmemory) You can fork current project to you, then test your own hardware, OS and Qt etc.

## Commercial Projects

### Defense Weapon System Project

#### Tactical Data Link System
![](image/tdl2.jpg)
- Tactical Data Link Software : C++, Qt, Linux, Network(ethernet), Etc.

#### Naval Landing Ship Command & Control Support System
![](image/lpx.jpg)
- Tatical Server : C++, Visual Studio, Network(ethernet), Serial(RS-232 etc), Etc.

### Other projects
- Vibration foundation project using construction software component(CAD) : C++, OpenGL, Visual Studio, Codejock Lib
- Integrated business of telegram service of Korean major telegram company : C++, Visual Studio, Tuxedo, CCT Lib
- Multimedia DRM(Digital Right Management) System : C++, Directshow(Filter), Cypher Algorithm
- Old MSN Messenger Encryption Server : Proxy network programming, C++ Builer, MSNP(MSN Protocol, old protocol)
- Exif(picture data) Viewer : C++, ActiveX(COM), Visual Studio
- PDB(Protein DB) Viewer (It's prototype project.) : C++, Visual Studio, OpenGL

## Freeware
> My freeware is mostly made to Korean. I am going to translate in English someday.

- ConverT : It converts the time UTC, Local time, Epoch. (Korean local time is KST that is GMT+9h.) [Download](https://j2doll.github.io/files/ConverT.7z)
- TC-1 : It converts the time from seconds to date and time. [Download](https://j2doll.github.io/files/TC-1.zip)
- DisplayVersionOnDesktop : display current Windows detailed version string on desktop. [Download](https://j2doll.github.io/files/DisplayVersionOnDesktop.zip)
- ConvertU : convert plain text to UTF-8 & URl-encoded string. Very simple! [Download](https://j2doll.github.io/files/ConvertU.zip)
- IEBNTracker : A program that allows you to preview and test how to work with the Web using Internet Explorer. It traces BeforeNavigate envent and shows RL, PostData, Headers, TargerFrame. [Download](https://j2doll.github.io/files/IEBNTracker.zip)
- TinyTimeSync : NTP(SNTP) client program for Windows. [Download](https://j2doll.github.io/files/TinyTimeSyncNT.zip)
- litococlock : It's a clock program that is made in LittleWitch(Japan). Translate menu language to English. [Download](https://j2doll.github.io/files/litoco.zip)
- URLDownload : Translate menu language to Korean. Code from [codeproject](http://www.codeproject.com/KB/IP/urldownload.aspx). [Download](https://j2doll.github.io/files/URLDownload.zip)


## Test code from books
- See [gitlab](https://gitlab.com/users/j2doll/projects) repo.
