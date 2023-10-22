---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Hello World!
Welcome to my personal webage. My name is Stefano Genetti. I'm currently a student at the University of Trento, enrolled in the Master's degree in Computer Science. My journey into the world of computer science began at a young age when my father introduced me to a computer, igniting a lifelong passion for this captivating field. I find various areas of computer science intriguing, from data science and artificial intelligence to networking. My curiosity spans across diverse realms of computer science, encompassing topics from data science and artificial intelligence to distributed systems. Presently, I invest most of my time in the following activities:
- Hypergraph Summarization Research: I'm contributing to a research project under the supervision of Professor Alberto Montresor and PhD student Francesco Lotito. With our work, we are introducing the first algorithmic solution to the novel problem of Hypergraph Summarization. Our aim is to publish a scientific paper based on our findings.
- E-Agle Trento Racing team: I'm excited to be part of the University of Trento's Formula Student Team. Here, my primary focus is on developing software solutions for the creation of a perceptron system for our autonomous vehicle competing in Formula Driverless competitions. Specifically, we're working on a visual SLAM solution that combines the ORB-SLAM3 algorithm with YOLO. This system allows the vehicle to localize itself on the track while identifying cones and their coordinates to construct a map of the circuit.
- English Certification: I'm preparing to achieve a Cambridge C1 Advanced English certification in December in order to improve and certify my language skills.
- Internship Search: I'm actively seeking an internship opportunity to conclude my university career. My aspiration is to attend an internship program abroad. This would be an incredible opportunity to discover new things, face new problems, broaden my horizons, connect with professionals in the field, discover new cultures. Furthermore, this would allow me to better understand what I want to pursue in my future after university.
- University Courses: At the university, I'm currently enrolled in the "Bio-Inspired Artificial Intelligence" course, exploring evolutionary algorithms and swarm intelligence. Additionally, I'm delving into "Low-Power Wireless Networking for the Internet of Things," which has introduced me to the exciting world of low-power wireless communication technologies. Furthermore, I'm enhancing my writing skills through the "Technical Writing" course, which also aligns with my preparation for the C1 certification.
Beyond my academic commitments, I enjoy engaging in various projects. In the recent years, the university occupies most of my time, as a consequence, my main extracurricular activities revolve around providing technical support to individuals, such as hardware repairs and consultancy. Living in a small village, I'm often the go-to person for technical assistance. I also have a passion for developing software solutions, including websites and management software for small clients.
Apart from my computer science interests, I pursue other hobbies. Recently, I joined an amateur volleyball team of wonderful people called "Diaspeck Volley Bolghera" where I play as a libero.

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
