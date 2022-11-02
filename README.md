<span id="title">

# Basic Thymio benchmark

</span>

[![webots.cloud - Benchmark](https://img.shields.io/badge/webots.cloud-Benchmark-007ACC)](https://benchmark.webots.cloud/run?version=R2022b&url=https://github.com/TotallyRandomGus/container-benchmark/blob/main/worlds/robot_programming.wbt&type=benchmark)

## Description

<span id="description">

In this benchmark you will learn how to program a Thymio in Webots.

</span>

<img src="./preview/thumbnail.jpg" width="75%">

## Information

<span id="information">

- Difficulty: Middle School
- Robot: Thymio II
- Language: Phyton
- Commitment: one second

</span>

---

## How to participate

### Create your own entry repository from the template
1. [Click here](../../generate) to create your own repository or do it manually by clicking on the green "Use this template" button.
1. Fill the "Repository name" field with a name for your controller.
Choose the visibility of your controller, keep it "Public" if you don't care about people looking at your controller code otherwise set it to "Private".
Finally, click on the green "Create repository from template".

You should now be on your own repository page. The URL should look like this: "https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME".  If it is not the case, go to your repositories and click on the first one from the list.

#### If you set your repository as private, add the organizer as collaborator:
1. ![Click here](../../settings/access) to go to the "Collaborators" setting page
   1. You might need to confirm the access by re-entering your GitHub password.
1. You should see a "Manage access" box where you will see the current collaborators of the repo.
Click on the "Add people" and search for "TotallyRandomGus". When you found the organizer, add them to the repository.

### Register yourself by using posting an issue
1. Go back to the main page of your repository if that is not the case and copy the repository URL from the address bar to your clipboard.
1. ![Click here](https://github.com/TotallyRandomGus/container-benchmark/issues/new?assignees=&labels=registration&template=registration_form.yml&title=Registration+to+benchmark) to go to the organizer repository and start your registration. If it doesn't work, you can do it manually by going to the organizer's repository, then to the "Issues" tab, creating a new issue and choosing "Registration to benchmark".
1. Paste your repository URL in the URL field and click the "Submit new issue" button.

A series of automated actions will take place in a few seconds. If everything went well, you should get a message saying that you are successfully registered to the benchmark. If there was a problem, read the feedback message to fix what went wrong. When you finished fixing your repository, you can post a "retry" comment on the registration issue to re-run the automated verifications.

### Modify the template controller and/or create your own one

Everything should be good to go, you can modify the main controller files in the controllers folder.

The supervisor controller is the special controller that is used to evaluate your controller's performance.

Your controller is evaluated in a [Docker container](https://www.docker.com/resources/what-container/). If you want to make a more complex controller, you are free to use any library that you want but be sure to update the controller_Dockerfile with any dependencies you would need. The default Webots Docker container has the tools needed to run and compile C, C++ and Python controllers.
