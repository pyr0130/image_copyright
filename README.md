# Screen capture system for digital image copyright protection (Capstone design 2020-2)

## Overview
* Needs, problems
한국저작권보호원에 따르면 모바일 앱을 통한 불법복제는 2014년부터 계속 증가하는 추세를 보이며, 2017년을 기준으로 출판 중 웹툰 분야에서의 피해액은 약 2000억원 수준에 이르렀다. 한 서비스 업체는 AI를 활용해 불법 업로더를 추적하거나, 앱 자체에서 스크린 캡쳐를 방지하는 기술을 적용했지만, 전용 앱을 사용하지 않고 웹사이트에 접근하면 자유롭게 캡쳐가 가능하다는 맹점을 가진다.

* Goals, objectives (evaluation)
 본 프로젝트는 특정 웹사이트에서 스크린 캡쳐를 하면 암호화된 사용자 정보를 가리키는 인덱스 정보가 이미지에 보이지 않도록 삽입되어 저장되는 디지털 핑거프린트 방식을 제안하고자 한다. 


## Schedule
1) 암호화와 이미지 프로세싱 및 핑거프린트 삽입 기술에 대해 연구한다.
2) 연구를 바탕으로 사용자 개인정보를 암호화한다.
3) 암호화한 개인정보를 비가시적으로 이미지에 삽입한다. 
4) 캡쳐할 때 효율적으로 핑거프린트를 삽입하며, 이미지 훼손에도 정보를 추출할 수 있도록 성능을 향상시킨다.

|:Date:|:Contents:|:Progress:|
|--------|------------------------------------|-------------|
|:0330:|:연구계획서 작성 및 최종제출:|::|
|:0406:|:암호화 기법 연구 및 세부 구성 수정:|:[PDF](doc/0408.pdf):|
|:0413:|:AES 알고리즘 작성:|:[CODE](src/AES_cryptography/AES.ipynb):|
|:0420:|:워터마킹 논문 서칭:|::|
<!--## Results-->
<!--* Main code, table, graph, comparison, ...-->
<!--* Web link-->


## Conclusion
1) 불법으로 유출된 이미지를 확인해 우선 캡쳐된 이미지임을 확인하고, 그 후 이미지 내 삽입되어있는 핑거프린트를 추출해 유출자를 찾는다.
2) 저작권 보호가 필요한 사이트/어플에서만 이 기능이 활성화되도록 유지하여 사용자가 디바이스 사용에 불편함이 없게 한다.

<!--## Reports-->
<!--* Upload or link (e.g. Google Drive files with share setting)-->
<!--* Midterm: [Report](Reports/Midterm.pdf)-->
<!--* Final: [Report](Reports/Final.pdf), [Demo video](Reports/Demo.mp4)-->
