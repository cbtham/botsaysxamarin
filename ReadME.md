# Xamarin Chat Bot Challenge

Create a Xamarin cross platform app with [Microsoft Bot Framework](https://dev.botframework.com).

Your solution must have the following:

A button.
A webview.
A chat bot. 

## Glue everything together

### Steps

1. Create a Chat Bot (if you already did, skip to step 2, else refer to https://github.com/cbtham/botsays )
2. Refer to this guide to setup Facebook authentication.

   https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-how-to-configure-facebook-authentication

3. Create an empty Xamarin project.
4. Add a button to the MainPage.
5. Add the logic - upon authenticated, navigate to the second page which contains a webview. You can choose your platform of choice.

    https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-auth

6. The webview loads the chat bot. 

Hint: Publish the bot as direct line/webchat to get the iframe URL. The iframe URL should be your webview source.



### Good Luck!!

