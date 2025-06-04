---
title: "Curriculum Vitae"
date: 2025-06-03
# type: page           # theme choices: landing / resume / resume-pro
# layout: index
sections:
  - block: resume-biography
    content:
      # "username" 要跟 content/authors 下的資料夾名稱相同
      username: admin
  - block: resume-experience
    content:
      username: admin
    design:
      # 是否先顯示 Education，再顯示 Experience？false 表示 Experience 先
      is_education_first: false
      # Hugo 可解析的日期格式（展示在區塊標題旁），例如 "January 2006"
      date_format: "January 2006"
  - block: resume-skills
    content:
      title: "Skills & Hobbies"
      username: admin
    design:
      # 是否要顯示技能的百分比例條 (如果您在作者檔案中寫了“percent”欄位)
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: "Awards"
      username: admin
  - block: resume-languages
    content:
      title: "Languages"
      username: admin
---