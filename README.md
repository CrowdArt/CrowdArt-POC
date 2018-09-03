# ca2

* [Axios](https://www.npmjs.com/package/axios)
* https://medium.freecodecamp.org/quick-guide-to-understanding-and-creating-reactjs-apps-8457ee8f7123
* [React-bootstrap](https://react-bootstrap.github.io/getting-started/introduction/)
* freeformater.com
* https://restfulapi.net/security-essentials/
* [Introduction to Distributed Systems](https://hackernoon.com/a-thorough-introduction-to-distributed-systems-3b91562c9b3c)
* [Dweb: Building Cooperation and Trust into the Web with IPFS](https://hacks.mozilla.org/2018/08/dweb-building-cooperation-and-trust-into-the-web-with-ipfs/?utm_source=dev-newsletter&utm_medium=email&utm_campaign=aug30-2018&utm_content=dweb)
* [Material Kit React](https://demos.creative-tim.com/material-kit-react/#/)

#### Material UI
* npm install @material-ui/core
* npm install @material-ui/icons
* npm install typeface-roboto --save
* npm install enzyme@^3.0.0
#### React Router
* npm install --save react-router react-router-dom react-router-config

### Create Build
* npm run dev:build:server
* npm run dev:server

## Firebase
Open a terminal window and navigate to or create a directory for your site

Sign in to Google:

$ firebase login
Initiate your project:

$ firebase init
Add your static files to your deploy directory (the default is public)

Deploy your website:

$ firebase deploy

```service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write;
    }
  }
}
```
```
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write;
    }
  }
}
```
## Axios
* [Axios](https://www.npmjs.com/package/axios)
* npm install axios --save
