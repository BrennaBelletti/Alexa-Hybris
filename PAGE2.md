#### Ingredients
## 2. Create the Skill <a id="title"></a>
<hr />


1. Login to [developer.amazon.com](https://developer.amazon.com) and click Alexa, then Alexa Skills Kit.
1. Create a new Skill called **Shoe Butler** with invocation name ```shoebutler```.
1. Paste in the [IntentSchema.json](./speechAssets/IntentSchema.json) :

```
{
  "intents": [
    {
      "intent": "MyIntent"
    },
    {
      "intent": "HelloIntent"
    },
    {
      "slots": [
        {
          "name": "Name",
          "type": "AMAZON.LITERAL"
        }
      ],
      "intent": "UserNameIntent"
    },
    {
      "intent": "AMAZON.HelpIntent"
    },
    {
      "intent": "AMAZON.StopIntent"
    },
    {
      "intent": "AMAZON.CancelIntent"
    }
  ]
}


```

1. Paste in the [SampleUtterances.txt](speechAssets/SampleUtterances.txt) :

```
    MyIntent what sizes are in stock
```

Pause here and leave this browser tab open.

#### Continue to the next step

 * [Part 3 - Create the Lambda function](./PAGE3.md#title)


<hr />
