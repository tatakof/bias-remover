# bias-remover

level 0
  - zero shot this  https://es.wikipedia.org/wiki/Falacia and prompt to use them to explain the falacies and remove them from the statement. 
  - make a small app/website to use it

level 1
 - make a twitter bot to use it. https://developer.twitter.com/en/docs/tutorials/how-to-create-a-twitter-bot-with-twitter-api-v2

level 2
  - make mixtral generate statements filled with each of the falacies, and then to explain why the statement is a falacy. This dataset can be statements and explanations per each  
    falacy, or statements with many falacies. Then train a qlora on top of mixtral or llama2.
  - use zero shot on top of qlora. Maybe compress the list of falacies before zero shoting them.
  - check how the heck to host an os llm with a qlora (https://medium.com/@yuhongsun96/host-a-llama-2-api-on-gpu-for-free-a5311463c183 or exprimir some aws free credits or 
    something else)

