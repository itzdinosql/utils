# Utils:
# Capitalize Function in JS
---

A `capitalize` function in JavaScript takes a string and capitalizes its first letter while converting the rest of the string to lowercase.

**Function**

```javascript
function capitalize(value) {
    if(typeof value !== "string") return "";
    return value.trim().charAt(0).toUpperCase() + value.trim().slice(1).toLowerCase();
}
