name: Greeting from LAM Yan Yu
on: push
jobs: my-job:
name: My Job
runs-on: ubuntu-latest steps:
- name: Print a greeting
      env:
        MY_VAR: Hi there! My name is
        FIRST_NAME: Yan Yu
        MIDDLE_NAME: Ashlynn
        LAST_NAME: LAM
run: |
echo $MY_VAR $FIRST_NAME $MIDDLE_NAME $LAST_NAME.
I added this line in the "master" branch.
