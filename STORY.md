# Discount Ascii Warehouse story

This is an **unusual** kind of changelog, which I decided to call "story". Instead of listing only changes in code, I also comment the development process. The goal of this file is to make it easier for the application review team to evaluate my steps.

## 1st hour of work

1. Quick overview of backend code
2. Testing server on Postman
3. Building minimal docs on Postman for reference
4. Git: initialize git, gitignore, commit server code and start branch `boilerplate`

## 2nd hour of work

1. ESLint: extend airbnb and ignore server files
2. Webpack: install React and ES2015 loaders

I though of saving this hour by using a generator tool like `create-react-app`, but that wouldn't be compatible with the idea of this coding challenge, which is to add frontend code to an existing codebase along with server code. `create-react-app` is meant to create a standalone app. In a green field project, I would suggest to the client to separate concerns (server and frontend) because it's more maintainable.