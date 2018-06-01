---
layout: page
title:  "Starting with Javascript testing"
subtitle: "An introductory guide to Javascript testing"
date:   2018-05-21 21:21:21 +0530
categories: ["Testing"]
---

Javascript is one my favorite languages for writing test cases as setting up project is way easier than any other language.
You need to have Node.js installed in your system. You can follow the steps mentioned in their site for installation process.

Before creating any project we should understand various components related to technology. While creating a project first we should create package.json which is sort of a dependency management similart to maven. In order to create a package.json file, go to the folder where you want to create project and use `npm init`. I prefer using bash as it is simpler and more powerful than command prompt. Once you enter the mentioned command, it'll some of the basic question. You can leave them blank if you want to, they can easily be edited later.

Now that we have our package.json created, it is time for adding dependencies which are required for our project. We are going to install these dependencies as default, devDepencies, or globally.

Use `npm install <package name>` for installing dependency into you project.

Use `npm install -save-dev <package name>`	for installing it as a dev depency into your project.

Use `npm install -g <package name>` for installing it globally.

I usually prefer not to install any of the package globally unless in CLI tool required to run that particular package

Each file which contains test script is called `spec` file. 

## Frameworks

Testing framework provides you the standard and structure to write your test cases. There are many testing framework available in Javascript. In fact this is one of the most exiciting times when ecosystem is filled with new and old frameworks

### MochaJs

Undoutedly, one of the most famous testing framework which has been around for over 7 years. It is very popular among developer, and is mostly a gateway to JS testing for almost everyone. It has very simple usage and can be used for unit or integartion testing.

You can install it by using `npm install --save-dev mocha`

While writing test cases in mocha, each `describe` block can be considered a test suite and each `it` block is a test case. So a usual test case would look like

```javascript
var assert = require('assert');
describe('First test',function(){
	//test suite
	it('Add 2 number',function(){
		//actual test
		assert.equal(2+2,4);
		});
	});

```

Mocha is simple yet powerful framework which offers solution to your daily test case writing process. To read further you can visit their official site [here](https://mochajs.org/).

### Jasmine

Jasmine is yet another popular framework which has been around for 8 years. One of the o