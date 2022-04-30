# Full Stack open CI/CD - exercise 1

----
#### Tools
The application will be coded in Python. Tools used for linting, testing and building in Python are:
- flake8 for linting, black for some extra code cleaning (it contains a few extra rules on top of PEP8 standards), and pre-comit for automating various tasks before commiting (it allows user to specify an array of different tasks that he would like performed any time he tries to commit new code)
- pytest (standard library used for unit testing) with pytest-cov (extension for presenting code coverage - percentage of source code that is checked by used tests)
- no building step in Python (it is an interpreted language).
----
#### Alternatives
Alternatives to Jenkins and GitHub Actions are:
- Circle CI,
- GitLab CI,
- Azure Pipelines,
- Atlassian Bamboo,
- JFrog Pipelines,
- Spinnaker,
- Buddy,
- CruiseControl,
- IBM UrbanCode, 
- Team City,
- etc.
----
#### Environments
For deciding whether it is better to put this application in a self-hosted or a cloud-based environment we need following information:
- size of a project (team of six people)
- time to finish it
Because the project is relatively small and it will be released soon (meaning: there is not much time to lose on setting up system for CI/CL), cloud-based environment would be a better option. Otherwise, it could become unnecessarily  expensive, time consuming and complicated.
----
