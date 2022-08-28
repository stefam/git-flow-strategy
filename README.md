# Contributing on Git Flow Strategy

## Branch Categories
- feature
- bugfix
- release
- hotfix

## Feature Branch Naming
* <strong>Feature Branch Name Template</strong>:<br />
`{Branch Category}/{task number}-{Short Feature Name}`

## Adding Changes
1. Create your feature branch<br/>
   `git checkout -b feature/1143-amazing-feature develop`
2. Stage changes<br/>
   `git add .`
3. Commit your changes<br/>
   `git commit -m '#1143 - Add some amazing feature'`
4. Push to the branch<br/>
   `git push origin feature/1143-amazing-feature`
5. Open a Pull Request to `develop` branch

## Release Branch Naming
* <strong>Release Branch Name Template</strong>:<br />
`release/{Major Change}.{Minor Change}.{Patch}`

## Creating a Release
1. Create your release branch<br/>
`git checkout -b release/0.1.0 develop`
2. Once tests are done and passed Open a Pull Request to `main` branch
