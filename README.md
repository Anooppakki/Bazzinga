These documents act as supplemental materials to the required deliverables officially submitted through the [Call for Code Global Challenge web site](https://compete.callforcode.skillsnetwork.site/competitions/2024-call-for-code-global-challenge), 

# Team Bazzinga

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Project development roadmap](#project-development-roadmap)


## Project summary

### The issue we are hoping to solve

In a fast paced city like New York, it becomes increasingly challenging for the community to keep up-to-date with flooding alerts and report incidents effectively. Existing solutions are ineffective and not
very user-friendly, which is an obstacle for both the residents and authorities. Our solution integrates seamlessly into daily routines, providing real-time data analysis and effortlessly notifies stormwater
incidents by utilizing IBM tools and algorithms.

### How our technology solution can help

As the problem with stormwater continues to grow, effective communication and public awareness becomes crucial to address the challenges people affected by floods face each year. The need for practive measures to prevent and mitigate these disasters is more crucial than ever.

### Our idea

Our approach integrates IBM tools and AI algorithms to provide real-time data and empower residents to report incidents seamlessly, offering speed, ease of use, and accessibility. The approach allows a user to effortlessly submit reports via photos, text, or voice, allowing our platform to pinpoint the issues’ location and notify relevant authorities swiftly. Our proposed solution hopefully will not only address stormwater challenges in NYC but also serve as a model for other regions facing similar issues, ensuring a more resilient and sustainable urban environment worldwide. Our solution at its core is a sophisticated monitoring system, akin to navigation systems in mapping apps, it collect data from various sources like weather forecasts, interactive mapping, and reports from the community. Using advanced algorithms, we then analyze this data to identify areas prone to flooding and other stormwater issues in real time.

Communities can also help enhance the decision-making process by actively participating in and providing valuable insights and feedback to authorities, ensuring that decisions are informed by local knowledge and needs. To help authorities make more informed decisions, our solution focuses on providing real-time data and managing data through robust data management protocols including pattern and trend identification, organizing and analyzing all while empowering communities through user-friendly tools. By streamlining the reporting process and offering accessible resources, we aim to bridge the gap between complex stormwater information and community understanding, ensuring that residents can also easily digest and engage with data. To make these solutions available and encourage usage, we prioritize accessibility and ease of use. By offering a user-friendly interface, real-time updates, and interactive features such as mapping flooded areas, we aim to engage residents and incentivize their participation in reporting and addressing stormwater issues.

## Technology implementation

### IBM watsonx product(s) used

**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - Snap Boosting Machine Classifier Model trained to predict floods

- [watsonx Assistant](https://cloud.ibm.com/catalog/services/watsonx-assistant) - Used to classify sentiment and urgency of a reported issue, Summarize Weather and Commute Data



### Other IBM technology used

**Additional IBM AI services (Remove any that you did not use)**

- [Watson Speech to Text]([https://cloud.ibm.com/catalog/services/watsonx-assistant](https://www.ibm.com/products/speech-to-text)) - Used to transcribe reported issues

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![AidNYC]([https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png](https://raw.githubusercontent.com/Anooppakki/Bazzinga/refs/heads/main/Architecture%20Diagram.png))

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

[![Watch the video](https://i9.ytimg.com/vi_webp/xv7gweFMBUo/mq2.webp?sqp=CLDjzLcG-oaymwEmCMACELQB8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGGUgUihDMA8=&rs=AOn4CLC_ISOICYSCVJOJFODjSSfK1Nh9SA)](https://youtu.be/xv7gweFMBUo)

- [Prototype](https://www.figma.com/proto/0mPEryrRzlQRXEQy4doGze/Bazzinga-%3A%3A-AI-Innovation-Challenge?page-id=0%3A1&node-id=653-1628&node-type=frame&viewport=-1089%2C-1104%2C0.06&t=l3frIhJOTLAdw0Un-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=653%3A1628)
