# Linux
All Linux need comand:



## Run deb file

Run .dev file:

```bash
  sudo dpkg -i /path/to/yourfile.deb
```
<!-- 
Using bower:

```bash
  bower install axios
```

Using jsDelivr CDN:

```bash
  <script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```

Using unpkg CDN:

```bash
  <script src="https://unpkg.com/axios/dist/axios.min.js"></script>
``` -->

<!-- 
## Post request

Post Request:

```javascript
const formData = new FormData();
formData.append('key', value);

axios({
    method: 'post',
    url: '{{ route('route.name') }}',
    headers: {
        'Content-Type': 'multipart/form-data',
        'X-CSRF-TOKEN': $('meta[name="csrf-token"]').attr('content')
    },
    data: formData
})
.then(function(response) {
    console.log(response.data);
})
.catch(function(error) {
     console.log(error);
});
```

```javascript
axios({
    method: 'post',
    url: '{{ route('route.name') }}',
    headers: {
        'Content-Type': 'multipart/form-data',
        'X-CSRF-TOKEN': $('meta[name="csrf-token"]').attr('content')
    },
    data: {
        key: value
    }
})
.then(function(response) {
    console.log(response.data);
})
.catch(function(error) {
     console.log(error);
});
```

Get Request:

```javascript
const formData = new FormData();
formData.append('key', value);

 axios({
    method: 'get',
    url: '{{ route('route.name') }}',
    params: formData
})
.then(function(response) {
    // Handle the success response
    console.log(response.data);
})
.catch(function(error) {
    // Handle any errors
    console.error(error);
});
```

```javascript
 axios({
    method: 'get',
    url: '{{ route('route.name') }}',
    params: {
        key: value
    }
})
.then(function(response) {
    // Handle the success response
    console.log(response.data);
})
.catch(function(error) {
    // Handle any errors
    console.error(error);
});
``` -->


