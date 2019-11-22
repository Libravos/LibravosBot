## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## whatIsMyPremium
* whatIsMyPremium
  - utter_premiumResponse

## whatIsMyConverage
* whatIsMyCoverage
  - utter_coverageResponse

## whatIsMyDeductible
* whatIsMyDeductible
  - utter_deductibleResponse

## doYouLoveMe
* doYouLoveMe
  - utter_iLoveYou

## areYouSingle
* areYouSingle
 - utter_letUsTalkAfter

## whyLibravos 1
* whyLibravos
 - utter_aboutLibravos
* affirm
 - utter_emailListServeSignUpYes

## whyLibravos 2
* whyLibravos
 - utter_aboutLibravos
* deny
 - utter_emailListServeSignUpNo

## whereDoesMoneyGo
* whereDoesMoneyGo
 - utter_charityMoney

## howToMakeClaim
* howToMakeClaim
 - utter_claimHelp


## curiosityAboutBot
* curiosityAboutBot
 - utter_botCapabilities

