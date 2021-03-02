# Site
repository: Git repository where your resume will be hosted, only required if you are hosting on GitHub (eg. sproogen/modern-resume-theme)
# favicon: Directory of your favicon (eg. images/favicon.ico)(optional)

# Content configuration version
version: 2

# Personal info
name: 고동우
title: 상명대학교 게임학과 3학년 재학
email: ehddn2202@gmail.com
# email_title: Email (Email title override)
phone: 010-7231-9001
# phone_title: Phone (Phone title override)
website: https://blog.naver.com/ehddn2202
# website_title: Web (Website title override)

# Dark Mode (true/false/never)
darkmode: true

# Social links
twitter_username: KDW
github_username:  https://github.com/201710890Ko
stackoverflow_username: ""
dribbble_username: 
facebook_username: 고동우
flickr_username: 
instagram_username: 
linkedin_username: 
xing_username: 
pinterest_username: 
youtube_username: 
googleplus_username: 
orcid_username: 0000-0000-0000-0000

# Additional icon links
additional_links:
- title: Link name
  icon: Font Awesome brand icon name (eg. fab fa-twitter) (https://fontawesome.com/icons?d=gallery&s=brands&m=free)
  url: Link url (eg. https://google.com)
# - title: another link
#   icon: font awesome brand icon name (eg. fab fa-twitter) (https://fontawesome.com/icons?d=gallery&s=brands&m=free)
#   url: Link url (eg. https://google.com)

# Google Analytics and Tag Manager
# Using more than one of these may cause issues with reporting
# gtm: "GTM-0000000"
# gtag: "UA-00000000-0"
# google_analytics: "UA-00000000-0"

# About Section
# about_title: About Me (Use this to override about section title)
about_profile_image: C:\Users\ehddn\OneDrive\바탕 화면\내사진.jpg
about_content: | # this will include new lines to allow paragraphs
  //Write an awesome description about yourself here, this supports markdown, so you can add [links](http://foobar.com) and highlight things <mark>like this</mark>.//

  You can even add paragraphs by using empty lines like this and add anything else [markdown](https://www.markdownguide.org/getting-started#what-is-markdown) supports such as
    - Lists
    - Tables
    - <a href="google.com">Links</a>
    - Images ![alt text](/images/landscape-trees.jpg "Trees")

content:
  - title: Projects # Title for the section
    layout: list # Type of content section (list/text)
    content:
      - layout: left
        title: Project name
        link: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
        link_text: Link Text
        additional_links:
          - title:  Github page for project (eg. sproogen/modern-resume-theme)
            icon: fab fa-github
            url: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
          - title:  Github page for project (eg. sproogen/modern-resume-theme)
            icon: fab fa-github
            url: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
        quote: >
          Short overview of the project (optional)
        description: | # this will include new lines to allow paragraphs
          Description about the work on/with the project
  - title: Experience
    layout: list
    content:
      - layout: right
        title: 상명대학교 게임학과
        sub_title: 마음만은 새내기 17학번
        caption: 재학기간 (eg. March 2017 - present)
        link: https://www.smu.ac.kr/ko/index.do
        quote: >
          Short description of the company (optional)
        description: | # this will include new lines to allow paragraphs
          Description of role
  - title: Education
    layout: list
    content:
      - layout: top-right
        title: Institution name
        sub_title: Qualifications (eg. BA Performing Arts)
        caption: Date Range (eg. 2016 - 2019)
        quote: >
          Short institution or course description (optional)
        description: | # this will include new lines to allow paragraphs
          Description of qualification
  - title: A Little More About Me
    layout: text
    content: | # this will include new lines to allow paragraphs
      This is where you can write a little more about yourself. You could title this section **Interests** and include some of your other interests.

      Or you could title it **Skills** and write a bit more about things that make you more desirable, like *leadership* or *teamwork*

# Footer
footer_show_references: true
# references_title: References on request (Override references text)

# Build settings
# theme: modern-resume-theme (Use this is you are hosting your resume yourself)
# remote_theme: sproogen/modern-resume-theme (Use this if you are hosting your resume on GitHub)

sass:
  sass_dir: _sass
  style: compressed

plugins:
 - jekyll-seo-tag

exclude : [
  "Gemfile",
  "Gemfile.lock",
  "node_modules",
  "vendor/bundle/",
  "vendor/cache/",
  "vendor/gems/",
  "vendor/ruby/",
  "lib/",
  "scripts/",
  "docker-compose.yml",
  ]
