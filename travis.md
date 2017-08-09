# Travis CI

Travis CI is a continuous integration service used to build and test projects hosted on Github. We will use it in this course to automatically test the code you submit, though the grading will not be automatic.

1. Go to travis-ci.com (not .org). Sign in with your github account.

2. On the left of your profile page, you should see a list of the organizations you belong to. One of the organizations should be this course (e.g. cisc3130). Click on the course.

3. You should now see a list of repositories belonging to the organization for which you are an admin. Click the switch on each one to enable Travis CI for each repository.

4. Now, whenever you push a new commit, Travis CI will try to compile and run your code. You should get an email with the results of the build. Additionally, in your commit history, each commit will have a check or cross next to it indicating whether it has passed the tests. Finally, the pull request you submit as homework will show whether it is currently passing.

5. You can click on any of these indications to go to your account on Travis CI to see the log of the build status. If you scroll down to the bottom of the log (which looks like terminal output) you will see the result of the build test(s) (there may be more than one). Green indicates a test that passed, red indicates a test that failed. Output from the build will be there as well.
