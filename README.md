*Monticello repository for directory-based Monticello packages enabling the use of git, svn, etc. for 
managing Smalltalk source code.*


## Installing

The current version of **FileTree** has been tested in GemStone2.4.4.1 (GLASS 1.0-beta.8.7.1), Pharo1.3 and Squeak4.3 and is 
expected to work in Pharo1.4:

 * [GemStone installation](https://github.com/dalehenrich/filetree/tree/master/doc/GemStoneInstall.md)
 * [Pharo installation](https://github.com/dalehenrich/filetree/tree/master/doc/PharoInstall.md)
 * [Squeak installation](https://github.com/dalehenrich/filetree/tree/master/doc/SqueakInstall.md)

### IMPORTANT NOTE:

If you already have FileTree installed in your image before 6/12/2012 
(SHA ece58e82dc803001578f7d40c2c6a61fbb0066c2)
you will need to:

1. move **MCMethodDefinition>=** to a different category (`comparing`)
2. upgrade to the new version FileTree
3. manually edit (or use method version browser) to eliminate the `true ifTrue:[true]` code 
in **MCMethodDefinition>=**.

## Contributing

Here are some guidelines on contributing to the project:

 * [use personal fork](https://github.com/dalehenrich/filetree/tree/master/doc/Contribute.md#forkme)
 * [use dialect-specific branching](https://github.com/dalehenrich/filetree/tree/master/doc/Contribute.md#branching)
 * [use topic branches](https://github.com/dalehenrich/filetree/tree/master/doc/Contribute.md#topicbranches)
 * [unit tests in separate repository](https://github.com/dalehenrich/filetree/tree/master/doc/Contribute.md#tests)

## Travis CI Status

**pharo1.3 branch** : [![Build Status](https://secure.travis-ci.org/dalehenrich/filetree.png?branch=pharo1.3)](http://travis-ci.org/dalehenrich/filetree) 

**pharo1.4 branch** : [![Build Status](https://secure.travis-ci.org/dalehenrich/filetree.png?branch=pharo1.4)](http://travis-ci.org/dalehenrich/filetree)

**pharo2.0 branch** : [![Build Status](https://secure.travis-ci.org/dalehenrich/filetree.png?branch=pharo2.0)](http://travis-ci.org/dalehenrich/filetree)

**squeak4.3 branch** : [![Build Status](https://secure.travis-ci.org/dalehenrich/filetree.png?branch=squeak4.3)](http://travis-ci.org/dalehenrich/filetree) 

**configuration branch** : [![Build Status](https://secure.travis-ci.org/dalehenrich/filetree.png?branch=configuration)](http://travis-ci.org/dalehenrich/filetree) 
