# microfrontend tools

Several tools to help development , build and deployment of microfrontend web applications.

## Requirements

- npm and Node.js


## Import module

- Execute :

```
npm install microfrontend-tools --save
```

- Or manually add this to your package.json dependencies:

```
"dependencies": {
    "microfrontend-tools": "1.0.0"
}
```

## Usage

```
import microfrontendTools from "microfrontend-tools";
var urlHelper = new microfrontendTools.UrlHelper();
var locationBasePath = urlHelper.getLocationBasePath();
console.log('locationBasePath: '+locationBasePath);
```

You will see in your browser log, something like :

```
locationBasePath: http://localhost:8080
```

or in production environment:

```
locationBasePath: http://my-awesome-web.com
```

