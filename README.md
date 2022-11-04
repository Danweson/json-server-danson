## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
    "events": [
        {
            "id": 1,
            "title": "Event 1",
            "description": "Description 1",
            "category": "sports",
            "date": "April 25"
        },
        {
            "id": 2,
            "title": "Event 2",
            "description": "Description 2",
            "category": "technology",
            "date": "April 22"
        },
        {
            "id": 3,
            "title": "Event 3",
            "description": "Description 3",
            "category": "food",
            "date": "May 25"
        },
        {
            "id": 4,
            "title": "Event 4",
            "description": "Description 4",
            "category": "technology",
            "date": "April 25"
        },
        {
            "id": 5,
            "title": "Event 5",
            "description": "Description 5",
            "category": "food",
            "date": "Dec 05"
        }
    ],
    "dashboard": 
        {
            "posts": 5,
            "likes": 150,
            "followers": 20,
            "following": 50
        },

    "news": [
        {
            "id": 1,
            "title": "News Article 1",
            "description": "New  Description 1",
            "category": "sports"
        },
        {
            "id": 2,
            "title": "News Article 2",
            "description": "Description 2",
            "category": "politics"
        },
        {
            "id": 3,
            "title": "News Article 3",
            "description": "Description 3",
            "category": "sports"
        }
    ],
    "products":[
        {
            "id": 1,
            "price": 3000,
            "description": "Description 1"
        },
        {
            "id": 2,
            "price": 8000,
            "description": "Description 2"
        },
        {
            "id": 3,
            "price": 5000,
            "description": "Description 3"
        }
    ]
}
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
