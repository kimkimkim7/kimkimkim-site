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

  - type: MediaGallerySection
    colors: colors-f
    subtitle: '제가 일했던 회사에요:'
    images:
      - type: ImageBlock
        url: /images/RISKZERO_CI.png
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
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
          - pl-4
          - pr-4
        justifyContent: space-between
        alignItems: center
      title:
        textAlign: center
      subtitle:
        textAlign: center

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
    subtitle: '자세한 경력은 아래에서 확인하세요!:'

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
          label: Sign me up to receive my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit 🚀"
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
