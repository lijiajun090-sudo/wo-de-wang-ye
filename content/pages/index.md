---
type: PageLayout
title: 留学直通车_专注机械工程海外辅导
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      留学直通车，海外学业辅导
    subtitle: >-
      专注机械工程/力学本硕博海外留学生的一对一辅导：课程作业、论文写作、选课、申请建议。私塾式整学期、整学年保驾护航，妈妈再也不用担心我的学习。
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: 你的需求？
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: 辅导课程列表
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: 辅导套餐一览
    showFeaturedImage: false
    actions:
      - type: Link
        label: 更多问题
        url: /blog
    posts:
      - content/pages/blog/post-two.md
      - content/pages/blog/post-three.md
      - content/pages/blog/post-seven.md
      - content/pages/blog/post-four.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: 留下您的联系方式（严格保密），我们会尽快联系您进行课程规划。
    form:
      name: contact
      method: POST
      netlify: true
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
          label: 联系方式
          hideLabel: true
          placeholder: Email/微信
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: 请在此输入您的需求或问题
          isRequired: true
          width: full
          type: TextFormControl
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
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
