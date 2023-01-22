# design-system

## initiate project with yarn init -y

## initiate git repo with git init

## create .gitignore

## SCSS design system
    create foundation and base folders
    install stylelint dependencies for scss 
    create .stylelintrs.json
    create scripts for stylelintrc.json in the package.json


1. Create folders: scss => src => foundation with files

    * _colors.scss - define default colors
    * _typography.scss - define default typography
    *_variables.scss - define variables
    * _mixins.scss - define functions
    * _all.scss - import all files

2. Create folder: scss => src => basic with files

    * _reset.scss - Normalize-scss is npm package to normalize browser rendering
    * _root.scss - scss is not fully compatible with css variables, so we have to embed them.

3. Create file: scss => src 
    * global.scss - import foundation and basic 

4. install stylelint and prettier packages with
    yarn install --dev prettier stylelint stylelint-config-prettier stylelint-config-sass-guidelines stylelint-prettier

5. create .stylelintrs.json

6. add scripts in the package.json

7. command for starting lint
    yarn lint