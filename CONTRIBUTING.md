# Contributing
1. Fork the repository.
2. Create a topic branch.
3. Add tests for your unimplemented feature or bug fix.
4. Run `script/test`. If your tests pass return to step 3.
5. Implement your feature or bug fix.
6. Run `script/test`. If your tests fail return to step 5.
7. Run `open coverage/index.html` in your browser. If your changes are not completely covered by your tests, return to step 3.
8. Run `rubocop` and see if your code has created any offenses, if it did return to step 5.
9. Add documentation for your feature or bug fix.
10. Run `yard`. If your changes are not 100% documented, go back to step 9.
11. Add, commit, and push your changes. For documentation-only fixes, please add `[ci skip]` to your commit message to avoid needless CI builds.
12. Submit a pull request.
