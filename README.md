# Getting Started: Laboratory Assignment #0

Welcome to CIT 384/L: Web Development and Hosting



# Overview:

### From the CIT160 Syllabus:

Today, very few have not heard of or have not used "The Internet." For the vast majority of users, they access network-based applications via the web. I.e., these users utilize a web-browser to access these applications. Some common examples include: social networks, communication tools, search tools, commerce sites, information sites, etc.

### From the CIT384 Syllabus:	

In this course, we will learn the fundementals of developing a web site and web applications. This will provide us with a better understanding of the needs of our users and of our software developers that we serve. We then turn our attention to developing the necesary tool set to configure, to deploy, and to maintain IT systems that hosts such web applications. We also examine other tools and techniques to ensure seemless and continous delivery of the associated services to users. Knowledge and expertise in both pieces will prepare us to be effective members of a [DevOps](https://en.wikipedia.org/wiki/DevOps) team.

While the best-practices and the techology tool-sets _de jour_ are constantly changing and evolving (and you will be expected to learn these new practices and technologies, again, again, and again _throughout_ your career), there are some widely accepted concepts and universally adopted technologies. 

As such, this class is designed to reinforce your knowledge of these prevalent technologies, but with an emphais on the core concepts and best-practices:

  - effective team-based communication --- using https://www.slack.com
  - source and version control --- using https://git-scm.com/docs/git-stash
  - container, containerization --- using https://docker.com
  - automation, automation, automation --- it's a mind set, not a tool!


# Required Background Knowledge:
For CIT384, we presume that each student already posses certain knowlege of various technologies, or has the ability to learn these technologies on their own. This information includes:

  - the bash shell environment: as introducted in CIT160
  - ssh, scp, and other file transfer protocols: as introducted in CIT160 and reinforced in other CIT cources.
  - basic programming: as introduced in COMP110, CIT160, CIT260, etc., etc., 
  - elememtry knowledge of docker: as introduced in CIT160

The writeup of this assignment presume this knowledge. If you don't know how to perform a particular step:
  - ask!
  - ask your teammates!
  - ask in slack!
  - the Professors look up to those that _work towards success and not afraid to ask for help along the way_


# Assignment Summary:
In this assignment, you will taking steps to setup your personal computer and various campus-provides resources. You will also need to establish accounts with various online services. These resources and services will be used throughout this course. Moreover, the professors will take every effort to utilize such services throughout the course. 

For example, 
   * all class material will be delivered via git using a github repository.
   * all class assignments will be submited via GitHub Classroom
   * all deployed software may be purged at anytime
      - the only thing that is assured to be stable is your github repository
      - this will force you to automate the deployment of all your deliverables


# Assignment #0
Complete the following steps, and submit your <user-id>.env via GitHub Classroom.


## Steps:
  1. Read these instructions in total before you begin!

  1. Send an email to my "steven.fitzgerald@csun.edu" account to provide me with your @my.csun.edu address.

  1. On your personal computer, create a working directory for this class
    - the canonical name for this directory is: \~/classes/cit384
    - as such, all class related documents will refer to this locations

  1. Validate that your campus resources are correclty configured!
    1. Log into the following shell servers using your campus user-id, and create a working directory for this class.
       ```
       - ssh.csun.edu 
       - ssh.sandbox.csun.edu
       - k200.ecs.csun.edu
       ```
       This step will validated that your campus account is configured correctly. If you run into any problems, contact the heldesk@csun.edu immediately so that any problems can be fixed quickly.

       If you don't know your user id, you can look it up via the [Forgot User ID web page](https://cmsweb.csun.edu/psc/CNRPRD/EMPLOYEE/SA/c/NR_SSS_COMMON_MENU.NR_FORGOTUID_CMP.GBL?&)
 
    1. Log into the VM (virtual machine) that has been created for you specifically for you, and create a create a working directory.
       ```
        - <user-id>.csun.edu
       ```
       - Note that the hostname for your VM is your cmapus user-id
       - Also note that you need to first ssh into one of the three aforementione shell servers first (or be on the VPN), and then ssh into your VM.
       - If you run into any problems with this step, contact "Barrett, Yolanda" <yolanda.barrett@csun.edu> immediately so that any problems can be fixed quickly.
  
   1. Establish accounts with the following online resources. In many cases, you might have already establish such accounts.
    - https://slack.com
      The communication tool for this class is Slack.
    - https://github.com
      All assigments and projects will be submitted via GitHub Classrooms, which requires a github account.
    - https://docker.com
      You will be using docker containers on you personal computer and on the CIT384 VM for all of your web hosting assignments.

  1. Setup your personal computer for CIT384:
    1. Install various software packages on your personal computer. In many cases, you might have already have these packages installed.
      - https://slack.co. // You also consider install the mobile slack application on your personal digital lifeline, aka your smart-phone.
      - https://github.co. // I recommend that you configure your account to authenticate using [SSH](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
      - https://docker.com

    1. Join the Slack CIT384 work space
      - Accept the automatic invitation via https://join.slack.com/t/cit-384/signup using your @my.csun.edu address
      - Add the 'fitzgerald-f21' channel, this is well all online-discussions will be conducted
      - Respond to the 'Hello Class' via the 'reply to thread' option (do NOT "Also send to #fitzgerald-f21")

    1. On your personal computer clone the CIT384 repository
      - git clone https://github.com/CIT384/class-material.gi. \~/classes/cit384/class-material/
      - Note that during the semester you will need to periodically perform a 'git pull' to obtain new material, updates, corrections, etc.

  1. Complete this first laboratory assignment
    1. Accept the assignment via GitHub Classroom
    1. Clone the assignment into the directory \~/classes/cit384/labs/getting-start
    1. Create a file called "<user-id>".env that contains the following information
    	```
    	name: Steven Fitzgerald
    	user-id: steve
    	email: steven.fitzgerald@csun.edu
    	githandle: smf-steve
    	```
	1. add this file to the repo (git add <user-id>.env)
	1. commit this change to the repo (git commit -m 'Some message' <user-id>.env)
	1. push to submit this assignment (git push)

  1. Now that you have read the instruction, in total:
    - You can no complete all the steps enumerated above, except
    - Do not seen me email to provide me with your @my.csun.edu email address,
    - this information is contained with the <user-id>.env file that you submit via GitHub Classroom




