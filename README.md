<h1 align="center">Final Cut Pro</h1>
<h5 align="center">Personal Study<br>by Juneyoung KANG</h5>

[<p align = "center">
![GitHub developer](https://img.shields.io/badge/Developer-Juneyoung%20Kang-blue.svg?longCache=true&style=flat-square)](https://github.com/Juneyoung-Kang)<br>[![HitCount](http://hits.dwyl.io/Juneyoung-Kang/final-cut-pro.svg)](http://hits.dwyl.io/Juneyoung-Kang/final-cut-pro) [![GitHub license](https://img.shields.io/github/license/Juneyoung-Kang/final-cut-pro.svg?longCache=true&style=flat-square)](https://github.com/Juneyoung-Kang/final-cut-pro/blob/master/LICENSE)

### 파이널컷 프로와 프리미어 프로와의 차이점 
Adobe의 프리미어 프로와 Apple의 파이널컷 프로 모두 영상편집 프로그램의 양대산맥이다. 하지만 두 프로그램은 다른 점이 있다. 영상편집에 필요한 소스파일을 관리하는 방법에 차이가 있는데, 프리미어는 가져오기를 통해 영상 편집에 필요한 소스들(영상 영상, 음악, 이미지 파일)이 원래 위치 그대로 있는 반면에, 파이널컷의 경우 라이브러리, 이벤트, 프로젝트와 같은 개념으로 영상편집 소스 파일들을 관리한다. 이때 파이널컷에서는 가져오기를 통해 소스들을 임포트하는 경우 라이브러리 안으로 모두 복사가 되며, 라이브러리 내에서 관리하게 된다. 

### 라이브러리, 이벤트, 프로젝트
라이브러리를 아파트에 비유하면 그 안에 동호수와 같은 개념인 이벤트가 있고, 집 안의 방인 프로젝트에서는 각 방에 가구를 배치하듯 각각의 소스들을 배치할 수 있다.

### Hello, Final Cut Pro!
- **새로운 라이브러리 생성하기**  
`File - New - Library`를 클릭한다.  
파이널컷은 기본적으로 라이브러리안에 모든 영상 소스 파일들을 저장한다.
- **자동으로 만들어지는 이벤트**  
라이브러리를 생성하는 경우 자동적으로 라이브러리를 생성한 날짜 이름으로 이벤트 폴더가 만들어진다. 
- **파일 가져오기**  
`Import Media`를 통해 영상 편집에 필요한 소스 파일들을 불러온다. `[Cmd + I]`
- **새로운 프로젝트 생성하기**  
실질적으로 영상 편집이 이루어지는 타임라인을 만들어주어야 한다.  
프리미어에서 시퀸스의 개념이 파이널컷에서는 프로젝트이다.  
`New Project`를 클릭하여 프로젝트를 생성한다.

### 영상 배치하기
- **파일 삽입하기**  
삽입하고자 하는 파일을 선택한 후 드래그하여 타임라인에 삽입할 수 있다. 
- **영상 계단식 배치**  
영상을 서로 중복하여 배치가 가능하다. 가장 상위의 영상을 보여주게 된다.
- **영상 배치의 3가지 방법**  
`Insert`(삽입), `Append`(덧붙이기), `Overwrite`(덮어쓰기)  
영상 배치 전 항상 타임인디케이터가 어디에 있는지 확인해야 한다.    
    - **Insert**  
Insert는 타임인디케이터를 기준으로 영상을 중간에 넣는 방식이다. `[W]`
    - **Append**  
Append는 영상 가장 마지막 부분에 붙여주는 방식이다. `[E]`  
타임라인을 굳이 옮기지 않더라도 영상의 마지막 부분에 배치하기 때문에 좀 더 시간을 절약하면서 효율적으로 배치할 수 있다는 장점이 있다.
    - **Overwrite**  
Overwrite는 타임인디케이터 기준으로 영상을 덮어쓰는 방법이다. `[D]`