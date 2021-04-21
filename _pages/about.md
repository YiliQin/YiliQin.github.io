---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received the M.S. degree from the University of Tsukuba in 2019. Now, I am a Ph.D. student at the University of Tsukuba and research assistant at [CNRS-AIST Joint Robotics Laboratory (JRL)](https://unit.aist.go.jp/jrl-2/index_en.html) in AIST, Japan.
My research interests include whole-body motion planning and control for humanoid robots, robotic manipulation for long deformable objects like cables, belts and so on.
* Education
    * Ph.D. student at Intelligent and Mechanical Interaction System, University of Tsukuba, Japan (2019.4~2022.3 Expected)
    * M.S. at Intelligent and Mechanical Interaction System, University of Tsukuba, Japan (2017.4~2019.3)
    * B.S. at Northeastern University, China (2006.9~2010.6)
* Work Experience
    * Student research assistant (2018.4~Present) 
        * National Institute of Advanced Industrial Science and Technology (AIST), Japan
        * Research about deofrmation object manipulation by humanoid robot 
    * FPGA engineer (2010~2015)
        * Beijing, China
        * R&D for communication equipments
     
Member of team Janus for ANA AVATAR XPRIZE
======
As one of the [38 teams](https://www.xprize.org/prizes/avatar/articles/38-semifinalist-teams-from-16-countries-aim-to-create-an-avatar-system) from 16 countries all around the world, team [Janus](https://unit.aist.go.jp/jrl-2/en/projects/janus/team-janus.html) passed the semifinalists selection for the [ANA AVATAR XPRIZE](https://www.xprize.org/home) Robot Challenge. The finals will be held in the United States on Dec. 2021. In the team Janus, my work are mainly about robot motion generation and software integration.

![ana_avatar](/images/ana-avatar.png)

Publications(International)
======

<ul>
{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}
</ul>
     

Publications/Talks(Domestic)
======
* Take a Long Deformable Belt out of a Bobbin by Humanoid Robot, Y. Qin, A. Escande, A. Tanguy, E. Yoshida, ロボティクス・メカトロニクス講演会(ROBOMECH), 2020
* Cable Installation by a Humanoid Integrating Dual-arm Manipulation and Walking, Y. Qin, A. Escande, E. Yoshida, 平成30年度先端ロボット工学合同ワークショップ, 2018
* Dual-arm Cable Manipulation by Whole-body Control of a Humanoid Robot, Y. Qin, A. Escande, E. Yoshida, ロボティクス・メカトロニクス講演会(ROBOMECH), 2018

<!--Getting started-->
<!--======-->
<!--1. Register a GitHub account if you don't have one and confirm your e-mail (required!)-->
<!--1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. -->
<!--1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.-->
<!--1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")-->
<!--1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  -->
<!--1. Check status by going to the repository settings, in the "GitHub pages" section-->

<!--Site-wide configuration-->
<!---------->
<!--The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. -->

<!--Create content & metadata-->
<!---------->
<!--For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).-->

<!--**Markdown generator**-->

<!--I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator-->
<!--) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.-->

<!--How to edit your site's GitHub repository-->
<!---------->
<!--Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. -->

<!--Example: editing a markdown file for a talk-->
<!--![Editing a markdown file for a talk](/images/editing-talk.png)-->

<!--For more info-->
<!---------->
<!--More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.-->
