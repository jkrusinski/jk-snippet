# JK-Snippet

CLI tool for pushing a local file as a [Bitbucket Snippet](https://confluence.atlassian.com/bitbucket/snippets-719095082.html)

This tool was built while following an [Atlassian](https://atlassian.com) tutorial on creating CLI scripts with Node.js, which can be seen at this [link](https://developer.atlassian.com/blog/2015/11/scripting-with-node/)

## Installation
- Install [Node.js](https://nodejs.org/) and [npm](https://npmjs.org/)
- Run `npm install -g jk-snippet`

## Usage
	snippet [options] <file>
	
	Options:

    -h, --help                 output usage information
    -u, --username <username>  The user to authenticate as
    -p, --password <password>  The user's password 
    
Snippet will prompt for username and password if not declared by an option.    