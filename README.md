# 04 GitHub Pages Deployment

This Projects serves as an introduction into CI/CD and how github actions works and the syntax used for it. whenver a push is made a vm is spun up with certain permissions and then checks the repo conigures the pages packages the files and then publishes them.

Project page: [roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)

## what I learned
- I learned how CI/CD automates deployments with github pages. pushing to main triggers a vm that builds and deploys without physcial intervetion
- I learned about the syntax and how important indentation is
- I learned how to deploy when specific files are changed with on and paths
- i learned how to use prebuilt actions using "uses" I was able to use actions/checkout instead of writing it all on my own
- I Learned about artifacts package files for handoff 
- I Learned how to clone a repository 
- i learned how to create permissions using the "content: read"