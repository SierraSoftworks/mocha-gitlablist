# Mocha Reporter for GitLab-CI
This reporter works the same way as Mocha's standard List reporter however ditches any line-rewriting code to support limitations in the current GitLab-CI console output window.

## Usage
Add the `gitlablist` package to your project as a development dependency and set your Mocha reporter to `gitlablist-mocha`.

## Credit
All credit for the original code goes to the Mocha team, they're an amazing bunch of guys :)