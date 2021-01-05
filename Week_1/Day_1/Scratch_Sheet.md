## Make Virtual Environment
1. conda create -n bootcampEnv python=3.8 and conda activate bootcampEnv
2. install ipykernel, if already installed:
3. python -m ipykernel install --user --name=bootcampEnv
4. deactivate bootcampEnv
5. Check jupyter lab from base environment, it should contain the new virtual environment

## Command Line Cheat Sheet
1. enter q to exit 'less'
2. use Ctrl + C to exit a node or stop a command

## Bash Practice Q&A with mentor
I used a simple sed command to change the delimiter from , to ; in a csv, is there a better way to do this in case the content contains commas which I do not want affected? 

Mentor suggested looking into regular expressions with sed

Check sed manual

Explore regex101.com to explore and test how to use reg ex in something like bash. 

eg: [] or ,\w, \W to only affect commas not followed directly by a character