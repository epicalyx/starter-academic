---
title: "Risk Forecasting from Earnings Calls Acoustics and Network Correlations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ramit Sawhney
- Piyush Khanna
- Arshiya Aggarwal 
- Puneet Mathur
- admin
- Rajiv Ratn Shah

# Author notes (optional)
author_notes:
- "Equal contribution"
#- "Equal contribution"

date: "2020-10-25"
doi: "10.21437/Interspeech.2020-2649"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proc. Interspeech 2020*
#publication_short: In *ICW*

abstract: Stock volatility is a degree of deviations from expected returns, and thus, estimates risk, which is crucial for investment decision making. Volatility forecasting is complex given the stochastic nature of market microstructure, where we use frenzied data over various modalities to make temporally dependent forecasts. Transcripts of earnings calls of companies are well studied for risk modeling as they offer unique investment insight into stock performance. Anecdotal evidence shows company CEO’s vocal cues could be indicative of the stock performance. The recently developing body of work on analyzing earnings calls treat stocks as independent of each other, thus not using rich relations between stocks. To this end, we introduce the first neural model that employs cross inter-modal attention for deep verbal-vocal coherence and accounts for stock interdependence through multi-layer network embeddings. We show that our approach outperforms state-of-the-art methods by augmenting speech features with correlations from text and stock network modalities. Lastly, we analyse the components and financial implications of our method through an ablation and case study.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://isca-speech.org/archive/Interspeech_2020/pdfs/2649.pdf"
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
 # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  #focal_point: ""
  #preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
