# Testing Ways to Anonymize a git repo for double-blind publications


1. https://anonymous.4open.science tool

Words to be removed Matteo, Italy, Github, Milan.

Anonymized repo
https://anonymous.4open.science/r/efbb23f6-4561-4364-9039-19f8fbb742eb/

2. https://www.gitmask.com/#terminal

Run the following commands locally:

git bundle create commits.bundle origin/master
curl -L -X PUT --upload-file commits.bundle https://git.gitmask.com/v1/bundle/github.com/mrava87/Testing_Anonymous/master
