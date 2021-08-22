---
title: "Query-Driven Video Event Processing for the Internet of Multimedia Things"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Piyush Yadav
- Dhaval Salwala
- Felipe Arruda Pontes
- Praneet Dhingra
- Edward Curry

# Author notes (optional)
author_notes:
-
- 

date: "2021-08-01T00:00:00Z"
doi: "10.14778/3476311.3476360"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the VLDB Endowment 2021*
publication_short: In *VLDB*

abstract: Advances in Deep Neural Network (DNN) techniques have revolutionized video analytics and unlocked the potential for querying and mining video event patterns. This paper details GNOSIS, an event processing platform to perform near-real-time video event detection in a distributed setting. GNOSIS follows a serverless approach where its component acts as independent microservices and can be deployed at multiple nodes. GNOSIS uses a declarative query-driven approach where users can write customize queries for spatiotemporal video event reasoning. The system converts the incoming video streams into a continuous evolving graph stream using machine learning (ML) and DNN models pipeline and applies graph matching for video event pattern detection. GNOSIS can perform both stateful and stateless video event matching. To improve Quality of Service (QoS), recent work in GNOSIS incorporates optimization techniques like adaptive scheduling, energy efficiency, and content-driven windows. This paper demonstrates the Occupational Health and Safety query use cases to show the GNOSIS efficacy.

# Summary. An optional shortened abstract.
summary: The paper demonstrates the Occupational Health and Safety use case queries. In future, multimodal data integration, edge-centric optimizations and developing more complex spatiotemporal operators are the key focus area of development in GNOSIS.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://vldb.org/pvldb/vol14/p2847-yadav.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=heH5Idec1eM'

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


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
