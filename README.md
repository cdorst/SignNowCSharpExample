SignNowCSharpExample
====================

This is a sample application built with C# and WebAPI to demonstrate integration with the SignNow REST API.

## Usage
The sample app uses NuGet to manage dependencies. Please make sure to pull down the packages it depends on

When you can successfully build the solution, start the application so the example API is accessible.

The [RestClient](https://addons.mozilla.org/en-US/firefox/addon/restclient/?src=search) add-on in Firefox or the [Postman](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm) extension in Chrome are good tools for sending JSON payloads to REST APIs. Alternatively, you can also use good ol' CURL commands in a *nix terminal.

### Calling the API
In `SignNowController.cs` there are 3 endpoints you can send JSON to that will get passed to the SignNow REST API via `SignNowApi.cs`. In the `Models` directory you will find classes that encapsulate some of the data structures that get sent to SignNow. 
