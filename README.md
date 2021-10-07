Welcome to the Alaffia DevOps Engineer Challenge!

In this challenge you are going to be assessed on your ability to stand-up infrastructure, build pipelines, and deploy containers by using the most efficient and automated means possible with the help of a wide range of tooling.

This repo contains a very simple API, written in Node, that will serve as the deployment guineau pig for your challenge.

The API serves up (2) routes:

/private - returns a JSON object that contains a hardcarded fact about dogs (who doesn't love dogs :))

/public - performs a fetch to an external API that serves up a random fact about dogs and returns a JSON object with the fact inside. Each time you hit this endpoint the fact changes.

If you are reading this you should have the high-level outcome and detailed steps needed to complete this challenge.

Best of luck!
<br>
<br>
# Getting Started With the App

## Installation

```
npm install
```

## Running the server

```
npm start
```

## Endpoints
 
The server exposes these endpoints: 
- http://localhost:9000/private
- http://localhost:9000/public

## Response Objects
```
[
  {
    "fact": "At the age of 4 weeks, most dogs have developed the majority of their vocalizations."
  }
]
```




