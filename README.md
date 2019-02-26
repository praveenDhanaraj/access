# pa11y-jenkins

A basic pipeline that tests for accessibility a single URL integrated in
Jenkins. It needs no Jenkins plugin, only `docker` available.

Assuming the Jenkins installation already has docker, simply importing this
project as a `Pipeline` project and executing it should create the docker image
for `pa11y`, and run it against the `SITE_URL`.

The `SITE_URL` defaults to
[http://germaniumhq.com/2019/02/26/2019-02-26-Pa11y-Accessibility-Testing-With-Docker-and-Jenkins/](http://germaniumhq.com/2019/02/26/2019-02-26-Pa11y-Accessibility-Testing-With-Docker-and-Jenkins/)
