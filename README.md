## GOLD DIGGER

### v1.0

Gold, the metal itself is the inspiration behind this app. Trends rise and fall. Fads come and go. For thousands of years, if something has remained constant is the respect of gold as the store of value. 

The app, available on [gold-digger.glitch.me](https://gold-digger.glitch.me/), uses okta sign in, self service registration, and multi factor authentication. After a successful sign in, the app greets the user with their name. The app lets the user check live gold price on [goldprice.org](https://goldprice.org/live-gold-price.html).  At the moment of writing this document, the price of gold is $1,292.13 per ounce, in case you are interested. The user needs to pay a small fee of $1000 for getting an image of a rock checked by an expert. The app is using Paypal for payment processing. The user then is requested to enter an email address and rock image url. The email address is where the report will be sent. For best results, the rock image url needs to be a high-resolution image. The user can use reputed image sharing platforms such as, [imgur.com](https://imgur.com/). The user can then submit the data. The data is securely stored in a mongodb cluster on cloud.mongodb.com. After data is received, the payment is verified and the data is reviewed by a reputed expert chosen by the gold-digger.glitch.me team. The report is then sent to the user. 

The app has been built with great care and each part of it has been tested painstakingly, to say the least. It uses okta platform as it is a leading provider of identity and access management solutions. Mongo db was chosen because of its ease of use, resiliency, and a-class performance. For hosting, glitch.com was chosen due to its excellent project management features. On the front-end, it uses a poised background and Montserrat font from google fonts to ensure an enchanting user experience. 

A number of challenges were encountered during development. The first one was due to not mentioning `appBaseUrl` while creating the oidc object. It was missing in the documentation and was resolved after a brief discussion with HODR, okta. The second one was a `redirect_uri` issue and was resolved after going through a well-written [knowledge base article](https://support.okta.com/help/s/article/The-redirect-uri-parameter-must-be-an-absolute-URI).

The developer considers the app a great accomplishment as it will help people in the mining industry in reducing the cost of gold extraction and also gold enthusiasts. Gold extraction is an expensive business. Using this app means expert advice can be taken from remote locations and there is no need for the expert to be on site. The app will also provide a lot of freelancing opportunities for gold experts. 

Important lessons were learned in the course of the development of the app. Various features of okta platform were explored and admired. The documentation was explored in depth. Each feature of the platform is well documented. The developer of the app has great admiration for the multi factor authentication that's in use in gold digger. 

In the next versions, machine learning will be added to the app to ensure there is an option of automated report generation. Tensorflow will be used for this purpose. The app will present option to the users for manual or automated review. In the future, the gold-digger.glitch.me team will aim to reduce the time required for manual review. 