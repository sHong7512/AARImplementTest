# AARImplementTest

aar 파일을 libs폴더에 넣고 implement하는 예제

1. 안드로이드 4.2 버전에서는 gradle -> task가 안뜰수 있음. 

preferences(settings) -> Experimental -> Do not build Gradle task list during Gradle sync 체크 해제 -> sync project with gradle files

하면 task폴더가 표시된다.


2. aar파일 위치
 
Gradle에서 assemble release로 빌드하면 project - build - outputs - aar 폴더에 있음


3. 자세한 방법은 레퍼런스 참고 

- 기본 aar 가져오기

reference : https://developer.android.com/studio/projects/android-library?hl=ko

- jitpack 퍼블리싱 

reference : https://dev.to/vtsen/how-to-publish-android-library-on-jitpackio-with-github-50n1

- jitpack 주소

https://jitpack.io/#sHong7512/AARLibraryExample
