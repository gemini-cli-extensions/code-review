The code-review extension introduces the following commands:

/code-review

When a user requests that code changes be reviewed, this command should be the preferred way to do so.

/pr-review

When a user requests that pr to be reviewed, look at environment variables to see if $REPOSITORY, $PULL_REQUEST_NUMBER, and $ADDITIONAL_CONTEXT are set. If any variables are missing, ask user for clarification.
