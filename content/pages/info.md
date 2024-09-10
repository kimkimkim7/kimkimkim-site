---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >-
      ## 안녕하세요, 저는 김효정입니다. UI/UX 기획자로 일을 하고 있으며 피그마, 구글 프레젠테이션, 노션, 지라 사용이 능숙합니다. 다양한 분야의 앱의 초기 기획 및 릴리즈를 진행하였고, PM으로써 프로젝트의 전반적인 기획 및 일정 관리를 주도한 경험이 있습니다. 평소에는 새로운 정보를 탐색하거나 다양한 상상을 하는 것을 좋아하며 생산적인 활동을 하지 않을 때는 누워있습니다.
    media:
      type: ImageBlock
      url: /images/myface.png
      altText: my face
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: '제가 일했던 회사에요:'
    images:
      - type: riskzero
        url: /images/RISKZERO_CI.png
        altText: Logo one
        caption: Logo one
      - type: softlunch
        url: /images/softlunch.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/platfarm.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/daymedis.png
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/kbrand.png
        altText: Logo five
        caption: Logo five

    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-100
          - pr-100
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: 이력서
            url: https://drive.google.com/file/d/1gCgzHN7tK79PLGgvt-GmLdcVomEQzMax/view?usp=sharing
          - type: Link
            label: 포트폴리오
            url: https://drive.google.com/file/d/1kPpXiFIo3NDJofdTCzbDjO7FZEtSfSC5/view?usp=sharing


    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: '자세한 경력은 아래에서 확안하세요!:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: '다음과 같은 작업들을 할 수 있습니다!:'
    items:
      - type: Label
        label: figma(Intermediate)
      - type: Label
        label: google workspace(Expert)
      - type: Label
        label: JIRA (Intermediate)
      - type: Label
        label: adobe photoshop(Intermediate)
      - type: Label
        label: 노션 (Intermediate)

  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
 
  - type: TextSection
    variant: variant-a
    subtitle: '연락처는 다음과 같아요!:'
    colors: colors-f
    text: |
      [workim7777@gmail.com](mailto:workim7777@gmail.com)
 
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: '자세한 경력은 다음과 같아요!:'
        text: |-
          **리스크제로, 성동구**
          * 2023년 5월 - 2024년 5월 
          * 회사 소개 : 건설현장의 중대재해법에 필요한 문서를 PC나 APP으로 간편하게 작성할 수 있는 플랫폼
          * 업무 스킬 : figma, XD, Slack, notion.co, excel
          * 업무 경험
            1. 리스크제로 3.0 app 총괄 기획
            - PC버전만 있는 리스크제로 3.0 플랫폼의 app 버전 전체 기획
            2. 리스크제로 3.0 app 버전을 기반으로 경기주택공사에 맞게 변형
            - 관리자,근로자APP menu struchture, IA, flowchart, policy, 설계서, Validation, Rule
            3. 리스크제로 3.0 app 버전을 기반으로 서울시설공단에 맞게 변형
            - 현장 및 기술단 APP menu struchture, IA, flowchart, policy, 설계서, Validation, Rule
            4. 리스크제로 3.0 app 버전을 기반으로 울산항만공사에 맞게 변형
            - 관리자 APP menu struchture, IA, flowchart, policy, 설계서, Validation, Rule

          **소프트런치, 중구**
          * 2021년 7월 - 2022년 12월
          * 회사 소개 : 안드로이드 가계부 앱 ‘페이스토리' 개발 및 이랜드 멤버십 앱 ‘이멤버' 기술 제공
          * 업무 스킬 : figma, jira, google slides, Slack, notion.co, google meet
          * 업무 경험
          1. 이랜드 멤버십 앱 ‘이멤버' 관리
          - 이랜드에서 제공한 기획서를 바탕으로 소프트런치에서 개발할 수 있도록 매니징 역할 수행
          2. 안드로이드 가계부 앱 ‘페이스토리' 관리
          3. 아이폰 버전 페이스토리 앱 기획
          4. 공증 관련 앱 프로토타입 기획
          5. 이랜드와 연계할 마감 임박 상품 판매 앱 기획
          5. 시간 별로 작성하는 일기 앱 기획

          **플랫팜, 마포구**
          * 2019년 11월 - 2021년 4월
          * 회사 소개 : 채팅창에서 사용할 수 있는 mojitok(이모티콘 api) 제공 및 이모티콘 스토어 운영. whatapp, samsung message 등에 api 제공. 
          * 업무 스킬 : google slides, Slack, Jira, notion.co, google meet
          * 업무 경험
          1. mojitok에서 판매되는 이모티콘 스토어 웹페이지 관리 및 이모티콘 제안 및 승인 과정 매니징)
          - 제안된 이모티콘 심사 및 큐레이
          - 심사 과정과 큐레이팅 과정 시간 단축 방안 기획 후 적용 실행 후 60% 단축
          - 홈페이지에서의 제안 과정 개선
          2. 콘텐츠 제작 관리 이모티콘 제작 기획 및 관리(고양시청, KPGA 이모티콘 제작)
          - 콘텐츠 수급 관리 크리에이터 및 이모티콘 수급을 위한 방안 제안 및 실행- 실행 후 30% 상o
          - 크리에이터 관리 크리에이터용 뉴스레터 매주 발행- 심사과정에서의 CS 문의 대응
          3. 정산 프로세스 구축 : 새로 변경된 프로세스에 맞는 정산 프로세스 구축

          **데이메디스, 은평구**
          * 2018년 12월 - 2019년 6월
          * 회사 소개 : 생활 속에 필요한 건강 관련 제품 제작 및 판매
          * 업무 스킬 : power point, imweb
          * 업무 경험
          1. 자체 웹 쇼핑몰, 쇼핑몰 연계 사용 후기 관련 콘텐츠 웹페이지 브랜드 관리 및 전략 기
          - 브랜드 아이덴티티 구축 및 SNS 관리«
          - 각 브랜드의 웹페이지 구조 및 전략 기
          - 각 브랜드의 방문자 추이 분석 후 구매 전환 방법 모색
          2. 브랜드 웹페이지 리뉴얼 기획- “아임오" 생리대 웹페이지 리뉴얼 기획 및 진행
          3. 제품 개발 및 기획- 수면 브랜드 “스르르" 브랜드 개발 및 아이덴티티 구축
          - 스르르 베개 와디즈 런칭 (3000% 달성)
          - 고체가글 제품 와디즈 런칭 기획
          콘텐츠 웹페이지 관리
          - 스케줄별 콘텐츠 제작 후 업로드

          **케이브랜드어쏘시에이츠, 용산구**
          * 2015년 2월 - 2018년 4월
          * 회사 소개 : 브랜드 개발 에이전시 (고객사 : sk c&c, 하이원 리조트, 망원시장, 세방전지 등)
          *  업무 스킬 : power point, excel, 나라장터
          * 업무 경험
          1. 브랜드 개발 전략 및 기획
          - 브랜드 개발 입찰 진행에 필요한 서류작업 및 제안서 작성
          - 계약진행에 필요한 서류 작성
          - 선금 및 잔금 진행에 필요한 보고서 및 세금계산서 발행
          - 브랜드 개발 기획 및 컨택 포인트 역할
          - 담당 프로젝트 : 하이원 리조트 브랜드 리뉴얼 개발 (2018), 망원시장 브랜드 개발(2017),KT뮤직 V플랫폼 BI 개발(2016), SK C&C new ICT 5종 개발(2016) ...
     
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0

    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "제 작업들이 흥미롭나요? 연락주세요!"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
