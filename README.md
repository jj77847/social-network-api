## social-network-api

## Table of Contents

- [social-network-api](#social-network-api)
- [Table of Contents](#table-of-contents)
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Packages used](#packages-used)
- [Links](#links)

<a name="description"></a>

## Description

Build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. I'm using Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the [Express.js](https://www.npmjs.com/package/express) and [Mongoose](https://www.npmjs.com/package/mongoose) packages, I'm going to use a JavaScript date library or the native JavaScript `Date` object to format timestamps.

<a name="user-story"></a>

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

<a name="technologies-used"></a>

## Technologies Used

#### Languages

- JavaScript
- JQuery

#### Packages used

- Node.Js
- Express
- MongoDB
- Mongoose
- Date Fns

<a name="links"></a>

## Links

GitHub: https://github.com/jj77847/social-network-api

Video:
