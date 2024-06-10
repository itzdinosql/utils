# utils

```javascript
    function mayuscula(value) {
        if(typeof value != "string") return ""
        return value.trim().charAt(0).toUpperCase() + value.trim().slice(1).toLowerCase()
    }
```