# Pattern Lab node solution with gulp

Pattern lab framework without PHP executable files

Modified source of pattern-lab framework to include scss files

source : https://github.com/pattern-lab/patternlab-node

# Notes

- Do not include package-Gruntfile.js & package.grunt.json unless using grunt is preferred for your project. In doing so rename the current package.json to
package.gulp.json and 'package.grunt.json' to 'package.json'.
- When package-Gruntfile.js is renamed to gruntfile.js the 'gruntfile' needs to be modified to complie .scss files and .js concat files, add the required
devDependencies in package.json as needed


