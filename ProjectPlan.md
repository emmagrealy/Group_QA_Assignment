ProjectPlan.md

 ProjectPlan: 

1. Topics:

Topics: |Assigned To:
------------ | -------------
Task Estimation: | All 4 as Group
Code Standards: | Emma and David
Code Review :   | Niamh and Gillian

2. David creates the master branch and also creates the develop branch 
    - Add the rest of us as collaboters, where each of us accept the invitation.

3. The other team members then fork Davids source respository.

4. Each member clones this respository created to their local machines. 
    > git clone https://github.com/your-username/git-flow-exercise.git

    i.e. cloning the fork copy not the orginal.  

5. Ensure the relevant branches are there:
    > git branch 

    Notice the result of this will only be local branch:
    >*master

    Next need to search for remote branches:
    > git branch - r
    
    Then checkout the develop branch, in order to get local copy:
    > git checkout develop

6. Create a feature branch for each topic -- Create this off the develop branch 
    ![](feature_branch_develop.png)

7. Research your given topic and find 5 good quality resources (articles, blog posts etc) related to the topic and identify common themes among those resources. 

    - Briefly introduce the topic.
    - Summarize most important guidelines in bullet points / diagrams.  
    - NB: highlight both good and bad practices. 

8. Commit regulary to the corresponding feature branch. On complete merge to the develop branch, by making a pull request. 

9. Ensure team members review and give feedback on pull requests. 

10. On completion, have a group retrospective. Identify what went well and what could have been done better.

