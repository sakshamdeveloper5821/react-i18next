This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

[![video](video_sample.png)](https://www.youtube.com/watch?v=9NOzJhgmyQE)

[watch the video](https://www.youtube.com/watch?v=9NOzJhgmyQE)

## using with locize

We added our translation management [locize.com](http://locize.com).

InContext Editing:

- [locize-editor](https://github.com/locize/locize-editor)

i18next Backend: loading translations, save new segments during runtime

- [i18next-locize-backend](https://github.com/locize/i18next-locize-backend)

last used: sets a timestamp on every key touched -> safely remove old/unused keys

- [locize-lastused](https://github.com/locize/locize-lastused)

You will find your project informations like projectId and apiKey on your locize projects settings. (Signup add a new project for testing).

Set projectId and apiKey in `/src/i18n.js`.

## start

```bash
# npm start
```

open `http://localhost:3000?locize=true` to open your application with the locize incontext editor.
