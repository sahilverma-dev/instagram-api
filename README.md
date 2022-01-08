![Logo](https://res.cloudinary.com/practicaldev/image/fetch/s--eDGqtKKM--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ze18u472x2gsdd1speqx.jpg)

# Instagram API

An express api which gives data about instagram posts and users.

## Installation

Clone this repo, install all packages with npm and start the server.

```bash
  git clone https://github.com/theviralboy/instagram-api
  cd instagram-api
  npm i
  npm start
```

## API Reference

#### Get instagram post

```http
  end_point/post/${postId}
```

| Parameter | Type     | Description                        |
| :-------- | :------- | :--------------------------------- |
| `postId`  | `string` | Instagram post id eg:`CYa0_SRtUrf` |

#### Get instagram user profile

```http
  end_point/user/${username}
```

| Parameter  | Type     | Description                            |
| :--------- | :------- | :------------------------------------- |
| `username` | `string` | Instagram username eg:`sahilverma.dev` |
