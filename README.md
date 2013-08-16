lsf-guides
==========

Print+Web guides for Love ◦ Sex ◦ Fur.

These are intended to be guides for distribution both through print and online.
The guides can cover any sort of topic in brochure-format that LSF would cover.
The online versions will be in <code>site/</code> and the print versions will be
in <code>print/</code>.

## Contributing

We welcome contributions of all sorts!  Here are just a few ways you can help
out:

* Make changes to the guide
  * You can submit a pull request, though see the Making Changes section below.
  * You can [email](mailto:submit@adjectivespecies.com) us with a change you'd
    like to make if you don't want to deal with git, or don't want to be seen as
    a contributor (you can remain anonymous).
* File an issue ([emailed](mailto:submit@adjectivespecies.com) issues are also
  welcome!).
* Review pull-requests

### Making Changes

If you have an idea to contribute, please feel free to fork and submit a pull
request!  However, we have a few requests before you do so.

* **Number One Most Important** - Please maintain parity between online and
  print versions of guides if they exist!\*  If you would like to submit an idea 
  only for someone else to write up for you, please only modify the 
  outline.markdown file in the online directory.  This means that, if you want 
  to contribute directly to the guides, you will need to be familiar enough with 
  HTML and the tool used for print guides to contribute your idea to both!  They
  should be fairly straight-forward.
* **Number One Point Five Most Important** - Always edit the outline first, even
  if you submit a pull request with changes to print/online versions.  Parity
  applies to the outline as well! Separate bullet point because it's important.
* Please try to maintain maximum column width of 80 characters and indentation
  of 4 spaces within HTML.\*\*  Just keep it clean :o)
* In order to maintain consistency in the printed version, your pull request may
  be rejected with an explanation in a comment rather than an annotation on
  code.  That's the problem with a graphical editor!
* Write up a short description of your changes in the form of a blog-post in the
  \_posts directory for every pull request, if you can (we will if not), so that
  the change-log can be updated with what you've accomplished!

The guides are [Jekyll](http://jekyllrb.com) projects, so you'll need to have
that to QA your changes.  Additionally, guides will be made available in print
(though we're working on settling on the best tool for that purpose).

\* Initial branches won't have this be the case, of course.

\*\* Sensible defaults are included for Vim in the file as such: `textwidth=80
expandtab tabstop=4 shiftwidth=4 fo=tc spell`.

### Filing Issues

If you notice something that is wrong or that could be improved within a guide,
feel free to file an issue!

* **Numer One Most Important** - Information must be factually accurate!  Please
  fact-check and file an issue flagged as a bug with inaccuracies!
* Information should be presented in a positive manner.  If something comes off
  as shaming, offensive, or hurtful, file an issue against it.
* Guides should be pertinent to the fandom.  They should be fun, interesting,
  and worth sharing!  You can file issues against dry language and lack of
  pertience to furry.

### Reviewing Pull-Requests

You can also review proposed changes by going over the open pull requests for
the project.  All of the bullet points in the previous two section are valid
things to check.  That is, check both to make sure that parity is maintained
between online and print versions (if applicable), as well as making sure that
information is factually accurate.  Additionally, you should be able to QA the
changes - this means cloning the branch, installing Jekyll to check the web
version, and making sure that the print version is also accurate in the tool of
choice as well as the PDF!  All branches should have at least two reviews before
they're merged.

## License

All guides are licensed under a Creative Commons Attribution-ShareAlike 3.0
Unported license.
