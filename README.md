##ChallengeWK3

## Be competent automating Jenkins 

### What was the challenge? 

- The challenge was to automate Jenkins carry out triggered tasks. The task was to use Jenkins pipelines that take an app and its dependencies from a given git repo,  make the builds, carry out given tests, create images in Docker and push these images to nexus upon being triggered by a push to the repository.

### How I expected the challenge to go. 

- I was confident in my understanding of Docker and how to use it after covering the modules. As I had access to videos of the demo's I was confident the task was acheiveable. I also had the piece of mind that Ben, our trainer would be on hand to lend assistance if required.

### What went well? 

- The demo's were essential in getting a handle on using Docker, Jenkins and Nexus, I was able to quickly reference any gaps in knowledge as well as verify the steps required at each stage.

### What didn't go as planned? 

- Unfortunately I experienced issues with my VM, it would had connectivity issues and would freeze when running the Docker build commands. I was forced to wipe the storage clean a few times as well has reset the VM in order to complete the challenge. I also hadn't planned on 2 scheduled meetings which took longer than expected, this took up quite alot my time, about 3 hours unexpectedly particularly very close to the 3pm deadline. In the end I was assisted by Holly and Ben to complete the task.

### Possible improvements for future challenges. 

In future I would test the VM first thing in the morning, on this occasion I watched the demo's in the morning to write down the correct syntax for the tasks. By the time I was ready to work in the VM, the scheduled meetings were looming and this meant reduced time on the challenge.













# NBS Challenge 3

## App

### Environment

To use the app you need to make sure the requirements are installed.
It is best to do this in a virtual environment OR use a Docker container.

#### Venv

```bash
sudo apt update && sudo apt install python3-pip python3-venv -y
python3 -m venv venv
. ./venv/bin/activate
```

### Testing

Then you can run the tests. This can only be done if the dependencies in requirements.txt are installed.

```bash
# In the root of the project
pytest
```

### Running

Or you can run the app.

```
python3 app.py
```
