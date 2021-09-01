---
title: "Knowledge Graph Driven Approach to Represent Video
Streams for Spatiotemporal Event Pattern Matching in Complex Event Processing System"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Piyush Yadav
- Dhaval Salwala
- Edward Curry

# Author notes (optional)
author_notes:
- 
- 

date: "2020-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Graph Computing*
publication_short: In *IEEE*

abstract: Complex Event Processing (CEP) systems is an event pro- cessing paradigm to perform real-time analytics over streaming data and match high-level event patterns. Presently, the CEP system is limited to process structured data stream. Video streams are complicated due to their unstructured data model and limit CEP systems to perform match- ing over them. This work introduces a graph-based structure for contin- uous evolving video streams, which enables the CEP system to query complex video event patterns. We propose the Video Event Knowledge Graph (VEKG), a graph driven representation of video data. VEKG models video objects as nodes and their relationship interaction as edges over time and space. It creates a semantic knowledge representation of video data derived from the detection of high-level semantic concepts from the video using an ensemble of deep learning models. A CEP based state optimization - VEKG-Time Aggregated Graph (VEKG-TAG) is proposed over VEKG representation for faster event detection. VEKG- TAG is a spatiotemporal graph aggregation method that provides a sum- marized view of the VEKG graph over a given time length. We defined a set of nine event pattern rules for two domains (Activity Recognition and Surveillance), which act as a query and applied over VEKG graphs to discover complex event patterns. To show the efficacy of our approach, we performed extensive experiments over 801 video clips across 10 datasets. The proposed VEKG approach was compared with other state-of-the-art methods and was able to detect complex event patterns over videos with F-Score ranging from 0.44 to 0.90. In the given experiments, the optimized VEKG-TAG was able to reduce 99% and 93% of VEKG nodes and edges, respectively, with 5.19X faster search time, achieving sub-second median latency of 4-20 milliseconds.

# Summary. An optional shortened abstract.
summary: The work proposes a semantic representation technique to detect event patterns from unstructured video in CEP systems. We present the Video Event Knowledge Graph (VEKG), a graph driven approach to represent video streams and enables the CEP system to detect visual patterns.

tags: []

# Display this page in the Featured widget?
featured: false

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
