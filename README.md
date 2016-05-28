![CF](https://i.imgur.com/7v5ASc8.png)  Test Repo (Demo)
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d4/00-test-repo-demo.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d4/00-test-repo-demo)   
This is only a test. Become familiar with the workflow for your lab assignments!

Get some practice in! 

1. Fork this repository.  
2. Copy the resulting git link to the clipboard.  
3. Clone this fork into your `driver` directory (review setup [instructions](https://github.com/codefellows/seattle-301d4/blob/master/README.md#create-and-setup-your-301-directory-structure)).  
4. `cd` into this repository.  
5. Immediately `git checkout -b test-branch`  
  - Notice the "build passing" message in this README file? That's an import from Travis CI - just one of many continuous integration tools used by organizations and project teams all over the world! We use Travis CI in this class to help us lint code being submitted (in your case as the developer, it will test any PRs you submit for proper linting).
  - Let's try and get a "build failing" message instead, so we can see what that's like.
10. Open up the `wat.js` file and remove the semicolon from the end of the line and save the file.
11. `git add wat.js`
12. `git commit -m 'remove semicolon to make the lint test fail'`
13. `git push origin test-branch`
13. Head over to GitHub to make a PR from `test-branch` and see what the result it!
