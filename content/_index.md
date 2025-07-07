---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 欢迎访问复旦大学智能机器人与先进制造研究院<br>朱云龙课题组
        content: 我们致力于解决精准医疗与高端显示装备中的核心技术挑战：(1)通过聚焦磁控微纳机器人与泛血管介入机器人研究，实现药物靶向递送、显微外科与微创诊疗等临床需求；(2)围绕高分辨OLED宏量喷印技术，突破蒸镀工艺瓶颈，攻克G8.5大型喷墨打印装备与系统控制关键问题，推动OLED显示制造体系国产化升级。我们将材料科学、机器人控制与系统工程深度融合，赋能医疗与制造产业迈向智能化、数字化新阶段。
        align: center
        background:
          image:
#            filename: Magnetic Helical Miniature Robot.png
            filename: icon.png
            filters:
              brightness: 0.7
          position: right
          color: '#ffffff'
          background-size: contain   # 使图片完整显示
          max-width: 100%             # 限制图片最大宽度为100%
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
        ## 面向精准医疗的微纳机器人
        🔬 面向精准医疗的微纳机器人在药物靶向递送、显微外科手术、疾病诊断等细分领域具有重要的发展潜力，被誉为“颠覆性的”新型医学诊疗器件，被Science期刊发布最前沿的125个科学问题之一。
        
        - 生物型微纳机器人集群通信理论（面向生物信息传感）
        - 磁控微纳医疗机器人研究（面向精准医疗）
        - 磁性软体连续医疗机器人研究（面向血管介入与微纳机器人长程递送）
        
        ## 智能医疗机器人方向
        🦾 高分辨OLED宏量电子打印技术
        中国电子显示产业面临挑战：占全球面板60%产能，高端电子显示屏OLED制备工艺以“蒸镀工艺”为核心，但关键装备完全依赖进口。发达国家已将OLED装备列为“国家核心技术”，禁止向中国出口。喷墨打印制造技术，被产业界誉为是由“蒸镀工艺”向“喷墨打印”的技术转变的、颠覆性的显示产业技术革命，也是制作大尺寸OLED产业升级的主要方向。
        团队以G8.5重大装备的优化控制问题为抓手，攻克面向非线性、强耦合、多目标优化问题的百兆级宏量喷印协同优化控制难题，同时承担G8.5装备关键零部件的攻关与系统研制，打破国外对该核心装备的技术垄断，为建立全球第一条G8.5代OLED电子喷墨打印生产线提供关键技术支撑。

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
