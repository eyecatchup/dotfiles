My personal dotfiles
--------------------

Based on 10+ years on the console and the web.

--

#### More, more, more..

If you're interested in (more) dotfiles, a great starting point is here: <https://dotfiles.github.io/>.

--

#### About `.gitkeep` files

Note that the (empty) `.gitkeep` files just exist to let Git *keep* (track of) directories that'd be empty otherwise. This is required because Git's index, by design(!), [cannot handle empty directories](https://git.wiki.kernel.org/index.php/Git_FAQ#Can_I_add_empty_directories.3F). 

> Also note, that `.gitkeep` is not a documented feature of Git but rather a convention created by the Git community. In fact, the file could be called anything.
>  
> That being said, some recent discussions suggest that `.keep` should be preferred over `.gitkeep` - as the former is agnostic to Git, whereas the latter is specific to Git. And, secondly, because the `.git` prefix convention should be reserved for files (and directories) that Git **itself** uses.

--

#### License

Released under the [Creative Commons Zero v1.0 Universal](http://choosealicense.com/licenses/cc0/) license.