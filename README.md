## ChallengeWK3

## Be competent automating Jenkins 

### What was the challenge? 

- The challenge was to automate Jenkins to carry out triggered tasks. In this case the task was to set up Jenkins pipelines that take an app and its dependencies from a given git repo,  make the necessary builds, carry out given tests, create images in Docker and push these images to nexus upon being triggered by a push to the repository.

### How I expected the challenge to go. 

- I felt the challenge would be straightforward, it felt the variuos components we had been shown in isolation could be brought together in this challenge

### What went well? 

- 

### What didn't go as planned? 

- 

### Possible improvements for future challenges. 

-
    
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      

NBS Challenge 3

App

Environment

To use the app you need to make sure the requirements are installed.
It is best to do this in a virtual environment OR use a Docker container

Venv

```bash
sudo apt update && sudo apt install python3-pip python3-venv -y
python3 -m venv venv
. ./venv/bin/activate
```

Testing

Then you can run the tests. This can only be done if the dependencies in requirements.txt are installed.

```bash
# In the root of the project
pytest
```

Running

Or you can run the app.

```
python3 app.py
```
