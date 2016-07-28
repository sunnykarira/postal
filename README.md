# **Postal**

*An **Alexa** skill based on *[ASK] **Alexa Skills Kit** that adds up an Alexa Skill onto **Amazon devices** ( Echo, Echo Dot, Fire TV ) to utter pincode of cities or locations in India.

# Pre-Requisites

## NodeJS

```bash
	sudo apt-get install nodejs
```

## Setting up a lambda function

> https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/developing-an-alexa-skill-as-a-lambda-function

1. Make sure you select us-east-north-virgina as your region.
2. Select a blueprint (Alexa-skills-color-expert).
3. Add Application ID.
4. Select runtime as NodeJS.
5. Put the code (index.js)
6. Role as lambda_basic_execution_role.
7.  You are now done with setting up you lambda function.

## Configuring App in Alexa Developer console

1. Make sure you have Amazon developer account with the same Email-ID as you AWS account.
2. Select Alexa.
3. Add a new Alexa Skill.
4. Provide the intent (INTERACTION MODEL) of the application (intent.js).
5. Put in some sample utterances. - (Sample Utterances.txt)
6. Define a test model.
7. You are done setting up your postal code application.


# Features

- Simplified handling of requests and generating responses
- Asynchronous handlers supported
- Returns Pincode of locations and cities as speech output.
