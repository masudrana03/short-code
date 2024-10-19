# VS Code
This thing all about vs code.


## This Scrion is for General Use

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Snipped](https://marketplace.visualstudio.com/items?itemName=JeffersonLicet.snipped)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Bootstrap IntelliSense](https://marketplace.visualstudio.com/items?itemName=hossaini.bootstrap-intellisense)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [Bootstrap 5 Quick Snippets](https://marketplace.visualstudio.com/items?itemName=AnbuselvanRocky.bootstrap5-vscode)
- [Format Selection As HTML](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.format-selection-as-html)


- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Bootstrap 5 Quick Snippets](https://marketplace.visualstudio.com/items?itemName=AnbuselvanRocky.bootstrap5-vscode)
- [Bootstrap 5 Quick Snippets](https://marketplace.visualstudio.com/items?itemName=AnbuselvanRocky.bootstrap5-vscode)



## This Scrion is for LAMP Stack

List Of extention:
- [Auto Import - ES6, TS, JSX, TSX](https://marketplace.visualstudio.com/items?itemName=NuclleaR.vscode-extension-auto-import)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)


## This Scrion is for MERN Stack

List Of extention:
- [Auto Import - ES6, TS, JSX, TSX](https://marketplace.visualstudio.com/items?itemName=NuclleaR.vscode-extension-auto-import)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
- [VSCode React Refactor](https://marketplace.visualstudio.com/items?itemName=planbcoding.vscode-react-refactor)












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
```


