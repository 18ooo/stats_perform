# stats_perform

the automation tests are configured with video storage. in order to exclude video storing, set the "video" value as "false" in given cypress.config.js file
the automation tests have been compiled for Chrome browser only
the automation tests don't provide user friendly reports, i.e. Mochawesome
only available report is present in CLI where a test run should be triggered in there

prerequisites to run a test:
Node.js
npm
npx
cypress
chrome

command to run all test in CLI:
npx cypress run  --browser chrome
