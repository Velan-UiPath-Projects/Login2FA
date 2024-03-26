Objective :

This is a sample use case to login GitHub with 2FA.

Activities used :

UiPathTeam.TwoStepAuthentication.Activities - 2.0.1


Generate Key from Github :


Settings -> Password and Authentication -> Authenticator App -> Setup Key

note down the key


To Generate Key :

UiPath Team -> TwoStepAuthentication -> Get Okta Token

Input : Github Key
Output : Token 
