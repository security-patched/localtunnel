# peparing a patch

1. update version field in `package.json`
2. add change to git `git push` and review
3. create tag `git tag -a 2.0.2-secpatched.<<version>> -m "release 2.0.2-secpatched.<<version>>"
4. push with tags `git push --tags`
5. publish to npm `npm publish --access public` (will need to be logged into npm first)
6. create release in github
