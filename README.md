# CustomViewExample
This is a simple sample project demonstrating how to have Stormpath endpoints working while tailoring the view. 


Sample request to register a new account:

```
http POST http://localhost:8080/register givenName==fooGivenName surname==fooSurname email==foo@email.com password==Pas12345! confirmPassword==Pas12345!
```