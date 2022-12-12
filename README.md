## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/elius-w/vercel-backend-blog) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://vercel-backend-blog.vercel.app
2. https://vercel-backend-blog.vercel.app/posts

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
  "posts": [
    {
      "id_user": 1,
      "date": "2022-11-29",
      "imageUrl": "https://i.postimg.cc/tJFwFxQF/08.png",
      "category": "cinema",
      "title": "O novo filme do Spider-man no way home",
      "resume": "Aqui é um resumo do posto: O novo filme do Spider-man no way home",
      "content": "Conteúdo do post do spiderman\n",
      "duration": "7",
      "star": "4",
      "views": "10",
      "status": true,
      "id": 9
    }
  ],
  "user": [
    {
      "id": 1,
      "user": "helio",
      "name": "Helio",
      "surname": "Alves",
      "token": "E10ADC3949BA59ABBE56E057F20F883E",
      "description": "Front-End Dev & UI motion based in Brasília/Brazil, more than 8 years of experience in product development (user interaction, movement, performance, design faithful to design) and creating interfaces with out-of-the-box animations.",
      "ImageProfile": "https://i.postimg.cc/85Rj3ZL3/helio.jpg"
    }
  ]
  }
```

## Reference


1. https://vercel.com
2. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
