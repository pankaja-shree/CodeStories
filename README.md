# bears-25

## Project: CodeStories

* A platform for coders/developers to share their story, experience, motivation, tutorials, hacks, etc along the coding journey.
* Mockup - https://xd.adobe.com/spec/06611bd8-a40b-476e-b091-6ced92a67373/

## Tech stack

* Backend language: Node
* Database: Mongodb
* Backend Framework: Express
* Frontend: Vue

## Git workflow

* Based on [this](https://medium.com/@francesco.agnoletto/how-to-not-f-up-your-local-files-with-git-part-1-e0756c88fd3c) article, important points are summarized here for ease of reference.

* `master` branch - production branch - when everything is tested and works, update this branch
* `development` branch - It is a base for all the other branches - You do not code here, you send pull requests here to be checked by other members of your team and merged. The team members have to check your code and then merge to development.
* All other branches are of the format - `Type/short-description` - see below for more info

### Branches where coding is done -

* 4 basic types of branches:
| Branch name | Purpose | Example
----------------------------------
| `bug` | Bugfixes | "bug/fixed-all-caps"
| `feature` | for developing new features | "feature/giant-duck-modal"
| `refactor` | code refactoring | "refactor/add-prop-types"
| `style` | design/css stuff | "style/everything-is-black"








