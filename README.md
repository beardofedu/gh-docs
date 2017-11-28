# How GitHub Uses GitHub - Writing documentation for your projects

## Introduction
- Matt Desmond, Trainer at GitHub, previous experience as a technical writer
- Eric Holscher, Founder Read|Write the Docs

## Why Document

- Ever been frustrated with trying to use a new tool or mess with new technology, don't let your project be the next end-user frustration. 
- Personally, if I begin using a new application or framework and I can't find documentation to either get started or utilize the functionality, I move on to other options.
- Hard to collaborate on a project if you don't know what it does / how it can help you, leading to minimal interest in helping a project grow and evolve
- Q for Eric, as the founder of Read | Write the Docs, what made you so passionate about documentation for projects? 

## Why use GitHub for Documentation

- I came from a world where I had 6 versions of the same Word file with -FINAL, -FINAL-For-Real, -FINAL-DATE, and FINAL-DATE-NO-REALLY for almost every project
- Sharing the documentation process with project maintainers and potentially project contributors

## Looking at Documentation

- Read the Docs repo: https://github.com/rtfd/readthedocs.org
- Read the Docs documentation: https://docs.readthedocs.io/en/latest/getting_started.html

- Q for Eric during webcast: Being involved with Read and Write the Docs, I would imagine you have seen your fair share of documentation, what do you think are your top 3 dos and 3 donts when it comes to documents?
- "perfect segue into getting started"

## Getting Started with Documentation

- Installation instructions
- Open source repository? Include how to contribute instructions
- Focus on consistent phrasing and making things easy to find

### Consider the Audience
- Keep content for specific end-users grouped
  - Your documentation should be segmented and easily referenced regardless of what the reader is looking for.
    - New to application or language? Getting Started Guide should be easy to find.
    - Interacting with your API? Have a dedicated section for using your API that isn't nestled inside more typical end user interactions. 
    - Let's look at the React documentation: https://reactjs.org/docs/hello-world.html
      - 1. the Docs link at the top of the page brings you to the Hello World exercise (even though it isn't the first topic)
      - 2. The content is segmented into different sections: Quick Start / New comers | Advanced Guides | a Reference section | and a Contributing Guide ... they do have a FAQ but I won't take too many points off for that :joy:

- Don't assume that your audience comes with any knowledge
  - Treat all of your reader's equally and don't expect someone using your project to have a wealth of knowledge about what your project does or how to use it. 
  - Don't use acronyms without spelling them out first
    - In topic driven content, it might be helpful to spell out an acronym the first time it is used on every topic (your reader might not be reading every topic, just trying to answer a specific question)
  - Docs vs Tutorials
    - Documentation instructs someone how to use your project, a tutorial can be used to guide a reader through a typical workflow or use case for your project

### Know what / when to document
- Not _everything_ needs to be documented
  - Examples of what not to document
    - Descriptions of a UI functions as standalone content
    - FAQs (https://content-guide.18f.gov/structure-the-content/#dont-use-faqs)
  - Examples of what to document
    - Typical workflows (how to install, normal operations, etc)

- Understand why you are documenting something  
  - Creating content just to create content probably isn't helpful for your reader. Identify what problem the documentation is going to address. 

## Publishing Documentation

- GitHub Pages 
- Read the Docs 
  - Eric: if you could provide a brief description of the process of getting documentation published on the RtDs platform here that would be awesome

## How to get community help with documentation?

- Not every open source contributor is ready to provide contributions to the code of your application. 
   - Identify documentation requirements and create issues with "beginner friendly" or "good first issue" labels
     - Q for Eric during the webcast: How many issues with a "good first issue" label do you think gets resolved by a new contributor to the Read the Docs repository?
     - Q for Eric during the webcast: How do you encourage newcomers to the Read the Docs repository to contribute?

## Where to go now

- Write the Docs Slack: http://www.writethedocs.org/slack/
- Write the Docs Getting Started guide: http://www.writethedocs.org/guide/writing/beginners-guide-to-docs/
