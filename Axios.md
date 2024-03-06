# Axios
A brief description of what this project does and who it's for

## Post request
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
