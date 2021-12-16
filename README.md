# Deep-Thoughts

Deep Thoughts is a social media web application that allows users to post "thoughts" online, comment on other thoughts as "reactions", as well as adding friends.

This application leverages JWT to enable user authentication. This allows users to post on their own profile, build up a friend base, and provide permissions not accessible to guests.

# Usage

When opening the application, there is a nav bar at the top to sign up or login. Create an account using a name, email, and password, or login using email and password.

Click on the form box to start typing a "thought" and use the submit button to post.

To react to another user's thought, click on their thought to expand. Below, you will see a reaction form to type in your comment.

![image](https://user-images.githubusercontent.com/85508030/146411233-a6c6cfb4-b8ef-4beb-bb3d-b4611d6bb4ae.png)

On a user's right hand side of their profile, you can see their friends as well as a button to add them as a friend.

Click on the homepage to view a timeline of historical thoughts and reactions.

## Usage

Clone the repository onto your local device.

From the root of the directory run the following in your terminal: 

```
npm init -y
npm install
```

Ensure all npm dependancies are installed correctly.

Then, run the following:

```
npm run develop
```

This command should use concurrently to start the backend server as well as the front end client view. A success message should appear in the terminal that GraphQL is running and the client side view should be found at [http://localhost:3000/](http://localhost:3000/).

## Technologies Used
<ul>
  <li>React</li>
  <li>Express</li>
  <li>GraphQL</li>
  <li>MongoDB</li>
  <li>JSON Web Token</li>
</ul>

## Created By
Jason Grossman

Git Hub Repository is located [here](https://github.com/jasongrossman/deep-thoughts).

Deployed on Heroku [here](https://radiant-fortress-66671.herokuapp.com/).
