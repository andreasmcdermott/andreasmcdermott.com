{
  "title": "Blog and Ida improvements",
  "description": "Blog is getting styled and Ida is watching.",
  "categories": ["projects"],
  "tags": ["ida", "blog"]
}

Ida is getting better. I've been able to generate a simple site like this one with a single command in the terminal for some time:

```
$ ida
```

This has worked really well for testing the build process. Today I wanted to add more styling to my blog. 
I'm writing my css in [Stylus](http://stylus-lang.com) which means I have to first build the css file, then I have to rebuild the blog.
This worked, but it was a bit annoying.

So, today I added a new command:

```
$ ida watch
```

This will regenerate the site on file changes. I then start watch using with the [Stylus compiler](https://www.npmjs.com/package/stylus).
Now with every template or style change the whole site is rebuilt and my development workflow has become so much better.

I have a lot of improvements I want to do still, but I'm already happy with where Ida is.