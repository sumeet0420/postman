# Created by Sumeet Agrawal

## Command to run the postman scripts
### npm install -g newman-reporter-html
### npm install -g newman-reporter-htmlextra
### newman run Trello.postman_collection.json --global-var "key=YOURKEY" --global-var "token=YOURTOKEN"

```
newman run Trello.postman_collection.json --global-var "key=YOURKEY" --global-var "token=YOURTOKEN" --reporters junit,cli,html --reporter-junit-export --reporter-html-export
```

'''
newman run Trello.postman_collection.json --global-var "key=YOURKEY" --global-var "token=YOURTOKEN" --reporters junit,cli,html,htmlextra --reporter-junit-export --reporter-htmlextra-export
```

```newman run reqres_users.postman_collection.json --reporters junit,cli,html,htmlextra --reporter-junit-export --iteration-data person.json
```
