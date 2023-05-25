# SocialNetworkApi

## Description

The SocialNetworkApi is a powerful application that allows users to share their thoughts, react to friends' thoughts, and create a friend list. It provides an API for a social network that utilizes a NoSQL database, making it capable of handling large amounts of unstructured data efficiently.


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


## Walkthrough Video

The following ia a walkthrough video that demonstrates the functionality of the social media API. 


https://drive.google.com/file/d/1zmgibEyCDs3WqvLeNo29x9lYoNPYQysr/view


## License

MIT License