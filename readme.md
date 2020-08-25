## HTTP to HTTPS redirect

Simple package for http to https redirection for React base application.

### Usage

Wrap your application in the component.
Force redirection will only take place in production. 

```
ReactDOM.render(
  <HttpsRedirect>
    ....
  </HttpsRedirect>,
  document.getElementById('root')
);
```
