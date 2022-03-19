# Discord QA

1. `cd discord-qa`
2. `npm i`
3. `npm start`

Configure the [serve](https://github.com/vercel/serve) static content server's behaviour by 
changing the settings in `serve.json`. With `cleanUrls` set to `true`, the following folder
structures would achive what you're looking for:

```
/
|_ index.html
|_ membership/
|            |_ index.html
|_ pricing/
          |_ index.html

```
```
/
|_ index.html
|_ membership.html
|_ pricing.html

```