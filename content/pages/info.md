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
    text: >+
      # 嗨，我是Jack Ma老师，毕业于世界前50机械工程博士，现任东大某高校AP，擅长工程数学和力学类课程/学术写作。

    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
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
        textAlign: left
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
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: '无论你未来工作想去:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo4.svg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/logo5.svg
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
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    subtitle: '你可以学到的课程：'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: 微积分Calculus
            url: '/courses/calculus'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 线性代数Linear Algebra
            url: '/courses/linear-algebra'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 复变函数Complex Functions
            url: '/courses/complex-functions'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 数值方法Numerical Methods
            url: '/courses/numerical-methods'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 材料力学Mechanics of Materials
            url: '/courses/mechanics-of-materials'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 动力学Advanced Dynamics
            url: '/courses/advanced-dynamics'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 结构力学Structure Mechanics
            url: '/courses/structure-mechanics'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 流体力学Fluids Mechanics
            url: '/courses/fluid-mechanics'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: 工程热力学Engineering Thermodynamics
            url: '/courses/engineering-thermodynamics'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'C++'
      - type: Label
        label: 有限元FEM
        url:  '/courses/fem'
      - type: Label
        label: 计算流体力学CFD
        url:  '/courses/cfd'
      - type: Label
        label: Matlab
      - type: Label
        label: Chemkin
      - type: Label
        label: 传热传质Heat and Mass Transfer
        url:  'courses/heat-transfer'

  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [liuxuezhitongche2@outlook.com](mailto:liuxuezhitongche2@outlook.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience & Education:'
        text: |-
          **Current**

          * 东大某大学助理教授

          **2020-2024**

          * 世界前50博

          **2018-2020**

          * 世界前100硕

          **2014-2018**

          * 985本

        styles:
          self:
            textAlign: left

    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
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
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
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
      submitLabel: "Submit \U0001F680"
      styles:
        self:
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
        flexDirection: row
        textAlign: left
---
