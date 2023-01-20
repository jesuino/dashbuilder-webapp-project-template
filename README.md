# Dashbuilder WebApp Template

This is a template to get start your Dashbuilder project.

Dashboards can be found in `static` folder and they are copied to `dist` along with Dashbuilder bundle.

## Building

Init the project at least once and:

```
npm run bootstrap
```

Then you can build the project:

```
npm run build
```

You can see the content locally using the `http-server` and accessing `localhost:8000`:

```
npm run server
```

## Creating Dashboards

Create dashboards with extension `dash.yaml`. A sample dashboard can be found in static folder: `hello-dashboard.dash.yaml`. New dashboards can be mapped in `setup.js`.

## Editing Dashboards

To edit your dashboards import your repository in [KubeSmarts](https://start.kubesmarts.org).

## Publishing your work

To publish your work checkout the branch `gh-pages`, delete the current content and copy the content from `dist` to this folder. Add your content, commit and push to branch `gh-pages`.