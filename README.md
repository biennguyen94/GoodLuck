# GoodLuck
## Internship Program
### Kazoo
* Every intern creates their folder under GoodLuck/users, eg: GoodLuck/users/bien.n.nguyen. This folder is used for individual tasks and internship team is responsible for review/submit this folder by themself.
* For every task, we need a final report to be reviewed by mentors, these final reports are saved under GoodLuck/doc folder. This GoodLuck/doc folder will be shown in 192.168.122.41:7777 as a web document, note that internship team needs to check to make sure these reports are shown in web correctly. For more detail refer to 'How to build doc'
* Don't touch applications forder

### AtomVM
* Every intern creates their folder under GoodLuck/users, eg: GoodLuck/users/bien.n.nguyen. This folder is used for individual tasks and internship team is responsible for review/submit this folder by themself.
* For every task, we need a final report to be reviewed by mentors, these final reports are saved under GoodLuck/doc folder. This GoodLuck/doc folder will be shown in 192.168.122.41:7777 as a web document, note that internship team needs to check to make sure these reports are shown in web correctly. For more detail refer to 'How to build doc'
* The GoodLuck/applications folder is used for final reports of applications/projects, to be reviewed by mentors

## How to build doc
* Go to container: sphinx.sbg-internship
* Prepare final reports under GoodLuck/doc/src first
* Add these final reports to GoodLuck/doc/src/index.rst
* Build doc
    ```
    cd GoodLuck/build
    cmake ..
    make sphinx-html
    ```
* Go to 192.168.122.41:7777 to see the result
