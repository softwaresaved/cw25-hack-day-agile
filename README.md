# CW25-Repository-Template
This is a template repository to be used as the base for new repos created for Collaborations Workshop 2025 projects. It comes with a set of default actions, tools and advice to help start your project properly.

# Immediate Set Up
The following steps will need to be performed immediately after creating the new repository to complete the set up.

## Branch Protection Ruleset
The first thing to do after creating your new repository from this template is to head to `Settings -> Rules -> Rulesets` then choose `Import Ruleset`. You will then need to import the `KeyBranchProtectionRules.json` ruleset which is stored within the `setup` directory in this repository.

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

# Suggest Improvements
Please feel free to suggest improvements to this template by adding issues to the repository.

# Licence

Copyright 2025 Research-IT, University of Manchester, UK

Licensed under [Apache Licence, version 2.0](https://www.apache.org/licenses/LICENSE-2.0). Any contributions received are assumed to be covered by the [Apache Licence 2.0](https://www.apache.org/licenses/LICENSE-2.0#contributions).


