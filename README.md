Gitignore
=========
This is a small tool that helps you to merge [github/gitignore](http://github.com/github/gitignore) presets into your .gitignore file

Install
-------
    git clone git://github.com/github/gitignore
    export GITIGNORE_REPO="`cd gitignore; pwd`"
    git clone git://github.com/tilltheis/utilities.git
    ln -s "`pwd`/utilities/gitignore" /usr/local/bin/gitignore
    echo "Please add the following to the end of your ~/.bashrc (~/.profile on Mac):"
    echo "export GITIGNORE_REPO='${GITIGNORE_REPO}'"
