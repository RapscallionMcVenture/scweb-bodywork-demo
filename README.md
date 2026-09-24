# Bodywork Practice Demo

Standalone training demo for Sam Clements Web. This copy retains realistic bodywork content and imagery for practising ordinary website updates. It is not a live business website. No bookings, payments or enquiries are possible.

## Local preview

From this directory run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/ in your browser. Stop with Ctrl+C. No build or dependencies are needed. All navigation uses static HTML files.

The demonstration form uses made-up entries only, prevents submission, and displays a local message. Its controls are disabled without JavaScript; a content security policy also blocks form destinations and scripted network connections. Google Fonts remains an external appearance resource. Video playback is disabled.

Every page has a training banner and noindex. Crawling remains allowed so search engines can read noindex; this is not access control.

This demo uses its own GitHub repository: https://github.com/RapscallionMcVenture/scweb-bodywork-demo. Any future Netlify deployment must use its own separate demo project. No Netlify project is connected and no deployment has been performed. Do not connect it to the original business project.
