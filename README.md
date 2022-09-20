# changesets-hello-world

Changesets allows you to manage version control for your packages by creating a `CHANGELOG.md` THAT updates after squashing all patches, minors and majors.

To prepare a new repository for `changesets`, you can find instructions [here](https://github.com/changesets/changesets/blob/main/docs/intro-to-using-changesets.md#add-the-changeset-tool).

`npx changeset` will allow you to document a change that you'd like to put under a patch, minor or major.

`npx changeset version` will collect up all patches, minors and majors and put out a new version within the `CHANGELOG.md` describing those patches, minor or major changes.