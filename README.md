# SMSWH_Team20
# 팀명<잇눈송팀> 프로젝트명 <ITSONGTEM>

- 구성원
    
    이지원(1815595) - 팀장
    
    이민재(1812084), 최다연(1813592) -
    

### 🔹산출물 주소

(예시) https://github.com/Sookmyung-Software-Hackathon/your_repository_url

### 🔹분야

- 웹

## 🔶서비스 개요

---

- 학교 마스코트 캐릭터인 눈송이를 이용한 굿즈를 제작하고 싶은 숙명여대 동문이라면 누구나 참여가능한 눈송이 굿즈 펀딩 플랫폼입니다.
- 홈페이지 홈 화면에서 학우들의 아이디어로 완성된 제품의 시안을 보고, 마음에 드는 굿즈라면 선결제를 통해 신청할 수 있습니다.
- 선결제가 진행되는 만큼, 플랫폼에서는 구매자와의 실시간 소통을 위한 창구 기재를 의무화하고 있으며, 구매자는 공구 주최자와의 소통에 어려움을 겪지 않고 진행상황을 실시간으로 확인할 수 있습니다.
- 공구 주최자가 글을 게시하고 2주 안에 작성자가 지정한 최소 인원수가 넘는다면 공구 진행이 확정되며, 이후로부터는 공구 주최자가 미리 기입해둔 공지사항 전달 창구를 통해 구매자들에게 진행상황, 상품 수령 방법등을 전달합니다.
- 최소 인원수를 넘지 못할 경우 자동 취소되며, 환불이 진행됩니다.

## 🔶서비스 목적

---

- ITSONGTEM은 "비대면 상황속에서, 숙명여대 재학생들간의 교류 그리고 소속감을 느끼게 할 수 있는 플랫폼이 없을까?" 라는 생각에서 출발하였습니다.
- 학교 학우들 모두에게 익숙하고 사랑받는 우리학교 마스코트 <눈송이>를 이용해서 학우들간의 아이디어 교류와 숙명여대의 소속감을 높이려는 목적으로 시작합니다.

## 🔶핵심 기술 및 주요 기능

---

- 로그인
- 회원가입
- 공구 작성하기
- 전체 글 조회
- 각 공구 게시글 조회
- 내가 신청한 / 주최한 공구 목록
- Front_End
    - React
- react modules
    
    ![KakaoTalk_20211107_190750304.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/729738a0-8e94-49bc-aecf-b88993623036/KakaoTalk_20211107_190750304.png)
    

- Back_End
    - Mysql, amazon s3, amazon ec2
        - database ERD
        
        ![erd 모델.PNG](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/56bca90c-047c-425d-92d9-9c6397ce43ac/erd_모델.png)
        
    - nodejs
        - npm modules
            
            ![node module.PNG](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/46495c79-dc85-4aee-b955-adbd1a837643/node_module.png)
            

## 🔶기대효과

---

- 기존의 커뮤니티에서 공구를 진행하는데 존재했던 다음과 같은 어려움들을 해결할 수 있습니다
    - 선결제 시스템을 도입하여 수요조사와 실신청 숫자의 차이로 인해 공구가 중도 무산되는 경우를 방지할 수 있습니다.
    - 공구 주최자가 직접 문의처와 공지 소통 창구를 상품 페이지에 기입해둠으로써, 공구 참여자가 좀 더 쉽게 주최자와 소통이 가능합니다.
    - 일일이 공구 주최자의 계좌에 송금하는 방식이 아닌, 플랫폼 중도 결제를 이용하는 방식으로 금액 집계가 편리합니다.
    - 기존 존재하던 플랫폼들은 홍보 등의 목적으로 계정을 사고파는 사례가 있었는데, 숙명 gmail과 연동하여 계정을 생성하는 방식으로 진행한다면 이와 같은 부정적인 사례를 방지할 수 있습니다.
- 학교의 마스코트인 <눈송이>를 이용한 굿즈 제작이므로, 학교 홍보와 재학생들의 애교심을 높이는데에 도움이 됩니다.
- 누구나 아이디어를 게시하고 참여할 수 있는 플랫폼인 만큼, 학우들의 교류의 현장이 될 수 있습니다.

## 🔶페이지 구성(시나리오)

---

![Untitled Diagram.drawio.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/331a7389-0319-444e-987f-485bcc3c8cc8/Untitled_Diagram.drawio.png)

Figma 디자인 링크 : [https://www.figma.com/file/vf5jrcmlrnPiMxLVSVQrvt/Temporary-Design?node-id=3%3A2](https://www.figma.com/file/vf5jrcmlrnPiMxLVSVQrvt/Temporary-Design?node-id=3%3A2)