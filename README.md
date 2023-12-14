# better-vplan-server

REST API server built with flask, based on the dsbapipy library from [@nerrixde](https://github.com/nerrixde) - will be used in my upcoming custom DSB client.
## Demo


This API is also hosted here: 

https://better-vplan-server.vercel.app/
## API Reference

#### Get full substitution plan

```
  POST /
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `username`| `string` | Your DSBmobile username |
| `password` | `string` | Your DSBmobile  password | 

#### More options will follow soon...


## Run Locally

Clone the project

```bash
  git clone https://github.com/joel-wlf/better-vplan-server.git
```

Go to the project directory

```bash
  cd better-vplan-server
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  flask run
```


## License

This project is licensed under the [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) License.

## Acknowledgements

 - [DSBApi](https://github.com/nerrixde/DSBApi) library
