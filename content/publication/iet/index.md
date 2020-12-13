---
title: "Inferring depth contours from sidescan sonar using convolutional neural nets"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Nils Bore
- John Folkesson

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"


date: "2020-02"
doi: "10.1049/iet-rsn.2019.0428"


# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-06"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IET Radar, Sonar and Navigation*
publication_short: In *IET Radar, Sonar Navig.*

Abstract: Sidescan sonar images are 2D representations of the seabed. The pixel location encodes distance from the sonar and along track coordinate. Thus one dimension is lacking for generating bathymetric maps from sidescan. The intensities of the return signals do, however, contain some information about this missing dimension. Just as shading gives clues to depth in camera images, these intensities can be used to estimate bathymetric profiles. The authors investigate the feasibility of using data driven methods to do this estimation. They include quantitative evaluations of two pixel-to-pixel convolutional neural networks trained as standard regression networks and using conditional generative adversarial network loss functions. Some interesting conclusions are presented as to when to use each training method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin # condimentum.

tags: []

# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'SSS waterfall image'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
