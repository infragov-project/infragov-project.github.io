---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Do Experts Agree About Smelly Infrastructure?"
authors: [Sogol Masoumzadeh, nuno-saavedra, Rungroj Maipradit, Lili Wei, jff , Dániel Varró, Shane McIntosh]
date: 2025-03-19
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-03-18T22:42:47Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "In *IEEE Transactions on Software Engineering* (To appear, 2025)"
publication_short: "In *TSE 2025*"
publication_ranking: "<b>Q1 journal</b>"
# Awards
#award_text: "**ACM SIGSOFT Distinguished Paper award**"
#award_text: "**Awarded:** _Artifact Evaluation Award (Available, Reusable)_. **Most cited paper from ICSE 2020 ([Google Scholar Metrics](https://scholar.google.com/citations?hl=en&view_op=list_hcore&venue=vtDF2hFAQ-cJ.2023&vq=eng_softwaresystems))**"

abstract: "
Code smells are anti-patterns that violate code understandability, re-usability, changeability, and maintainability. It is important to identify code smells and locate them in the code. For this purpose, automated detection of code smells is a sought-after feature for development tools; however, the design and evaluation of such tools depends on the quality of oracle datasets. The typical approach for creating an oracle dataset involves multiple developers independently inspecting and annotating code examples for their existing code smells. Since multiple inspectors cast votes about each code example, it is possible for the inspectors to disagree about the presence of smells. Such disagreements introduce ambiguity into how smells should be interpreted. Prior work has studied developer perceptions of code smells in traditional source code; however, smells in Infrastructure-as-Code (IaC) have not been investigated. To understand the real-world impact of disagreements among developers and their perceptions of IaC code smells, we conduct an empirical study on the oracle dataset of GLITCH—a state-of-the-art detection tool for security code smells in IaC. We analyze GLITCH's oracle dataset for code smell issues, their types, and individual annotations of the inspectors. Furthermore, we investigate possible confounding factors associated with the incidences of developer misaligned perceptions of IaC code smells. Finally, we triangulate developer perceptions of code smells in traditional source code with our results on IaC. Our study reveals that unlike developer perceptions of smells in traditional source code, their perceptions of smells in IaC are more substantially impacted by subjective interpretation of smell types and their co-occurrence relationships. For instance, the interpretation of admins by default, empty passwords, and hard-coded secrets varies considerably among raters and are more susceptible to misidentification than other IaC code smells. Consequently, the manual identification of IaC code smells involves annotation disagreements among developers—46.3% of studied IaC code smell incidences have at least one dissenting vote among three inspectors. Meanwhile, only 1.6% of code smell incidences in traditional source code are affected by inspector bias stemming from these disagreements. Hence, relying solely on the majority voting, would not fully represent the breadth of interpretation of the IaC under scrutiny."
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: publication/2025/TSE/tse2025_masoumzadeh.pdf
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
aliases:
    - /publications/2025/TSE
    - /publication/2025/tse
---
