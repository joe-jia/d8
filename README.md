# Wesley Mission QLD Drupal 8 test

REQUIREMENTS: 
* Test must be completed along with the [questionnaire](http://bit.ly/wmq-d8test). 
* Test must be submitted as a link to a public git repository.
    If you don't have public git access, you can create free account at one of the popular version control services e.g. [GitHub](https://github.com/), [Bitbucket](https://bitbucket.org/) or [GitLab](https://gitlab.com/).
* You don't have to complete the whole test. 
    Complete as much as you think necessary to demonstrate your skills.
    Comment if you are unable to complete particular sections and state your reasons.

## Tasks

### Section 1: documentation

1. Update current README.md file. 
2. Add THEME section and list your preferred Drupal theme (or themes). 
3. List pros, cons and possible usage of the theme (or themes).
4. Provide solution as `feature/section-1-doc` branch.

### Section 2: configuration

1. Create content type `Petition`.
2. Add fields:
    * `Category` taxonomy reference to `Petition Category` vocabulary
    * `Closing date` date and time [compulsory] 
3. Display `Category` and `Closing date` as inline label and field value.
4. Export above content type, fields and taxonomy as Feature
    * add feature files and folders to root folder of this repository 
    * provide solution as `feature/section-2-config` branch.

### Section 3: contributed modules

1. Add URL pattern for `Petition` content type: `petition/[title]`.
2. Display `Category` and `Closing date` in separate columns one next to another.
3. Create view to display
    * page with all petitions 
    * block with 5 latest petitions 
4. Update feature from `Section 2` 
    * add feature files and folders to root folder of this repository 
    * provide solution as `feature/section-3-modules` branch.

### Section 4: frontend development

1. In `index.html` create 3rd column below jumbotron.
2. Change colour of jumbotron header to `#6666AA`
3. Change `Sign up today` green button to blue.
4. Commit above changes as `feature/section-4-frontend-devel` branch.

### Section 5: git

1. Merge all 4 above branches into 1.
2. Provide solution as `feature/section-5-merge` branch.

## Hints

You can add this module to your Drupal installation by

* Clicking on download icon [here](https://gitlab.com/wmqld/dev-test-d8)
* Unarchive module to your Drupal module location
* Rename unarchived folder to `wmq_dev_test`  
