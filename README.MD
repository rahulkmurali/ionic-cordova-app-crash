# ionic-cordova-app-crash

Crash your app on demand. Created for crash testing.

## Installation

```bash
$ cordova plugin add https://github.com/rahulkmurali/ionic-cordova-app-crash.git
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

