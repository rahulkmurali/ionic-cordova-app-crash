# ionic-cordova-app-crash

Crash your app on demand. Created for crash testing.

## Installation

```bash
$ cordova plugin add ionic-cordova-app-crash
```

## Usage

```javascript
cordova.plugins.AppCrash.crash(
    "crash",
    (successResp) => {
        console.log(successResp);
    }, (error) => {
        console.log(error);
    }
);
```

## Collaborators
- [Rahul K Murali](https://github.com/rahulkmurali)

