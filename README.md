# ui-webalerts
Javascript library for ui web alerts

## Installation
Implement the following script in <head>
```html
<link rel="stylesheet" href="ui-webalerts.css">
<script src="ui-webalerts.js"></script>
```

## Init ui-webalerts
Use the folling code in your app.js
```javascript
const webalerts = new UIWebAlerts();
webalerts.setIconPath("./res/");
```

## Create ui-webalerts
```javascript

createAlert(type, message, duration);  // default duration is 5000 = 5sec

webalerts.createAlert("success", "This is a success alert");
webalerts.createAlert("info", "This is an info alert");
webalerts.createAlert("warning", "This is a warning alert");
webalerts.createAlert("error", "This is an error alert");
```
