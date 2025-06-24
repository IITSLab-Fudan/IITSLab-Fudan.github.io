---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
#  - block: hero
#    content:
#      title: |
#        复旦工业智能与技术系统实验室
#      image:
#        filename: welcome.jpg
#      text: |
#        <br>
#        
#        复旦大学工业智能技术与系统实验室，致力于……

  - block: markdown
    content:
      title: '📚 研究内容'
      subtitle: '医疗机器人'
      text: |-
        ## 光学显微与半导体检测方向
        🔬 聚焦光学显微技术创新与半导体检测装备国产化
        基于光学相干断层扫描（OCT）与计算成像技术，研发高速高分辨显微系统，突破亚微米级三维检测精度。主要应用于：
        
        - 半导体晶圆缺陷智能检测
        - 纳米级三维形貌动态分析
        - 集成电路关键尺寸测量
        
        通过自适应光学校正与深度学习算法融合，形成具有自主知识产权的检测装备体系，助力国产半导体设备打破海外技术垄断。
        
        ## 智能医疗机器人方向
        🦾 开发精准微创诊疗机器人系统
        面向肿瘤介入、神经外科等临床场景，研制多自由度手术机器人平台，集成：
        
        - 多模态影像实时融合导航
        - 力反馈精准控制技术（精度<100μm）
        - 智能人机协作操作界面
        
        重点攻克柔性器械精准操控、生物组织动态补偿等关键技术，形成覆盖术前规划-术中导航-术后评估的全流程解决方案，推动优质医疗资源下沉基层。
    design:
      columns: '1'
      background:
        color: "#f8f9fa" # 浅灰色（可替换为其他颜色值，如 #ffffff 纯白）
        text_color_light: false # 当背景为浅色时建议关闭浅色文字
      spacing:
        padding: ['20px', '0', '20px', '0']

      
#  - block: collection
#    content:
#      title: Latest News
#      subtitle:
#      text:
#      count: 5
#      filters:
#        author: ''
#        category: ''
#        exclude_featured: false
#        publication_type: ''
#        tag: ''
#      offset: 0
#      order: desc
#      page_type: post
#    design:
#      view: card
#      columns: '2'
  

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
