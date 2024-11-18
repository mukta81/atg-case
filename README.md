# atg-case
## Prerequisites

You need to have node.js already installed, verify using node -v

## install playwright
npm install playwright

## install typescript
npm install -g typescript

## Executing the test case
npx playwright test selectBet.spec.ts

## run from root
atg-frontend-case-e2e-tests\atg-frontend-case-e2e-tests\app>

## info on test cases
total 5 test cases
test 001 - check for all data
test 002 - check for all data
test 003 - check for all data
test 004 - one set of row
test 005 - one set of row

## Features with test case traceability
User should be able to:
*  Select a bet type (`V75`, `V86`, `GS75`) and the most recent result for that bet type should be displayed  
---- test 002
    *  Following should be displayed: bet type, track name(s), start time  
    ---- test 001 (bet type), test 002 (track name(s), start time )
*  It should be possible to change sort order between most recent or oldest results first  
    ---- test 003
*  See information about the selected bet type’s races
    *  Following should be displayed: race number, race name, race start time  
    ---- test 004
*  See information about the starting horses in the race
    *  Following should be displayed: start number, horse name, driver first and last name  
    ---- test 005
*  See detailed information about each horse by clicking a horse’s row
    *  Following should be presented: trainer first and last name, name of the horse father  
    ---- test 005
