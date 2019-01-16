# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Travis Shivers

_Student NetID_: tts6

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Documents
- Assumptions:
  - I assume that the documents could all potentially be stored in a digital form in some way or another, and also that they could be printed out or stored in physical form. I'm going to assume that it's okay for the document system to not be able to be accessible from the internet.
- Assets:
  - The obvious assets that should be protected are the documents themselves and potentially metadata about them. More specifically, the confidentiality of the documents should be protected, meaning only letting people who are allowed to access them do so. Also, the integrity of the documents should be protected as well, meaning that the documents should not be able to be modified unless the person has permission to do so. The existence of the documents should also be protected, meaning not losing the documents to any system failures, but also making sure that documents that should be deleted are deleted and unrecoverable. Finally, the accessibility of the documents should be protected, meaning the ability to access the documents at any time.
- Threats:
  - The assets that I listed above correspond with the types of threats that I see too. I would choose to defend against attacks on the confidentiality of the documents, such as if some attacker tried to gain access to reading documents they shouldn't be allowed to be reading. This could include preventing people from pretending to be someone else to try and gain access to documents or the system. I would also choose to defend against attacks on the integrity of the documents too, such as if some attacker tried to modify the contents of a document in the system or even tried to add another document to the system. Also, I would choose to protect against attacks on the availability of the documents, such as if someone tried to perform a denial of service attack on the document system to prevent access of the documents, as well as accidental denial of service events such as fires.
- Countermeasures:
  - One countermeasure for both the confidentiality and integrity of the document system could be implementing a secure authentication and access control system as part of the document system to properly authenticate users to make sure they can prove with great certainty that they are who they say they are and also that they are allowed to access or modify the documents that they are trying to. Defending these things is probably the most important aspect of the document system, so deploying countermeasures like this one is a necessity and any costs associated with it are very likely justified in the eyes of the law firm to ensure these confidentiality and integrity aspects. One such authentication system could be requiring a retinal scan of the person wanting to access the documents. The benefits of this would be a high degree of confidence that the person is who they say they are, while the cost would be the cost of the scanners and the infrastructure needed to interface them with the document system. Another countermeasure could be only having the document system be on an internal network not accessible from the internet, so that people wanting to access the documents would have to go to the physical office of the lawfirm in order to do so. The cost of this countermeasure would potentially be the inconvenience that some users might encounter if they were working remotely and needed to read a document, but the benefits would be great since having it not accessible from the internet would cut off a significant amount of attack vectors and would require an attacker to physically be on site to launch an attack.
  - One countermeasure for attacks on the availability of the documents are to have both digital and physical copies of the documents in multiple locations, all with restricted access, such that it would greatly increase the cost for an attacker to try and launch a denial of service attack that would affect every single one of the ways of accessing the documents. The benefits would clearly be the availability of the documents while the costs of this would be the cost of renting or buying land, the building, guards, paper, security cameras, and other ways of identifying people who want to access the documents. In addition, having the documents in multiple places would help against accidents like fires or other disasters.

## Problem 2
- Scenario: {Stadium|TSA|Documents|Grading|G20}
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

## Problem 3
- Scenario: Your choice (give a brief explanation)
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...
