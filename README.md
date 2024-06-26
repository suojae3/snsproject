# iOS: SNS Project 
>개발기간: 2023/08/14 월요일 ~ 2023/08/18 금요일<br>
>발표: 2023/08/21 월요일

## 소개
<table>
  <tbody>
    <tr>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/Luna828">
       <img src="https://avatars.githubusercontent.com/u/93186591?v=4" width="100px;" alt="Luna828"/>
       <br />
         <sub>
           <b>김은경</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/riyeonlee">
       <img src="https://avatars.githubusercontent.com/u/139096422?v=4" width="100px;" alt="이리연"/>
       <br />
         <sub>
           <b>이리연</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/se-ryeong">
       <img src="https://avatars.githubusercontent.com/u/139101661?v=4" width="100px;" alt="이세령"/>
       <br />
         <sub>
           <b>이세령</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/suojae3">
       <img src="https://avatars.githubusercontent.com/u/126137760?v=4" width="100px;" alt="조규연"/>
       <br />
         <sub>
           <b>전종혁</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
    </td>
    <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/HAHOHAHOL">
       <img src="https://avatars.githubusercontent.com/u/139090041?v=4" width="100px;" alt="조규연"/>
       <br />
         <sub>
           <b>하호형</b>
         </sub>
       </a>
       <br />
     <sub>
         <b>iOS Developer</b>
     </sub>
     <br />
    </td>
  </tbody>
</table>

## 와이어 프레임
참조: 와이어 프레임의 사진의 출처는 @nimbus_cloud_dog 입니다 (가장 좋아하는 강아지 사진이라 가져왔어요)
![IMG_1541](https://github.com/iOS-TEAM11/snsproject/assets/93186591/4cd5cf64-c28b-4ecf-9b2f-bfd378e954cf)
![IMG_1542](https://github.com/iOS-TEAM11/snsproject/assets/93186591/77354c97-fd96-4e6a-9e4d-0deedfb57c85)

## 역할분담
[발표자료 Notion](https://teamsparta.notion.site/11-S-A-07637d8a984947be945dba731cf12c6b)
* 이세령: 홈 피드 화면 구현하기 및 TabBar 구현, 피드 댓글 구현 
* 전종혁: UIImagePicker를 사용하여 앨범에서 사진 고르기 및 피드 추가 구현
* 김은경: 프로필 화면 구현 및 프로필 사진 앨범에서 고를 수 있게 만들기
* 하호형: 프로필 편집 화면 구현
* 이리연: UIKit 공부 및 Swift 스터디

### 팀 규칙
* 각자가 맡은 일에 충실할 것
* 8PM 개발 진척도 확인 및 문제점 공유 및 해결
* commit 메세지 수시로 작성해두기

## 앱 시현 영상
영상 사이즈가 너무 커서 이미지로 대체하도록 하겠습니다
<table>
  <tbody>
    <tr>
      <td>
        <img src="https://github.com/iOS-TEAM11/snsproject/assets/93186591/4ae3affd-b743-438f-8a84-deaceace029b" width = 200 height = 400>
      </td>
       <td>
        <img src="https://github.com/iOS-TEAM11/snsproject/assets/93186591/cf5bff81-699e-4e04-8a22-77c34d94e004" width = 200 height = 400>
      </td>
       <td>
        <img src="https://github.com/iOS-TEAM11/snsproject/assets/93186591/d27cf1b7-48e5-447f-9f98-a8ec7a062432" width = 200 height = 400>
      </td>
      <td>
        <img src="https://github.com/iOS-TEAM11/snsproject/assets/93186591/aa1364f8-61f9-4d77-9e0b-8bcdf032080e" width = 200 height = 400>
      </td>
    </tr>
  </tbody>
</table>

[자세한 기능 구현 영상](https://youtu.be/OzzGY_m__vg)

## 프로젝트 주요 기능

- 전종혁 : CreatePage, Dummy Data
    
    > *UIViewController, 데이터 Post 모델 구조 작성,* UIImagePicker, UIAlertController, UIButton: PullDownButton
    > 
    
- 이세령 : Feed, TabBar, 댓글
    
    > *UITableView, UITabBarController, UIViewController, UITableViewDelegate*
    > 
    
- 김은경 : MyPage, Dummy Data
    
    > *UI(MyPageCell, PostCell)CollectionView 구성 , UILongPressGesture,                      Singleton pattern적용*
    > 
    
- 하호형 : EditProfile
    
    > *UIViewController,* UIScrollView
    >

## 추후 구현 목표
- 중복 코드 제거
- MVC 패턴 나눠보기 → 튜터님께 방식 여쭤보기
- storyboard에 있는 MyFeedCell  stackView 감싸서 2개의 Label로 바꾸기
- 릴스 + 돋보기 기능 추가

