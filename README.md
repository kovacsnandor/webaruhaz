# webaruhaz
[this repo](https://github.com/kovacsnandor/webaruhaz)

# json szerver
[json szerver](https://github.com/typicode/json-server)

- install: `npm install -g json-server`
- Create a db.json file with some data:
```json
{
    "products": [
        {
            "id": "lb2nwj9fwoyagkwrk4m",
            "name": "Áru 1",
            "price": 1500,
            "quantity": 97,
            "isInStock": true
        },
        {
            "id": "lb2nwj9fjecpanfnjjn",
            "name": "Áru 2",
            "price": 2500,
            "quantity": 15,
            "isInStock": true
        },
        {
            "id": "lb2nwj9fdb8ek3sxbti",
            "name": "Áru 3",
            "price": 3500,
            "quantity": 25,
            "isInStock": false
        },
        {
            "id": "lb2nwj9fp5esy079kel",
            "name": "Áru 4",
            "price": 4500,
            "quantity": 10,
            "isInStock": true
        }
    ]
}
```
- start: `json-server --watch db.json`