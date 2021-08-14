# IBM-Watson:

I using IBM watson assistant website to create a chatbot.

The website : https://www.ibm.com/sa-en/cloud/watson-assistant Before you start must be create an account.

# Create an assistant:

1- Click the Create assistant.

2- Name the assistant.

3- Click Create assistant.

![p1](https://user-images.githubusercontent.com/85816257/128745739-0ab60d5b-038f-4f9d-add6-0785e74ad431.png)


# Create a dialog skill:

1- Click the My first assistant tile to open the assistant.

2- Click Add dialog skill.

3- Name the skills.

4- Click Create dialog skill.

5- Click to open the skill you just created.

![p2](https://user-images.githubusercontent.com/85816257/128745909-c8d96407-adc7-4f3f-a50a-bd2bc4c9e041.png)

# Add intents from a content catalog:

When you open the skill, you land on the Intents page.

![p3](https://user-images.githubusercontent.com/85816257/128746167-6da24112-57f9-4d12-90ed-e961b0cd5700.png)

Add training data that was built by IBM to your skill by adding intents from a content catalog. In particular, you will give your assistant access to the General content catalog so your dialog can greet users, and end conversations with them.

1- From the skill menu, click Content Catalog.

2- Find General in the list, and then click Add to skill.

3- Open the Intents tab to review the intents and associated example utterances that were added to your training data. You can recognize them because each intent name begins with the prefix #General You will add the #General_Greetings and #General_Ending intents to your dialog.

![p4](https://user-images.githubusercontent.com/85816257/128746377-73babcf0-58e7-4531-a8aa-c5ce08e94805.png)

![p5](https://user-images.githubusercontent.com/85816257/128746550-dcccf627-2d79-4e3b-a8d3-d519f28f7618.png)

# Build a dialog:

1- From the Skills menu, click Dialog.

2- Two nodes were added to the dialog for you:

Welcome: Contains a greeting that is displayed to your users when they first engage with the assistant.

Anything else: Contains phrases that are used to reply to users when their input is not addressed by any of the existing dialog nodes.

3- Click the Welcome node to open it in the edit view.

4- Replace the default response with the text, Like "Welcome to the Watson Assistant".

5- Click Close to close the edit view. you can add node, start to type #General_Greetings. Then, select the #General_Greetings option, Add the response text, Good day to you! then try it .

![Screen Shot 2021-08-09 at 9 16 57 PM](https://user-images.githubusercontent.com/85816257/128754923-786c017d-be83-49a0-92f4-1ff20badc3cc.png)


# Integrate the assistant:

![p8](https://user-images.githubusercontent.com/85816257/128748901-a6e97cdd-956c-415a-a3c8-bdfeca23445e.png)

From the Integrations section, click the Preview link, Then click the URL that is displayed on the page.

![Screen Shot 2021-08-15 at 12 09 36 AM](https://user-images.githubusercontent.com/85816257/129460071-b596e10a-4c91-4b94-b2d5-83fa313d89db.png)





