---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Engineer
    company: Data Science Institute, NUI Galway
    company_url: 'https://datascienceinstitute.ie/'
    company_logo: dsi
    location: Galway, Ireland
    date_start: '2019-10-01'
    date_end: ''
    description: |2-
      * Designed and implemented Computer Vision Pipeline for Gnosis MEP engine in Python, Redis Streams, Docker.
      * Assisted in scientific research for building Complex Event Patterns (CEP) in Data Streams. Worked on individual problem sets.
      * Worked alongside Research Fellows, Postdoctoral Researchers and PhD students on design challenges and refining CEP work problems.
      * Collected and studied large scale video datasets. Performed manipulating, processing, and extracting value from these datasets. Ran Image Processing models to analyse the accuracy and prepared ground data - TensorFlow/Keras.
      * Adopted efficient microservices architecture to execute ML pipeline on the streaming multi-modal data.
      * Designed benchmarking platform for a CEP Pipeline that includes Object Detection, Object Tracking and Annotation via Jaegar/Python.
      * Modelled data obtained through the CEP pipeline into a Knowledge Graph through spatiotemporal relationships. 
      * Designed a matching engine for video querying that uses an openCypher query to explore Knowledge Graphs.
      * Paper on Query Driven Urban Accessibility using complex event processing accepted in ACM Multimedia 2021.
      * Assistant Chair and co-organiser for the 27th AIAI Irish Conference on Artificial Intelligence and Cognitive Science, Galway, Ireland, December 5-6, 2019. 

      Technologies: Python3, TensorFlow, Pytorch, Docker, RedisGraph, RedisStreams, DNN models.
                
  - title: Technical Lead
    company: TCS - Eurex Advanced Risk Protection (ARP) – Deutsche Börse Group, Frankfrut.
    company_url: 'https://www.tcs.com'
    company_logo: tcs
    location: Pune, India
    date_start: '2015-05-01'
    date_end: '2018-08-10'
    description: |2-
      * Member of the Design Team that created technology stack for a risk interface application that monitors risk exposure in real-time for Eurex Exchange T7.
      * Led a team of associates to critical deliveries. Leveraged strong expertise in solving and identifying bugs while working with production support.
      * Worked closely with Business Analysts in mapping the business requirement with the Physical Data Model.
      * Developed AMQP interfaces to different cross-platform business entities and facilitated data exchange using Google Protocol Buffer (GPB).
      * Architect a state-of-the-art Cash Payment System (CPS) for Eurex Trading Platform T7. It offers a high degree of flexibility in terms of processing trades, payment locations, message formats and cross-currencies transactions. Created chained transaction handling using Spring Transaction Management.
      * Developed SWIFT message simulator in Spring Boot that performs load testing on thousands of concurrent payment instructions.
    
      Technologies: Java8, EJB3, Python3, Spring Boot, Hibernate, Apache Qpid, Jboss7, PostgreSQL, Git, Maven, Protocol Buffers.

  - title: Software Developer
    company: TCS - ICG Credit Approval System – Citigroup Corporation, NJ USA.
    company_url: 'https://www.tcs.com'
    company_logo: tcs
    location: Pune, India
    date_start: '2013-03-01'
    date_end: '2015-05-01'
    description: |2-
      * Gained functional knowledge while working with legal, compliance and lending team on credit approval workflows and lending practices.
      * Optimized Citigroup’s Risk Management Business workflow using TIBCO iProcess and Spring Scheduler.
      * Enhanced UI response rate and operational efficiency of the platform by eliminating legacy codebase.
      * Working on Design Patterns, Unit Testing, Refactoring, Code structuring.
    
      Technologies: Java1.6, Adobe Flex, Spring, Hibernate, IBM Websphere, Oracle 10g, Git, Maven, HP Load Runner.

---
