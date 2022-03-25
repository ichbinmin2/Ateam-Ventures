# ✔️ 원티드 프리 온보딩 - 견적 요청 페이지 구현

## 에이팀벤처스

![에이팀벤처스ᅳ](https://user-images.githubusercontent.com/53133662/153177356-da26b823-1757-4287-80f9-46c8cba92e90.png)


## 프로젝트 소개

- 에이팀벤처스의 파트너스 견적요청을 확인하는 페이지 구현

- typescript로 안정적인 개발 환경 구현

- json-server & mock rest-api server 연동 및 배포

- 파트너 요청 페이지, 필터 같은 옵션에 따라 해당하는 아이템만 받아올 수 있는 페이지 구현

- UI 라이브러리를 사용하지 않고 직접 구현

- 미디어 쿼리로 모바일에서도 가독성이 높은 반응형 페이지 구현

## 팀 Repo 링크 가기

["On-Basic" Repo 바로가기](https://github.com/On-Basic/Ateam-Ventures)

## 배포 주소

[배포 사이트 바로가기](https://ateamventures.herokuapp.com/)

## 과제 구현 목록

☑️ json-server&dev-server 세팅(concurrently)하여 가상의 데이터 서버 구성

☑️ json-server로 mock rest-api server 연동

☑️ mock rest-api로 data 호출 및 type 지정

☑️ theme, global style 지정

☑️ 대시보드 메인보드 UI 스타일링

☑️ 대시보드 카드 UI 스타일링

☑️ 대시보드 Modal UI 및 기능 구현

☑️ 대시보드 메인 반응형 UI 스타일링

☑️ heroku를 이용한 json-server 배포

<br/>

## 기능 구현 영상

☑️ 셀렉트박스 카테고리별 액션

![셀렉트박스 카테고리별 액션](https://user-images.githubusercontent.com/84560867/153098729-6d8813c6-80c6-4b5c-8c92-2f110f74da35.gif)

☑️ 필터링 리셋

![필터링 리셋](https://user-images.githubusercontent.com/84560867/153098741-fa813733-bcae-4d21-b01a-baf33db397a8.gif)

☑️ 상담중 토글

![상담중 토글](https://user-images.githubusercontent.com/84560867/153098751-fe488eee-27e8-4b51-81df-d6e1b6ceb789.gif)

☑️ 모바일 버전 모달

![모바일 버전 모달](https://user-images.githubusercontent.com/53133662/153101561-95d3fc9c-9b9a-4907-8f04-3d7273f4c820.gif)


<br/>

## 새로 배웠거나 고민했던 지점 : [팀 노션으로 효율적인 팀 협업 진행하기](https://velog.io/@ichbinmin2/원티드-프리온보딩-프론트엔드-과정-3차-과제-견적-요청-페이지)

세번째 과제를 진행하면서, 이전에 내가 만들었던 팀 노션 페이지가 생각보다 활용도가 높지 않은 것 같다고 느껴졌다. 팀원들과 더 효율적으로 소통하고 팀원들 간에 보다 쉽게 정보를 공유하기 위해서 두번째 프로젝트가 끝난 후 시간적인 여유가 있을 때마다 노션 페이지를 틈틈이 수정했다. 결과적으로는 팀원들의 반응도 좋았고, 팀에 조금이나마 긍정적인 영향을 줄 수 있어서 뿌듯한 일이었다.

**팀 노션 메인 페이지**


![](https://images.velog.io/images/ichbinmin2/post/0095b6ce-a6ab-497f-8bcc-52844df8d749/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.30.44.png)

팀에서 회의 혹은 스크럼을 할 때마다 우리가 나눈 모든 논의들을 기록하고 후에도 복기할 수 있도록 정리하고자 했다. 다른 팀원들도 이 기록물들을 용이하게 사용할 수 있도록 아예 템플릿을 만들었는데 이것도 반응이 매우 좋았다!

**회의록**

![](https://images.velog.io/images/ichbinmin2/post/647f7c09-26ae-4620-a082-f5a68ee88308/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.31.11.png)

| 회의록 | 스크럼 |
|:----------:|:----------:|
|![](https://images.velog.io/images/ichbinmin2/post/4d69b085-60b8-49e2-a28a-df43850391c9/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.31.46.png) | ![](https://images.velog.io/images/ichbinmin2/post/69b68168-dc78-4b2f-aada-810a1ffe1350/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.32.37.png) |
</br>

**코딩 컨벤션 및 깃 커밋 가이드 라인**

이전에 우리가 구두로 합의하고 두서없이 정리되어있던 코딩 컨벤션이나 커밋 가이드 라인을 다시 정리했고, 다른 팀원들의 의견도 종합해서 최종적으로 수정한 내용을 공유해서 이번 프로젝트에 적용할 수 있었다.

</br>


| 코딩 컨벤션 | 깃 커밋 가이드 라인 |
|:----------:|:----------:|
|![](https://images.velog.io/images/ichbinmin2/post/0e9ae5cc-3b03-456b-95d0-f538a764e761/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.33.11.png) | ![](https://images.velog.io/images/ichbinmin2/post/e0c89123-943e-4fb9-b65f-e896657b02b6/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-03-23%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%208.33.47.png) |

</br>

프리온보딩 수업에서 멘토님께서 팀 협업이 얼마나 중요한지에 대해 이야기하신 적이 있다. 이 부분을 설명하시며 다른 팀분들이 어떻게 노션을 통해서 효율적으로 팀 협업을 진행하고 있는지에 대해 예시로 몇가지를 보여주셨었는데 팀 노션 페이지를 수정할 때 참고가 많이 됐다. 


## 프로젝트 후기

[✍🏻 프로젝트 회고 보러가기!](https://velog.io/@ichbinmin2/원티드-프리온보딩-프론트엔드-과정-3차-과제-견적-요청-페이지)

<br/>

## 설치 및 시작하는 법

**프로젝트 클론**

```
$ git clone https://github.com/On-Basic/Ateam-Ventures.git
```

**패키지 설치**

```
$ yarn
```

**서버 실행**

```
$ yarn dev // json-server 실행
$ yarn start:dev // localhost 실행
```
