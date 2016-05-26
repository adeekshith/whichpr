# whichpr

Find the pull request from commit id

Pull requests have lots of information regarding why the commit is made and approved so knowing which pull request the commit is part of will be very helpful. Sometimes it is more helpful than `git blame`. This script helps you to easily get the pull request from the commit ID (SHA).

## Install
- Clone this repo
- Add symlink `ln -s ~/your-download-path/whichpr/whichpr /usr/local/bin/whichpr`

## Usage
`whichpr <your_commit_SHA>`
`whichpr c3gdt64ye`

## Limitations:
- This only works for Bitbucket at present.
- Shell script is made for Mac only. Need some changes to make it work for other platforms.

Feel free to make a pull request to improve this. Thanks.