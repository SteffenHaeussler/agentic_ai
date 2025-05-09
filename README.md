# Agentic AI Framework

This is a generalized framework for building agentic AI systems for internal question answering.


## Running service manually

To run the service manually in debug mode install the required python dependencies:

`uv install`

You can run the service in dev mode by default:

via fastapi app:
```
make dev
```
and access via [http://127.0.0.1:5000/docs](http://127.0.0.1:5000/docs)

via cli:

```
make run Q="how are you?"
```



## Running service in Docker


```
make up
```

and to shut down the service:

```
make down
```


## Local querying


## API Documentation


## Testing

To run the tests:

`uv run python -m pytest --verbose --cov=./`


## Agent Design

![Agent Design](architecture/agent_design.png)


## System Design

![System Design](architecture/system_design.png)



This is a personal project inspired by my past work, but built independently from scratch. This project is oriented by this[book](https://www.cosmicpython.com/)
