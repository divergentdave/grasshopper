# Grasshopper

### This is a work in progress. This software is in alpha status and is not ready for production use ###

**Description**:  Put a meaningful, short, plain-language description of what
this project is trying to accomplish and why it matters. 
Describe the problem(s) this project solves.
Describe how this software can improve the lives of its audience.

Other things to include:

  - **Technology stack**: Indicate the technological nature of the software, including primary programming language(s) and whether the software is intended as standalone or as a module in a framework or other ecosystem.
  - **Status**:  Alpha, Beta, 1.1, etc. It's OK to write a sentence, too. The goal is to let interested people know where this project is at. This is also a good place to link to the [CHANGELOG](CHANGELOG.md).
  - **Links to production or demo instances**
  - Describe what sets this apart from related-projects. Linking to another doc or page is OK if this can't be expressed in a sentence or two.


## Dependencies

Grasshopper needs [Elasticsearch](http://www.elasticsearch.org/) as a backend to store data for geocoding. 
The services layer runs on the Java Virtual Machine (JVM). The project is being built and tested on JDK 8, but JDK 7 and OpenJDK versions 7 and 8 should also work. 

Describe any dependencies that must be installed for this software to work. 
This includes programming languages, databases or other storage mechanisms, build tools, frameworks, and so forth.
If specific versions of other software are required, or known not to work, call that out.

## Building

To build the project, `sbt` is required. Please refer to the [installation instructions](http://www.scala-sbt.org/0.13/tutorial/Setup.html) for your platform

Grasshopper is a multi-module sbt project, each project has a specific task and usually represents a Microservice. 

Once installed, from the project directory run the following:

```
sbt
```

From the sbt prompt, type `re-start` to fork a JVM and start the geocoding service.

## Configuration

If the software is configurable, describe it in detail, either here or in other documentation to which you link.

## Usage

Show users how to use the software. 
Be specific. 
Use appropriate formatting when showing code snippets.

## How to test the software

To run the tests, from the project directory: 

```
sbt test
```

This will run unit and integration tests. The integration tests will stand up a temporary Elasticsearch node, no additional dependencies are needed.  

## Known issues

Document any known significant shortcomings with the software.

## Getting help

Instruct users how to get help with this software; this might include links to an issue tracker, wiki, mailing list, etc.

**Example**

If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.

## Getting involved

This section should detail why people should get involved and describe key areas you are
currently focusing on; e.g., trying to get feedback on features, fixing certain bugs, building
important pieces, etc.

General instructions on _how_ to contribute should be stated with a link to [CONTRIBUTING](CONTRIBUTING.md).


----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)


----

## Credits and references

1. Projects that inspired you
2. Related projects
3. Books, papers, talks, or other sources that have meaniginful impact or influence on this project 
