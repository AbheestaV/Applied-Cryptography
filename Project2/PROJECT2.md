Project 2.

Project type 1

Project type 2

Project type 3

Project type 4

Project type 5

Project type 6

Project type 7

Grading and Submission Policies: 

The project should be realized by a team of 2, 3 or 4 students (exceptions should be well motivated and allowed by the instructor; online students are allowed to be a 1-person team, although they are encouraged to be in larger teams). Teams are supposed to split the amount of work more or less equally among the team members and detail which member did what task in their submission; if a team splits the work in a way that is too unbalanced, the score given to team members may be suitably unbalanced. Project submissions from larger teams will be expected to do better and will be judged accordingly. Project scores will contribute to the class grade as specified in the syllabus.

The project comes with a minimal assignment and requires a submission of software, a presentation document and a 10/15-minute presentation video (including a video- or screenshot-based demonstration of your software), being graded according to scoring criteria defined below; any additional work you perform will be considered extra credit work (specifically, Extra Credit 3) if later you submit a short summary of it under the appropriate space for Extra Credit 3 under Quizzes.

There are three deadlines related to this project.

    A first deadline (November 18) only requires you to go to Quizzes and submit your tentative team names, project type and project title. You can later change this information.
    A second deadline (November 24) requires you to go to Quizzes and submit the design of your method/solution, in any desired form, so to obtain instructor/TA feedback before starting implementation (the instructor will not go over too many details of your design but will tell you if he can quickly see any major design flaws or omissions or improvement opportunities). You can later change the design as well.
    On the third and final deadline (December 10) you will go to Quizzes and submit the following information:
        team name (cool and creative),
        names and emails of team members,
        project type chosen (a number between 1 and 7)
        project title (descriptive of what you did)
        team names, a link to your presentation video (if you are an online student), and either a link to a software repository or an attached zip file containing your software and presentation document.
        as an attachment, a project presentation pdf file (generated from a ppt file), named <last-names>-cs6903-fall22-project-<chosen-project-type>-presentation.pdf
        as an attachment, your zipped software, including source, executable and any other files needed to compile, the zip file being named <last-names>-cs6903-fall22-project-<chosen-project-type>-software.<zip extension> and your contained files as <last-names>-presentation, <last-names>-source, etc. Please include all files that allow us to run or compile them.
    It is ok if only one team member submits all of the above, but the other members should still submit some short text describing a project title, the team name or teammates names, and specifically indicating the submitting team member. 

No late submissions can be accepted without score penalty and early submissions are encouraged.

Project types (to choose from): 

The team is free to choose (exactly) one of the project types described below. (I may be posting new Project Types gradually over time especially if they rely on later lectures; I expect in the end there will be between 7 and 10 types). Each project type, in turn, comes with several options you can choose from. If you already have a cryptography project in mind, tell me about it, and I can help you match it with the right Project Type on this page.

Project 2 Type 1 (Designing an end-to-end cryptography solution to protect your data application from attacks):

The project consists of a software implementation and demonstration of your method to enhance "your (ideally, real-life) data processing application" with end-to-end security (from start device to end device) against attacks that we have studied in this class, including at least the following 4 attacks: data eavesdropping, data modification, data originator spoofing and data replay. You will be asked to analyze variations and extensions of these attacks in the presence of the various parties involved in the data processing application, and to design your method based on state-of-the-art cryptographic algorithms and protocols, and implement your method using available cryptography libraries. See posted file for more details.

Project 2 Type 2 (Designing a Q/A-interface for helping a non-expert user to select a scheme for a given cryptography primitive):

The project consists of a software implementation and demonstration of methods that facilitate a user with no (or a minimal amount of) cryptography knowledge to select the appropriate scheme for a given cryptography primitive, among a set of options. Given a cryptographic primitive, you should create an "implementation usage" table containing potential schemes as rows and scheme features or properties as columns. The lectures contain some tables for some primitives. You can start from one of them, but are required to enhance it with at least one new row and one new column. You have to design a Q/A interface for a non-expert user asking possibly adaptive questions and ultimately selecting a valid scheme (or possibly a list of ranked schemes). You can use any publicly available decision tree algorithm (and code) in the literature to generate questions and selecting the scheme. You need to evaluate your own method with respect to one or two meaningful success metrics. See posted file for more details.

Project 2 Type 3 (Designing a cryptography solution to allow computation over your outsourced encrypted data via homomorphic encryption)

The project consists of design, software implementation and demonstration of your method to allow computation over outsourced encrypted data via homomorphic encryption. Assume Alice wants to outsource her dataset (e.g., numeric datasets, and/or text, image, audio, video files with keywords) to a cloud server Carol. Then, assume Alice desires confidentiality for her data and thus stores it at Carol's site in encrypted form, using a (partially or fully) homomorphic encryption scheme. Later, Alice may query Carol for a function to be computed over the stored encrypted data, as follows: (1) Alice specifies the query function to Carol; (2) Carol evaluates this query function over the encrypted data and returns a ciphertext to Alice; (3) Alice obtains the output of this function evaluation by decrypting the ciphertext obtained by Carol. See posted file for more details and https://github.com/google/fully-homomorphic-encryption for potentially very useful code.

Project 2 Type 4 (Outsourced secure/private computation, via homomorphic encryption, of machine learning classifiers):

Similar to project 2 type 3, replacing database computations with machine learning classifiers. See posted file for more details.

Project 2 Type 5 (Implementation and Comparison of Two-party and multi-party secure function evaluation schemes (Yao-based, FHE-based):

The project consists of design, software implementation and performance comparison analysis of at least 2 methods for secure 2-party or multi-party function evaluation, for one or more interesting functions of your choice. See posted file for more details and https://github.com/rdragos/awesome-mpc for potentially very useful code.

Project 2 Type 6 (Designing a quantum-resistant cryptography solution to secure your communication).

Create an implementation usage table for quantum-resistant cryptography schemes for a specific cryptography primitive of your choice. The table needs to include a performance feature column, where you enter the performance of all the schemes in the table on a common computing platform. You can obtain that by running available schemes with carefully chosen security parameters as well as other parameters. Details to appear soon. 

Project 2 Type 7 (Implementations and Performance Analysis of State-of-the-Art Advanced Cryptography Solutions)

The project consists of literature review, software implementation and performance analysis of state-of-the-art methods of "advanced cryptographic primitives or protocols" that we have only briefly studied or mentioned in this class. This could include review of a specific published research paper, software implementation of the main advanced cryptography solutions (i.e., primitives or protocols) in it, and performance analysis. See posted file for more details.

Cryptography libraries.

In many of the above project types, you are recommended to use software from cryptography libraries. If you are not sure which library, this link may help: https://en.wikipedia.org/wiki/Comparison_of_cryptography_libraries

Other useful links:

Homomorphic encryption: https://github.com/google/fully-homomorphic-encryption 

Multi-party computation: https://github.com/rdragos/awesome-mpc 


