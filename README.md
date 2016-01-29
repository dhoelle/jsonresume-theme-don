# Don theme

This is a fork from [Kwan Theme](https://github.com/icoloma/jsonresume-theme-kwan) by Nacho Coloma, modified to add a toolsUsed section under each work description.

_Note: At time of writing (Jan 2016), this does not conform to jsonresume spec. However, other people have expressed similar needs ([jsonresume/resume-schema #37](https://github.com/jsonresume/resume-schema/issues/37))._

### To develop your resume

To develop iteratively (either to modify the template, CSS or resume contents) to the following

```
$ git clone https://github.com/dhoelle/jsonresume-theme-don.git
$ cd jsonresume-theme-don
$ npm install
$ grunt watch // watches for less file changes
$ ./serve.js [optional_resume_filename] // Do this in a separate terminal to run the server with the provided resume or a default one
```

Visit [http://localhost:8888](http://localhost:8888) to see the theme in action.

