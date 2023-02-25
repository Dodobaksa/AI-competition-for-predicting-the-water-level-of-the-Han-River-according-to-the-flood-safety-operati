# AI-competition-for-predicting-the-water-level-of-the-Han-River-according-to-the-flood-safety-operation
In 10 minutes, to predict the water level of the four bridges, Cheongdam Bridge, Submersible Bridge, Hangang Bridge, and Haengju Bridge, various derivative variables are generated, experimented, and model advanced

___
## Description
As natural disasters such as floods continue to occur due to recent climate change, the role of dams to protect the lives and safety of the people by minimizing flood damage is becoming very important. Paldang Dam is a dam managed and operated by Korea Hydro & Nuclear Power (KHNP) and serves as the last bastion for flood defense in Seoul and the metropolitan area. It is expected that damage caused by flood disasters can be prevented and minimized by predicting the water level at major points (submersible bridges, etc.) of the Han River in Seoul according to the flood safety operation of Paldang Dam.

___
## Operating System and Development Environment
Windows 10 Enterprise, 64비트 운영 체제(x64 기반 프로세서)
Intel(R) Core(TM) i7-10700KF CPU @ 3.80GHz   3.80 GHz
RAM 16.0GB
*python version 3.9.7

___
## Library Version
pandas 1.3.4
numpy 1.19.5
lightgbm 3.3.2
tensorflow 2.7.0
keras 2.7.0
scipy 1.7.1
scikit-learn 1.1.2
statsmodels 0.12.2
tqdm 4.62.0

___
## API and file data usage sources
변수: 중랑천 수위&유량, 탄천 수위&유량, 안양천 수위&유량, 
출처: 한강홍수 통제소
URL:http://www.hrfco.go.kr/main.do

변수: 증발량, 기온, 일조, 일사
출처:기상자료개방포털
URL: https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36&tabNo=1

변수: 강화대교조위
출처: 바다누리 해양정보 서비스
UTL: http://www.khoa.go.kr/oceangrid/khoa/takepart/openapi/openApiObsServiceInfo.do

변수: 청담대교수위, 잠수교수위, 한강대교수위, 행주대교수위
출처:한강홍수통제소
URL:http://www.hrfco.go.kr/main.do

___
## Poster
![포스터한강](https://user-images.githubusercontent.com/97015589/221364958-cbc1bf2d-f911-4a1c-9ef4-c7bb6854b43d.jpg)
