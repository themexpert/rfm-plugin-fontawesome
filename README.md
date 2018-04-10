# FontAwesome Plugin for React FileManager
> This is client side plugin and has server side plugin dependency.

#### Dependencies

FileManager: https://github.com/react-filemanager

Back-end Support: https://github.com/themexpert/rfms-plugin-fontawesome

#### Installation

`npm i @themexpert/rfm-plugin-fontawesome`

or

`yarn add @themexpert/rfm-plugin-fontawesome`

#### Usage:

> Include `@themexpert/rfm-plugin-fontawesome` in babel loader in your webpack config

```JS
    import initFM from '@themexpert/react-filemanager'
    import FontAwesome from '@themexpert/rfm-plugin-fontawesome'
    
    const openFilemanager = initFM('server');
   
    window.ReactFileManager.registerPlugin(FontAwesome);
    
```
