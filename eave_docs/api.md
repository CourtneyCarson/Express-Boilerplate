## Home Endpoint

```
GET /
```

This API endpoint returns a greeting message.

### Path Parameters

None

### Example Request

```javascript
fetch('http://localhost:3000/', {
  method: 'GET',
})
.then(response => response.text())
.then(data => console.log(data));
```

### Example Response

```
"Hello, world!"
```

### Response Codes

**200**: This response code will be returned when the request is successful.

<br />

