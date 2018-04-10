# FontAwesome Plugin for React FileManager
> This is client side plugin and has server side plugin dependency.

#### Dependencies

FileManager: https://github.com/react-filemanager

Back-end Support: https://github.com/themexpert/rfms-plugin-fontawesome


Usage:

```JS
    import initFM from '@themexpert/react-filemanager'
    import FontAwesome from '@themexpert/rfm-plugin-fontawesome'
    
    const openFilemanager = initFM('server');
   
    window.ReactFileManager.registerPlugin(FontAwesome);
    
```
