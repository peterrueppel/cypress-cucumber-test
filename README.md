## Primitive Cypress project that uses @badeball/cypress-cucumber-preprocessor.

ATTENTION: The binary **cucumber-json-formatter** has to downloaded for the
actual used platform (linux, mac, windows)

from `https://github.com/cucumber/json-formatter/releases/tag/v19.0.0`

and to be placed in the folder `./binary` as `cucumber-json-formatter`

General useful Links about Cypress / Cucumber / Xray integration:
1. https://docs.getxray.app/display/XRAYCLOUD/Testing+using+Cypress+and+Cucumber+in+JavaScript
2. https://docs.getxray.app/pages/viewpage.action?pageId=31622264
3. https://www.npmjs.com/package/@badeball/cypress-cucumber-preprocessor
4. https://github.com/badeball/cypress-cucumber-preprocessor/blob/master/examples/webpack-ts/cypress.config.ts

To execute the primitive test do:
1. `npm install`
2. download cucumber-json-formatter (see above)
3. `npm test`
4. see files in `./output` folder

Next step: try to import `./output/cucumber-report.json` in Jira / Xray!
