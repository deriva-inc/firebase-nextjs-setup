This repo is a template for setting up your web app using [NextJS](https://nextjs.org) using [Firebase Hosting](https://firebase.google.com/products/hosting) and [Firebase Cloud Functions](https://firebase.google.com/products/functions).

For change log, please see [CHANGELOG.md](https://github.com/deriva-inc/firebase-nextjs-setup/blob/master/CHANGELOG.md).

## Set-up
- Clone the repository on your system.
```
git clone https://github.com/deriva-inc/firebase-nextjs-setup.git
```
- Install `node` and `npm`/`yarn` if you haven't.
- Go to root directory i.e. `firebase-nextjs-setup`
- Open `.firebaserc` file and change the `your-firebase-project-id` to your actual firebase project ID.
- Go to `functions` folder.
```
cd src/functions
```
- Install dependencies.
```
npm install
```
- Go to root directory.
```
cd ../..
```
- Run `install` script.
```
npm run install
```
- If the script run was successful, you will see a `next` folder generated inside `functions` folder.
- Install `firebase tools` if you haven't.
- Now to test your app locally run `firebase emulators:start` in your root.
- Open a new terminal @ `firebase-nextjs-setup` and run `cd src/app && npm run serve`.
- Your web app should be live on `localhost:3000` and your Firebase Emulators should be live on `localhost:400`.

## LICENSE

Copyright 2020 Deriva

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.