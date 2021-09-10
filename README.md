# plan
A plan list for generating Dapeng's backlog

- assist set up monorepo environment DOP-1747
- - ECR ECS IAM role setups 
- - connect with Lambda BFF
- - image lifecycle & routine clean up
- - repositories
- build Azure pipeline for monorepo CICD
- - build APP image
- - version apps & tag image & push to ECR
- - deploy the image in the correct cluster (tasks creation & execution)
- - allow deploy multiple apps
- Unit test integration & TDD


deploy multiple apps
- flag & version control
- buffer environment - no
- the ability to deploy multiple apps in the same time (container - > and return multiple links)
