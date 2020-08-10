Look for files in docs/ directory

https://phy188-288-ucb.github.io/seljak-fall-2019/

To build locally,

    pip install python-markdown-math
    pip install mkdocs

    git clone ...

    cd seljak-fall-2019

    git pull

    mkdocs build
    mkdocs gh-deploy

    # sometimes need to run twice or github won't refresh the CDN cache (or something alike)
    mkdocs gh-deploy


Issues related to the datahub service, shall be filed at

https://github.com/berkeley-dsep-infra/datahub/issues


Adding a lecture note:

1. Upload the file from github to the lecture-notes directory,
2. Add a link to docs/lectures.md; change the file name to match the note.
3. Rebuild and deploy the site (see above)

Adding a homework:

To convert github url to datahub url, use

http://url-to-interact.herokuapp.com

