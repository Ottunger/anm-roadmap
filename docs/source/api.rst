API
===

You can find the whole API of ANote Music server here:
`API <https://app.anotemusic.com/api-doc/index.html>`_. Feel free to start spending time around!

Concepts
--------

The main objects in the API are:

* SongContract: The main item on which users can place bid, acquire shares, and ultimately receive dividends
* Song: The songs within SongContracts
* Artist: The artists involved in songs
* BidShare: A bid of a user to receive ownership of a SongContract at the end of an auction
* AskShare: An order of a user to exchange ownership of a SongContract
* OwnerShare: The ownership of a user on a SongContract

Endpoints
---------

* PROD: `<https://api.anotemusic.com/api/v1>`_
* TEST: `<https://api-test.anotemusic.com/api/v1>`_

Authentication
--------------

The API accepts tokens emitted by AWS Cognito as a bearer token.

You can enroll an account then do a login with the following parameters.

* PROD: region: 'eu-central-1', cognitoUserPoolId: 'eu-central-1_bZn2tVIU2', clientId: '4d8at0err04mrjp91glgvuo4i8'
* TEST: region: 'eu-central-1', cognitoUserPoolId: 'eu-central-1_p8DDGNY7k', clientId: 'b5mse79hn12pg6mr1cfcc5ili'
