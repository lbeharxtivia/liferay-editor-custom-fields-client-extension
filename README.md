# Liferay Editor Custom Fields - Sample Client Extension

A Liferay 7.4 global JS client extension that initializes your Liferay Editor Custom Fields apps.

## Getting Started
- Open a terminal instance and go to your liferay 7.4 workspace client-extensions folder.
  - If you don't have a client-extensions folder in your workspace, create one. `mkdir client-extensions && cd client exensions`
- Type `git@github.com:lbeharxtivia/liferay-editor-custom-fields-client-extension.git` in your terminal to clone the repo.
- Use yarn to install all the liferay-editor-custom-fields packages you are going to use
- Make sure that the version number corresponds with the minor version of Liferay (e.g. ^74.0.0 for Liferay 7.4)
- For example `yarn add @liferay-editor-custom-fields/image-enhancements@^74.0.0`
- Image Tools is already added. You can remove it if you're not going to use it.
- In src/index.js, import and run the modules. An example is below:

```
import initImageTools from '@liferay-editor-custom-fields/image-enhancements';

initImageTools();
```

## License
MIT Licensed. Copyright (c) Xtivia 2026.
