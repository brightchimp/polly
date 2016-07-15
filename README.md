# polly

A hack day project to play with Alexa.

## Setup
The lambda function needs adding to Lambda. First version was a copy & paste
Blueprint from an [AWS guide](https://developer.amazon.com/appsandservices/solutions/alexa/alexa-skills-kit/docs/developing-an-alexa-skill-as-a-lambda-function)

The files in the alexa_config directory get pasted in when creating the Alexa
skill and are also copy paste from an [AWS Guide](https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/registering-and-managing-alexa-skills-in-the-developer-portal)

I installed [Lexi](http://www.heylexi.com/) (£2.99)on an ipad to be able to
speak to Alexa without an Amazon Echo. I also tried
[Roger](https://rogertalk.com/auth/alexa) for Android (free) which I couldn't
get working properly... after setting it up & givin all permissions, I could
find Alexa by handle, but she never seemed to Listen to anything I sent her.

After failing with Roger, I revoked the app's permissions to my Amazon account
(you need to authorize them to speak to Alexa). App access to Alexa can be
managed [here](https://amazon.com/ap/adam)

You can manage Alexa on your device
[here](http://alexa.amazon.com/spa/index.html#welcome) but I didn't do much
as my development skill was automatically enabled on my device (Lexi email
and Amazon email are the same).
