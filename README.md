# Contacts app
Contacts application similar to the one you can find in your smart phone.
This prototype can be taken as a base, screenshots and video on the page gives you a good idea about the application's look and feel: https://www.behance.net/gallery/119373967/Contacts-UIUX-App-Redesign

But as long as you fulfil all the functional requirements, you may adjust graphical design to your liking, you may use one or all of the following resources as inspiration:
- https://www.behance.net/gallery/136417375/contacts-app-(light-and-dark-view)
- https://dribbble.com/shots/10605728-Pharmacy-App-Calendar-the-list-of-contacts/attachments/2360143?mode=media
- https://dribbble.com/shots/17361502-Contacts-Autenti-web-app/attachments/12482886?mode=media
- https://dribbble.com/shots/18909456-Airplan-Contacts

## High level requirements
- User should see a list of contacts in the main view
- User should see a list of recent calls 
- User should be able to access contact details page (all contact's data)
- User should be able to create new contact
- User should be able to delete contacts one by one
- User should be able to edit contact details and save them
- User should be able to search/filter contacts by any detail
- User should be able to paginate through the contact list
- User should be able to email individual contact easily
- User should be able to call individual contact easily
- User should be able to see individual contact street address visualised on the map

## More specific implementation requirements
- The main front-end technology is to be selected from: Angular, React, or React frameworks, e.g., Gatsby or Next.js
- Use server-side search/filter/sorting
- Use server-side pagination
- Create reusable components
- Use Tailwind CSS for styling
- Write unit tests
- Make informed decisions. Use what you think is suitable for e.g., state management, making HTTP requests, rendering the map.
- Make it look nice, try to match the theme of the app and the content, but don't go over the top (don't spend more than a few hours)
- This is a great opportunity to express your creativity, so make sure the app reflects your strengths, for example:
  - Make it look super nice visually if you are a graphical designer at heart, and we may forgive you for the messy code 😄.
  - TDD adept? Cover it with tests thoroughly, we won't care if it comes out ugly in this case 😂.
  - Frontend architect? Surprise us with the project structure and architectural decisions, make Uncle Bob proud of you 👍!
  - Have any other superpower(s)? Now is the time to show them off!

## API endpoints
There are 2 API endpoints, for contacts and for history, and this is the base URL for the API:
https://64a6ab2a096b3f0fcc803d56.mockapi.io/:endpoint

### Contacts entpoint
Get list of contacts:
```http request
GET /contacts
```

Get individual contact details:
```http request
GET /contacts/:id
```

Add new contact:
```http request
POST /contacts
```

Edit existing contact:
```http request
PUT /contacts/:id
```

Delete existing contact:
```http request
DELETE /contacts/:id
```

### History endpoint
Get list of history entries:
```http request
GET /history
```

Get individual history entry:
```http request
GET /history/:id
```

Add new history entry:
```http request
POST /history
```

Edit existing history entry:
```http request
PUT /history/:id
```

Delete existing history entry:
```http request
DELETE /history/:id
```

### Search/filter, sorting and pagination
Information on how to use search/filter, sorting, pagination and some other features of the API with great code examples is available here: 
https://github.com/mockapi-io/docs/wiki


## Delivering the result
Create a GitHub repository for your solution, make a live demo available (GitHub pages, Vercel, Netlify), and send us links to both source repository and the deployed app.
And don't forget to give a star to this repository if you've had fun implementing the App!

