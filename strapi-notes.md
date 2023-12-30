## Strapi Part-1 : 

Strapi will provide us row data. We will use this data in our fornt-end application. 

Web-site `strapi.io` 

`Note: The best way to learn strapi is that study docs`

We will install strapi by **CLI**.
```js
yarn create strapi-app my-project --quickstart
```

**--quickstart** it will create default database without any option. 

After installing the project it will take me admin pennel.Then i have register.

- `content manager` it means it will manage our content.
- `content type builder` it means potita content er type kemon hobe sata build kora. 
- `Media Library` it user for image,video etc

- `plugins` it meas kono third party package.
- `setting` eikha ne amra bibinno jinis configure korte parbo.


## part-4: Relation

article er sathe tag and categories er connection ase.
author er connection ase potita articale er sathe data ase. ei goli strapi nije thake drill kore.

for creating slug we need to use **UID** field. Then slug take attach kore ditehobe name er sathe. slug meang url er / porer name.

example : 
name :            slug
web               slug

Now we will add relation: for that we will add another field.

suppose amra categories er shathe relation korbo.


akta categories er under a multiple item thakte pare abar akter article er sathe multiple categories thakte pare.

Relation korar age amake chinta korte hobe then relation korate hobe. content er relation amake age theke fix korte hobe.


Article er shate user er relation set korte hobe. 
article ei filed er name dilam author > user-permission


akgon user many article likhte perbe. user has many articles.

`note: relation er field goli by default populate hoi na. Ei jonne url a likhte hobe populate=*`

`note: strapi amader k date by default dia dai`

Rest api formate e kaj korbe. 

category goli create kore amra api request patie dekhbo.
pagination ta o thakte hobe. 

`Task : content design korte hobe.`

## part - 5: 
Home page er jonne ami single type nibe.

`note: component goli amader k akti nidisto section er under a implice korte hobe`

## part - 6: postman nia.

login registar button. 






