# Number-recognition

테스트 이미지 폴더

jupyter notebook 으로 작성한 숫자인식 프로그램

주제 : 랜덤한 위치와 랜덤한 크기의 나오는 200x200 pixels의 숫자 이미지를 분류

방법 : 트리를 사용한 분류

1. 막힌 도형이 있는가

-있다:4,6,8,9,0

-없다:1,2,3,5,7

2.막힌 도형이 2개인가

-그렇다 8

-아니다 4,6,9,0

3.막힌 도형이 삼각형인가

-그렇다 4

-아니다 6,9,0

4.동그라미의 중점의 위치를 통해 분류

-중점의 위치가 하단 6

-중점의 위치가 상단 9

-중점의 위치가 중간 0

------------------------막힌도형 분류완료 ---------------------

막히지 않은 도형은 (FeatureToGoodTrack)함수를 이용하여 특징점을 통해 

