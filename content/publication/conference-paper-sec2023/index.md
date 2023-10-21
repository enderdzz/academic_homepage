---
title: 'Differential Testing of Cross Deep Learning Framework APIs: Revealing Inconsistencies and Vulnerabilities'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Guozhu Meng, Kai Chen, Tong Liu, Lu Xiang, and Chunyang Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 32nd USENIX Security Symposium
publication_short: In USENIX Security 23

abstract: With the increasing adoption of deep learning (DL) in various applications, developers often reuse models by, for example, performing model conversion among frameworks to raise productivity. However, security bugs in model conversion may make models behave differently across DL frameworks, and cause unpredictable errors. Prior studies primarily focus on the security of individual DL frameworks, but few of them can cope with the inconsistencies and security bugs during cross-framework conversion. Furthermore, the impact of these issues on DL applications remains largely unexplored. To this end, we propose TENSORSCOPE, a novel approach to test cross-framework APIs for security bugs. It takes as input a number of counterpart APIs that are supposed to be equivalent in functionality, then performs differential testing to identify the inconsistencies. We design novel strategies to boost testing efficiency, including 1) joint constraint analysis to raise the quality of test cases, and 2) error-guided test case fixing to refine the constraints for input. TENSORSCOPE is extensively evaluated on 1,658 APIs of six popular DL frameworks. The results show that TENSORSCOPE is more effective than FreeFuzz and DocTer by raising 28.7% and 24.3% code coverage, respectively. We find 257 bugs including 230 new bugs, and receive 8 CVEs and $1,100+ bounty with developers' acknowledgment. Most importantly, we make the first attempt to exploit these inconsistencies to make the accuracy of three models reduced by at most 3.5%.

# Summary. An optional shortened abstract.
summary: 

tags: [Deep learning framework, Tensor, Constraint, Differential testing]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.usenix.org/system/files/usenixsecurity23-deng-zizhuang.pdf'
url_code: 'https://github.com/tensorscopepro/Tensorscope'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
