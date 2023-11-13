# COMMAND

added 228 packages in 17s

45 packages are looking for funding
  run `npm fund` for details
npm notice 
npm notice New major version of npm available! 9.8.1 -> 10.2.3
npm notice Changelog: https://github.com/npm/cli/releases/tag/v10.2.3
npm notice Run npm install -g npm@10.2.3 to update!
PS H:\Activities-exercises\ngcalculator> Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
PS H:\Activities-exercises\ngcalculator> ng serve
ng : The term 'ng' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if   
a path was included, verify that the path is correct and try again.
At line:1 char:1
+ ~~
    + CategoryInfo          : ObjectNotFound: (ng:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException
 
PS H:\Activities-exercises\ngcalculator> npm install -g npm

added 1 package in 6s

26 packages are looking for funding
PS H:\Activities-exercises\ngcalculator> ng serve
ng : The term 'ng' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if   
a path was included, verify that the path is correct and try again.
At line:1 char:1
+ ng serve
    + CategoryInfo          : ObjectNotFound: (ng:String) [], CommandNotFoundException
PS H:\Activities-exercises\ngcalculator> npm bin -g
Unknown command: "bin"

To see a list of supported npm commands, run:
  npm help
PS H:\Activities-exercises\ngcalculator> npm prefix -g
>> 
C:\Users\jappsb23\AppData\Roaming\npm
PS H:\Activities-exercises\ngcalculator> $env:Path += "C:\Users\jappsb23\AppData\Roaming\npm"
PS H:\Activities-exercises\ngcalculator> ng --version
Error: You need to specify a command before moving on. Use '--help' to view the available commands.
PS H:\Activities-exercises\ngcalculator> ng --help
ng <command>

Commands:
  ng add <collection>            Adds support for an external library to your project.
  ng analytics                   Configures the gathering of Angular CLI usage metrics.
  ng build [project]             Compiles an Angular application or library into an output directory named dist/ at the given output path.        
                                                                                                                                      [aliases: b]  ng cache                       Configure persistent disk cache and retrieve cache statistics.
  ng completion                  Set up Angular CLI autocompletion for your terminal.
  ng config [json-path] [value]  Retrieves or sets Angular configuration values in the angular.json file for the workspace.
  ng deploy [project]            Invokes the deploy builder for a specified project or for the default project in the workspace.
  ng doc <keyword>               Opens the official Angular documentation (angular.io) in a browser, and searches for a given keyword.[aliases: d]  ng e2e [project]               Builds and serves an Angular application, then runs end-to-end tests.                                [aliases: e]  ng extract-i18n [project]      Extracts i18n messages from source code.
  ng generate                    Generates and/or modifies files based on a schematic.                                                [aliases: g]  ng lint [project]              Runs linting tools on Angular application code in a given project folder.
  ng new [name]                  Creates a new Angular workspace.                                                                     [aliases: n]  ng run <target>                Runs an Architect target with an optional custom builder configuration defined in your project.
  ng serve [project]             Builds and serves your application, rebuilding on file changes.                                      [aliases: s]  ng test [project]              Runs unit tests in a project.                                                                        [aliases: t]  ng version                     Outputs Angular CLI version.                                                                         [aliases: v]

Options:
  --help  Shows a help message for this command in the console.                                                                          [boolean]

For more information, see https://angular.io/cli/.
PS H:\Activities-exercises\ngcalculator> ng serve
Node packages may not be installed. Try installing with 'npm install'.
Error: Could not find the '@angular-devkit/build-angular:dev-server' builder's node package.
PS H:\Activities-exercises\ngcalculator> npm install
npm WARN deprecated @babel/plugin-proposal-unicode-property-regex@7.18.6: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-unicode-property-regex instead.
npm WARN deprecated @npmcli/move-file@2.0.1: This functionality has been moved to @npmcli/fs
npm WARN deprecated @babel/plugin-proposal-async-generator-functions@7.20.7: This proposal has been merged to the ECMAScript standard and thus this plugin is no longer maintained. Please use @babel/plugin-transform-async-generator-functions instead.
npm WARN deprecated w3c-hr-time@1.0.2: Use your platform's native performance.now() and performance.timeOrigin.
npm WARN deprecated @wessberg/ts-evaluator@0.0.27: this package has been renamed to ts-evaluator. Please install ts-evaluator instead

added 1009 packages, and audited 1010 packages in 2m

117 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS H:\Activities-exercises\ngcalculator> ng serve
? Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.io/analytics. No
Global setting: not set
Local setting: disabled
Effective status: disabled
✔ Browser application bundle generation complete.

Initial Chunk Files   | Names         |  Raw Size
vendor.js             | vendor        |   2.04 MB |
polyfills.js          | polyfills     | 333.17 kB |
styles.css, styles.js | styles        | 230.61 kB |
main.js               | main          |  20.21 kB |
runtime.js            | runtime       |   6.52 kB |

                      | Initial Total |   2.61 MB

Build at: 2023-11-13T03:39:12.238Z - Hash: a6ad494a2350b452 - Time: 18160ms

** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **


√ Compiled successfully.


important 
 $env:Path += "C:\Users\jappsb23\AppData\Roaming\npm"
