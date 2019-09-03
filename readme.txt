DESCRIPTION
You must install a few postcss plugins and configure them for post-processing input CSS file.

PREPPERATION:
1) Node.js setup
2) Run 'npm install' in the 'source' directory
3) Done all requirements
4) Run ‘npm run postcss’
5) Check build.css file

REQUIREMENTS
1) Use 'Autoprefixer' to automatic add vendor prefixes
(https://github.com/postcss/autoprefixer)
    - $ npm install autoprefixer --save-dev
    - include it to config.json
    - add vendor prefixes only for 2 last versions of all modern browsers

2) Use 'CSSNano' to minify your build
(http://cssnano.co/)
    - $ npm install cssnano --save-dev
    - include it to config.json

WORKFLOW:
Upload implemented task to git in folder "<module name>/<topic name>/task-02"
Use current structure for the task + build.css (output file)

Structure of the task should be:

task-02
    src/
        styles.css
    config.json
    package.json

SOURCES:
src/styles.css - input CSS file
config.json - options for PostCSS CLI
package.json - npm dependencies

DEADLINE:
Due Date - 06-05-2019 23:59
Penalty will be applied for each overdue day