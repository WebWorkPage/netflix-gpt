
1) create react app
2) configure tailwindcss
3) Push code to github
     - create a new repo 
     - push the existing repo/ existing app to newly created repo in github from commandLine
3) create Login page

https://github.com/WebWorkPage/netflix-gpt.git

WAYS TO CREATE A REACT APPLICATION :
1) Build react app from scratch - by installing bundler, testing lib, create folder structure, change in script file for dev run on own

2) create-react-app -> install lot of packages , create basic folder structure for react app, install jest lib and setup done 
it uses Webpack bundler behind - does similar job as parcel bundler 
npm run start / npm start - to start dev server

3) Vite -> similar to create-react-app

#features
- Login/Sign Up Page
    - Sign In/ Sign up Form
    - redirect to Browse Page
- Browse page(after authentication)
    - Header
    - Main Movie/Body Content
        - Trailer running in Bg
        - Title & Description on top of Trailer
        - Movie Suggestions
            - MovieLists * N
- NetflixGPT
    - Search Bar
    - Movie Suggestions
        