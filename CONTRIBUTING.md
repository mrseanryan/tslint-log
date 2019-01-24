# Contributing to tslint-log

## Instructions

These steps will guide you through contributing to this project:

- Fork the repo
- Clone it and install dependencies

		git clone https://github.com/YOUR-USERNAME/tslint-log
		npm install

Make and commit your changes. Make sure the commands npm run build and npm run test:prod are working.

Finally send a [GitHub Pull Request](https://github.com/alexjoverm/tslint-log/compare?expand=1) with a clear list of what you've done (read more [about pull requests](https://help.github.com/articles/about-pull-requests/)). Make sure all of your commits are atomic (one feature per commit).

### dependencies

We use [yarn](https://yarnpkg.com/lang/en/docs/install) because we like it.

### use a feature branch

It's best to first develop on a feature branch - named like `feature/my-feature`, and then when it has a green build, merge it to master.

### running tests

before pushing:

`yarn build-and-test`

### merging to master

merging a feature branch into master: (after the build is green!)

#### via github site (recommended)

- create pull request for the feature branch
- merge the pull request into master

#### via command line (not recommended, as then need to delete branches)

```
git checkout master
git fetch && git pull
git merge feature/my-feature
git push
```

### releasing (from master branch)

`yarn pub`
