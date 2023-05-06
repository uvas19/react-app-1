# Level 0 - Practice & learn react app beginner

## install & validate if you have node & npm
```
node -v
npm -v
npx -v
```

```bash
npx create-react-app app-2
cd app-2
```

## Development 
```bash
npm start
```

## Production

```bash
npm run build
serve -s build
```

### troubleshooting
if you see the following try sudo

```
code EACCES
npm ERR! syscall mkdir
npm ERR! path /usr/local/lib/node_modules/serve
npm ERR! errno -13
```

```bash
sudo npm run build
serve -s build
```

### Useful Links

[create react app ](https://create-react-app.dev/docs/getting-started/)

[create react deployment](https://create-react-app.dev/docs/deployment/)

[learn react](https://react.dev/learn)
