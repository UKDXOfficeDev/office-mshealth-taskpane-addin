# Office MS Health Task Pane Addin
Sample which uses an ASP.NET 5 web app as the basis for an Office Add-in. 
The Add-in retrieves data from the MS Health API (Preview) http://developer.microsofthealth.com/cloudAPI which enables access to data from the Microsoft Band.

#Setup
To run the addin sample it is necessary to supply an application client id and client secret for an app which is registered to authenticate against the MS Health API Preview. The full instructions for this can be found here http://developer.microsoftband.com/cloudAPI (click on the Learn More button to access a pdf with instructions). Alternatively, go here https://account.live.com/developers/applications and register an app. This will enable you to access a client id and client secret. The ASP.NET 5 web app uses 'user secrets' configuration to avoid the need to place secrets inside source control. You need to set two secrets up ClientId and ClientSecret. For further details of ASP.NET 5 configuration see http://docs.asp.net/en/latest/security/app-secrets.html  
