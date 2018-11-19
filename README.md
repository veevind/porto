# porto
portfolio


#Start the project
```
cd MY_PROJECT
middleman server
```

The preview server allows you to build your site, by modifying the contents of the `source` directory, and see your changes reflected in the browser at: `http://localhost:4567/`

To get started, simply develop as you normally would by building HTML, CSS, and JavaScript in the `source` directory. When you're ready to use more complex templates, simply add the templating engine's extension to the file and start writing in that format.

For example, say I am working on a stylesheet at `source/stylesheets/site.css` and I'd like to start using Sass. I would rename the file to `source/stylesheets/site.css.scss` and Middleman will automatically begin processing that file as Sass. The same would apply to CoffeeScript (`.js.coffee`), Haml (`.html.haml`) and any other templating engine you might want to use.

Finally, you will want to build your project into a stand-alone site. From the project directory:

```
middleman build
```

This will compile your templates and output a stand-alone site which can be easily hosted or delivered to your client. The build step can also compress images, employ JavaScript & CSS dependency management, minify JavaScript & CSS and run additional code of your choice. Take a look at the `config.rb` file to see some of the most common extensions which can be activated.
