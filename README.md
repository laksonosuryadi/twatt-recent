# twatt-recent

List of **tweet** routes:

|Route | HTTP Method | Description |
|------|-------------|-------------|
|`/tweet/search/:q` | GET | Search tweet based on what you type in the ':q' |
|`/tweet/recent` | GET | Display all of your recent tweets ':q' |

##### example usage:
`http://localhost:3000/tweet/search/jokowi`
This will give you all tweets that related to Jokowi.

`http://localhost:3000/tweet/recent`
This will display all of your recent tweets.

<br>
:bulb: All HTTP Methods described above can be executed using a Chrome app named  [POSTMAN](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en).

-----

### :rocket: Usage

With only npm:

```
npm install
npm start
```
