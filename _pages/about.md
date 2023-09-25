---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I received my master's degree in Electrical and Computer Engineering from the College of Engineering, [Boston University](https://www.bu.edu/eng/). I was very fortunate to be supervised by [Prof. Prakash Ishwar](https://www.bu.edu/eng/profile/prakash-ishwar/) as a teaching assistant in his _Introduction to Machine Learning_ course. After graduation, I worked as a research assistant in the [Bio-Imaging & Informatics Lab](https://sites.bu.edu/bil/) under the guidance of [Prof. Bang-Bon Koo](https://www.bumc.bu.edu/camed/profile/bang-bon-koo/). My research interest includes Machine Learning, Data Analysis and Human-computer Interaction.

Before joining Boston University, I obtained my B.S. degree in Computer Technology and Application at Macau University of Science and Technology (MUST). I graduated with first-class honors and my thesis was awarded as one of the best in the college. During this period, I was honored to be mentored by [Prof. Subrota Kumar Mondal](https://www.must.edu.mo/scse/staff/subrota) and collaborate with [Prof. Hongning Dai](https://www.comp.hkbu.edu.hk/~henrydai/) to conduct research in the fields of serverless computing and container technology.

I am passionate about exploring more efficient feature selection algorithms and trustworthy machine learning models to help people mine valuable information from large and complex data sets. My research motivations are all human-centered, and I hope to use artificial intelligence to make people better perceive and utilize data. My ultimate goal is that everyone can derive meaningful information from large amounts of data through simple interaction with a computer.

You can find my CV here: [CV](../assets/TianTan.pdf).

Publications
======
* Subrota Kumar Mondal\*, __Tian Tan\*__, Sadia Khanam, Keshav Kumar, Hussain Mohammed Dipu Kabir, Kan Ni.  <br>
  Security Quantification of Container-Technology-Driven E-Government Systems  <br>
  Electronics, 2023. [Paper](https://www.mdpi.com/2079-9292/12/5/1238) <br>
* Subrota Kumar Mondal, Rui Pan, H M Dipu Kabir, __Tan Tian__, Hong-Ning Dai. <br>
  Kubernetes in IT Administration and Serverless Computing: An empirical study and research challenges   
  The Journal of Supercomputing, 2022. [Paper](https://link.springer.com/article/10.1007/s11227-021-03982-3)
* __Tian Tan__, Xuepin Ma, Jun Liu, Zuren Li  
  Photocatalytic Degradation of Residual Orthene in Vegetables by Nano-TiO2  
  China Science & Technology Education, 2017.   
* __Tian Tan__  
  An Analysis on Canceling the Division of Liberal Arts and Sciences in the College Entrance Examination  
  Culture And History Vision (Theory), 2016.  
* __Tian Tan__, Ruiming Zhou  
  Thoughts on Reform of China's Personal Income Tax System  
  Modern SOE Research, 2016.  
  
_**Note**: * above denotes equal contribution_

<!--
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
-->
