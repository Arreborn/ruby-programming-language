# SproutScript
This document specifies the file(s) relevant for specific data structures in SproutScript. Please consider the current folder as root for these paths. These are listed in alphabetical order.

## cases/cases.rb 
Defines the nodes used for if-statements (as well as else if, else)
## data/basic_data.rb 
Defines the most basic data nodes such as integers, booleans
## data/complex_data.rb 
Defines complex data such as lists, strings
## data/frames.rb 
Defines frames (used for scope) and syntax trees, mainly used in the parser and complex nodes needing access to variables
## errors/errors.rb 
Creates custom error messages for SproutScript
## functions/functions.rb 
Defines nodes used to create and execute user-defined functions (see also: frames.rb)
## loops/for.rb 
Defines for-loops which can be executed by SproutScript (see also: frames.rb)
## loops/while.rb 
Defines while- and do while-loops (see also: frames.rb)
## nodes/function_nodes.rb 
Defines SproutScripts custom functions such as print, input, test
## nodes/nodes.rb 
Defines construction nodes, responsible for creating a new node from two others - for example, arithmetic nodes, comparison nodes
## parser/parse.rb 
The parser for SproutScript - defines the tokens and rules for the language
## parser/rdparse.rb 
The recursive descent parser given to us in the course, virtually unchanged except for one pass with RuboCop
## projects/ 
Contains complete example projects written in SproutScript
## tests/unit_tests.rb 
Unit test suite for SproutScript, testing all nodes in a vacuum
## tests/.sproutscript_tests/ 
Tests written in SproutScript used during development (hidden folder as it may be interesting for evaluation, but not relevant to end user)
