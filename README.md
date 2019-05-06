# Agile Toolkit Server
## Getting Started
From the home directory of the app, run:

`docker-compose build`

followed by: 

`docker-compose up`

The app should be available at [http://localhost:4000](http://localhost:4000) in the browser. 

To seed the session database when first running the app, in localhost:4000 enter

```bash
mutation {
  createSession(data: "oh snap") {
    _id
    data
  }
}
```
