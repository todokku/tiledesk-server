== 

npm run test:int

== Run specific test ==

npm test --  --grep 'Subscription./requests.create'



mocha trigger.js   --grep 'Trigger.EventEmit'

mocha trigger.js   --grep 'Trigger.EventEmitCreateRequest'


mocha ./test/authenticationJwt.js    --grep 'AuthenticationJWT.signinJWt-Project-external-user-YESAudYesSubject'