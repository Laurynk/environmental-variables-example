# environmental variable
1. create a file at the root of the project
```

.env
```
2. inside the .env file add the text:
- you must use `NEXT PUBLIC` or else it will not work
```

NEXT_PUBLIC_FILE = "Digital Design and Development"
```
3. on the page, in between the export and return write the variable:
```
var title = process.env.NEXT_PUBLIC_TITLE
```
4. then in between the main tag, write:
```
(title)
```
5. Make sure `gitignore` file has `.env` inside
- you want to prevent the secret title from being displayed

## BCIT data from Digital Design and Development Diploma
[Digital Design and Development Diploma Courses] ()