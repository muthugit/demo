# American eagle outfitter - Alexa integration - Documentation

## Software development

Test case: [https://docs.google.com/spreadsheets/d/1gkjYJzSdeR6EqiAtOPKdoub1ZSWXH2hk63qQuPnqILI/edit#gid=0](https://docs.google.com/spreadsheets/d/1gkjYJzSdeR6EqiAtOPKdoub1ZSWXH2hk63qQuPnqILI/edit#gid=0) 

---

 **Requirement documents** 

[](https://static.notion-static.com/703e118f428441648209fd2804661695/Utterances_AEO_14_July_2017.docx)

- UX flow charts https://aq6ibu.axshare.com/#g=1&p=link_account_card (PW: 19HotMetal)

[Documents](https://www.notion.so/2901eafd18dd48f3990d40bc08b9620e)

---

## Environments

Development

- Alexa Skill - " **American Eagle Outfitters - Dev** "
  - (id: amzn1.ask.skill.ec5fcfbb-f806-4e00-8cc4-d94598adec55)
- [Mani] Alexa skill invocator lambda - " **AEOAlexaService-Dev** "
  - (ARN: arn:aws:lambda:us-east-1:857597635104:function:AEOAlexaService-Dev)
- [Mu] AcceleratorEngine - " **AcceleratorV2-Dev** "
  - (ARN: arn:aws:lambda:us-east-1:857597635104:function:AcceleratorV2-Dev) note:we do not use space in lambda function

Demo environment

- Alexa Skill - " **American Eagle Outfitters** "
  - (id: amzn1.ask.skill.71d1256a-e47d-425a-b1e3-7a0d13259dad)
- [Mani] Alexa skill invocator lambda - " **AEOAlexaService** "
  - (ARN: arn:aws:lambda:us-east-1:857597635104:function:AEOAlexaService)
- [Mu] AcceleratorEngine - " **AcceleratorV2** "
  - (ARN: arn:aws:lambda:us-east-1:857597635104:function:AcceleratorV2)

# Releases

 **v1.0 - June, 2017** 

Created sample contents for alexa responses

 **v2.0 - 8 Aug, 2017** 

Sent for client verification on 8 Aug, 2017

Change log

1. Changed alexa skill and named as "American Eagle Outfitter" with invocation name "American eagle"
2. Created utterances based on the client document
3. Created intent on the Skill developer site, which can be understandable by AcceleratorV2
4. Created AcceleratorV2 lambda functions to connect with AEO Alexa skill
5. Created and updated sample responses in the Database
6. This version will give the response from the Database (only for AEO)
7. Created appropriate properties file to handle Order status, Product price checker, CMS Contents

 **v2.1 - 10 Aug, 2017** 

1. Updated utterances based on the requirement (UX flow charts https://aq6ibu.axshare.com/#g=1&p=link_account_card (PW: 19HotMetal))
2. Added some commands from Matt and also replied the working and non-working commands in the email
