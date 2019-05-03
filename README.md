# Crispr-Cas9

This webpage represents a short overview of CRISPR-Cas9 and other gene editing methods, created as an assignment for the [Computational Genomics (2018/2019) course][course], which is a part of the Master studies at the [School of Electrical Engineering][school], [University of Belgrade][uni].

The page can be accessed [here][page].

## Dependencies

This page was developed with [Jekyll][jekyll]. Below are the steps needed to run the page locally, and they represent a shorter version of the [full description][full_description]. 

In order to run a local version of the page, you need [Ruby][ruby] 2.1 or higher. To check the Ruby version you have installed, run the following command.

```
ruby --version
```

If you cannot execute the command, or if the version is less than 2.1, you will need to [install Ruby][ruby_download].

Next, you will need [Bundler][bundler]. If you don't have it installed, run the following command.

```
gem install bundler
```

Navigate to the root directory of this project and run the following command to install other dependencies.

```
bundle install
```

Finally, to run the server that will host the local version of the page, execute the following command from the root directory of the project.

```
bundle exec jekyll serve
```

The local version of the page can be seen with a browser at the following address.

```
http://localhost:4000
```

[course]: https://github.com/vladimirkovacevic/gi-2019-etf
[school]: https://www.etf.bg.ac.rs/
[uni]: https://www.bg.ac.rs/
[page]: https://nikolapeja6.github.io/gi-crispr-cas9/
[jekyll]: https://jekyllrb.com/
[full_description]: https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll
[ruby]: https://www.ruby-lang.org/
[ruby_download]: https://www.ruby-lang.org/en/downloads/
[bundler]: https://bundler.io/
