## Gulp config from Grayni  
***
#### Description:  
     Build gulpfile.js for development sites with use
     different libs and frameworks.
     Functions: convert, unites, minify (sass,css,scss in css), js, move in dist-dir.
     Have two browser-servers.
***
### IMPORTANT:  
     Need install **lamp or other local server**.
     Then first 'domain' must input in [app] - root-dir.
     Second 'domain' must input in [dist] - root-dir.
     In hosts-file write domains (mysite,dist) on 127.0.0.1
     or change variables (localhost, localhost2) on your domains and
     change ways root-dir ([app],[dist]). 
     Do not forget install missing pakages-gulp.
***
#### For using create tree:  
    [app]  
      [css]  
      [fonts]  
      [img]  
      [js]  
        custom.js    // you create func  
        libs.js      // gulp-rigger import libs  
      [libs]         // dir bower libs  
      [sass]  
        libs.sass    // @import sass,scss,css  
        custom.sass  // you create sass  
      index.php      // or .html  
***
#### Commands:  
    gulp      => server for develop work (faster) (folder 'app')  
    gulp dist => server for control final result  
    gulp save => easy save app in dist  
    gulp clch => clear cache

