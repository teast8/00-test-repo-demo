![CF](https://i.imgur.com/7v5ASc8.png)  Test Repo (Demo)
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d4/00-test-repo-demo.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d4/00-test-repo-demo)   
This is only a test.

Get some practice in! 

1. Fork this repository.  
2. Copy the resulting git link to the clipboard.  
3. Clone this fork into your `driver` directory (review setup [instructions](https://github.com/codefellows/seattle-301d4/blob/master/README.md#create-and-setup-your-301-directory-structure)).  
4. `cd` into this repository.  
5. Immediately `git checkout -b test-branch`  
6. `cp -r starter-code/ submissions/brian-rick`   
  - The command above copies the starter-code directory and its contents, and places them directly into the submissions directory with the new name that you provide it with in the path (in this case, `brian-rick`). 
7. `git add submissions/brian-rick`
8. `git commit -m 'add new demonstration directory for our test repo!'`
  - We do not need to push anything yet. Commiting at different stages and continuing on is good practice. Think of it like check points in a video game. Multiple save files that we can go back to if needed.
9. `cd submissions/brian-rick`
  - Notice the "build passing" message in this README file? That's an import from Travis CI - just one of many continuous integration tools used by organizations and projects all over the world! We use Travis CI in this class to help us lint code being submitted (in your case as the developer, it will test any PRs you submit for proper linting).
  - Let's try and get a "build failing" message to see what that's like.
10. Open up the `wat.js` file and remove the semicolon from the end of the line and save the file.
11. `git add wat.js`
12. `git commit -m 'remove a semicolon to make the lint test fail'`
13. `git push origin test-branch`
13. Head over to GitHub to make a PR from `test-branch` and see what the result it!
