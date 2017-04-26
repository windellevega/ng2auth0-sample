# Angular with Auth0 App

This is my output app upon finishing the [tutorial](https://www.youtube.com/watch?v=i_dHFvi1BJc "Traversy Media Angular 2 and Auth0 Tutorial) of Traversy Media.
Original Output/Source Code is [here](https://github.com/bradtraversy/ngauth0).

This is an Angular app that implements Auth0 platform.

###Tools used
Angular (at least version 2.0)
NodeJS
Auth0

#Setup Project
• Clone this repository on your specified repository

```sh
$ cd <project_folder_name
```
• Install dependencies node modules
```sh
$ npm install
```
•Go inside your project folder
```sh
$ cd <project_folder_name>
```
• Modify `auth.service.ts` inside `src/app/services/` and change Client ID and Domain (refer to your Auth0 client settings).
```Typescript
lock = new Auth0Lock('Client ID', 'Domain', {});
```
• Build Project
```sh
$ npm start
```

