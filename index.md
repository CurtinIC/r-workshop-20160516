---
layout: default
---
{% assign email_recipient = 'curtinic@curtin.edu.au' %}
{% assign email_subject = 'RSVP for R workshop' %}
{% assign email_body = 'I am going to attend the workshop' %}
{% capture mailto %}
mailto:{{email_recipient}}?subject={{email_subject|uri_escape}}&body={{email_body|uri_escape}}
{% endcapture %}

**When:** 16 May 2016, 10am-12pm

**Where:** [Cisco IoE Innovation Centre](http://research.curtin.edu.au/about/institutes-centres/cisco-internet-of-everything-innovation-centre/), building 216, level 2

**Please RSVP by 13 May sending an email to [{{email_recipient}}]({{mailto}})**

**Places are limited**

R is a high level programming language for statistical analysis and data visualisation. It is an open source and well supported language that provides many packages for a wide variety of statistical and graphical techniques.

If you would like to know more about R and how to get started come along to the work-along **Introduction to R** hosted by the [Curtin Institute for Computation](http://computation.curtin.edu.au).

The session is aimed at beginners and will show you how to access and work with your data, how to load packages and where to find help.

This introduction will use RStudio, an implemented development environment for R, and we ask you to follow the instructions below to install R and RStudio before the session. If you need help with the installation please arrive 15 minutes early so we can help you.

This workshop is available free of charge to Curtin students and staff.

<a href="#course-outline" id="course-outline" class="anchor"><span class="octicon octicon-link" aria-hidden="true"></span></a>Course Outline
============================================================================================================================================

1.  Overview of R and RStudio

2.  Importing your data into R

3.  Manipulating your data

4.  Visualising your data

<a href="#install-instructions" id="install-instructions" class="anchor"><span class="octicon octicon-link" aria-hidden="true"></span></a>Install instructions
==============================================================================================================================================================

R is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. To interact with R, we use RStudio.

<a href="#windows" id="windows" class="anchor"><span class="octicon octicon-link" aria-hidden="true"></span></a>Windows
-----------------------------------------------------------------------------------------------------------------------

[Video Tutorial](https://www.youtube.com/watch?v=q0PjTAylwoU) Install R by downloading and running [this .exe file](http://cran.r-project.org/bin/windows/base/release.htm) from [CRAN](http://cran.r-project.org/index.html). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).

<a href="#mac-os-x" id="mac-os-x" class="anchor"><span class="octicon octicon-link" aria-hidden="true"></span></a>Mac OS X
--------------------------------------------------------------------------------------------------------------------------

[Video Tutorial](https://www.youtube.com/watch?v=5-ly3kyxwEg) Install R by downloading and running [this .pkg file](http://cran.r-project.org/bin/macosx/R-latest.pkg) from [CRAN](http://cran.r-project.org/index.html). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).

<a href="#linux" id="linux" class="anchor"><span class="octicon octicon-link" aria-hidden="true"></span></a>Linux
-----------------------------------------------------------------------------------------------------------------

You can download the binary files for your distribution from [CRAN](http://cran.r-project.org/index.html). Or you can use your package manager (e.g. for Debian/Ubuntu run sudo apt-get install r-base and for Fedora run sudo yum install R). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop).
