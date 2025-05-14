# CW25-Repository-Template
This is a template repository to be used as the base for new repos created for Collaborations Workshop 2025 projects. It comes with a set of default actions, tools and advice to help start your project properly.

# Immediate Set Up
The following steps will need to be performed to create, link, and setup your project board and repository.

## Create Project Board
Go to the [Software Saved Project Board Template](https://github.com/orgs/softwaresaved/projects/42), and click on the green **Use this template** button. Select the owner organisation or user for your project board, name the project board, and click **Use template**.

## Create Project Code Repository
At the top-right of this repository webpage, click the green **Use this template** button, and select **Create a new repository**. Don't select 'Include all branches' - we only want the default branch. Chose an owner organisation or user (having the same owner as your project board will make things a *lot* easier). Name the repository, and click **Create repository**.

## Link Project Board and Code Repository
Select the **Projects** tab at the top of the repository page. Click the **Link a project** button, and select your project board.

Then, on the project board click the `...` button at the top-right of the page, then select **Workflows**. On the workflows page select the `Auto-add to project` option on the left panel. Click the `edit` button at the top-right, select your project repository, and set the rules to be `is:issue,pr is:open`. Finally click the green **Save and turnon workflow** button.

## Branch Creation
The default branch is `develop`. When following Gitflow development practice you will be creating feature branches from this branch, carrying out your work in these, then merging them (via Pull requests) back into `develop`. It is common to have a `main` branch too, to which you will merge (via Pull requests) code from `develop` for release to end users. A `main` branch is not included when you create your code repository, but you can create this by clicking on the branch button (showing `develop`) at the middle-left of the repository page, and selecting the `View all branches` screen. Then click the green `New branch` button to the top right of the page.

## Branch Protection Ruleset
The first thing to do after creating your new repository from this template is to setup up the branch ruleset. Download the `KeyBranchProtectionRules.json` ruleset which is stored within the `setup` directory in this repository to your computer. Then head to `Settings -> Rules -> Rulesets` then choose `Import Ruleset`. Import the `KeyBranchProtectionRules.json` ruleset that you have just downloaded.

**This ruleset is designed to enforce a GitFlow development process which protects your main code branches. It is advised to not relax or disable these rules unless exceptional circumstances dictate it e.g. if an existing CI integration requires a rule to be relaxed.**

## Licensing and Copyright
This template repository is shared under the [Apache v2.0](http://www.apache.org/licenses/LICENSE-2.0) licence, a copy of which is provided in the file LICENSE. The Apache v2.0 licence has been chosen because it is both permissive and self-enforcing for contributions or modifications. By being permissive, it allows the software to be combined with other software governed by different licences (if the licence for that software allows it). It also does not restrict distribution, including within commercial products, without requiring release of all source code, including that not under this licence.

If you are producing non-code documentation, written material, or literature, and wish to use an open licence, then a creative commons licence could be more appropriate. The [CC-BY 4.0 licence](https://www.tldrlegal.com/license/creative-commons-attribution-cc) is recommended, as this allows any use of the material but requires attribution to the original authors.

If you wish to change the licence then guidance on open source licensing choices are available from [choosealicense](https://choosealicense.com). Once you have chosen a licence, delete the LICENSE file in this repository, then select 'create a file' option and name the new file 'LICENSE'. At this point GitHub will provide a range of open-source licence templates for you to chose from. Follow the instructions included to create your new licence. 

Intellectual property (IP) created as part of your job will usually reside with your employer. In such a circumstance the copyright of your work should be marked "Copyright <YEAR> <Employer>". Guidance on copyright issues should be available from them (see, for example, the [University of Manchester library](https://subjects.library.manchester.ac.uk/copyright/research) guidance).

To state the copyright, and use the Apache v2.0 licence, you should include the following text in your README.md file:
```
Copyright <YEAR> <Author>, <Institution>

Licensed under [Apache Licence, version 2.0](https://www.apache.org/licenses/LICENSE-2.0). Any contributions received are assumed to be covered by the [Apache Licence 2.0](https://www.apache.org/licenses/LICENSE-2.0#contributions).
```
Within the LICENSE file boilerplate text is included, that you can add to your source files as required.

## Setup `.gitignore`
Setup `.gitignore` according to your project needs, see `.gitignore` templates [here](https://github.com/github/gitignore/tree/main).

## Cleanup
Delete the `setup` folder and it's contents.

## Replace `README.md`
Edit this readme file, and replace it with information relevant to your project.

Recommended sections:
- Project description
- Software requirements
- Installation instructions
- Usage guidelines / Quickstart
- Contribution guidelines
- Licence and Copyright

## Citation Guidance
If you want to help others to properly cite your project, you can creation a citation 

# Suggest Improvements
Please feel free to suggest improvements to this template by adding issues to the repository.

# Licence

Copyright 2025 Research-IT, University of Manchester, UK

Licensed under [Apache Licence, version 2.0](https://www.apache.org/licenses/LICENSE-2.0). Any contributions received are assumed to be covered by the [Apache Licence 2.0](https://www.apache.org/licenses/LICENSE-2.0#contributions).


