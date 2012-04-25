# 0x10c Standards Committee #

The 0x10c Standards Committee is a fully community driven organization working towards a series of standards for application development for the DCPU-16 within 0x10c.

## Directory Hierarchy ##

### ABI ###
This directory contains the standards and proposals regarding the Application Binary Interface.

### ASM ###
If you want to write DCPU-16 assembly (probably the case), this is where to look. It contains standards about the syntax and has information for assemblers and compilers.

### FS ###
This directory contains the standards and proposals regarding the File System(s) used by the DCPU-16.

### LIB ###
In here go all specifications and proposals for the layout and implementation of libraries.

### NET ###
Anything about networking goes in the net folder.

### HW ###
Anything about hardware components and communicating directly with hardware components goes in here.

### MISC ###
In this directory goes everything that does not fit in the other directories defined above.

### TESTS ###
Tests for software that can be used to ensure standards compliance.


## Procedures and Naming Standards ##

If you have a proposal, idea or comment regarding upcoming or new standards, you can make an issue about it.

From these issues, a Draft named Draft\_\<Subject\>.xml will be created using Pull Requests, with the XML format as defined in RFC 2629.

When the community agrees on the draft being a standard, and the game is expected to not collide with the standard in a later stage, the draft will be renamed Standard_\<Subject\>.xml .

New versions of a standard must be submitted as a new draft, if this draft becomes a standard it must contain a reference to the superseded standard which is subsequently updated with a reference to the new version.

## Voting ##

Voting times will be based on their importance and impact:

### LOW IMPORTANCE ###
LOW IMPORTANCE votes are votes for minor changes such as naming standards and file formats. Expected time: 15-30 minutes.

### HIGH IMPORTANCE ###
HIGH IMPORTANCE votes are votes for major changes such as method call conventions. Expected time: At least 24 hours, to give people across the world enough time to vote.


## Community ##

With pull requests you can propose changes to drafts or create new drafts.

The issues section should be used to comment on the documents and to suggest changes to make them better.

Everything that is not directly about the standards should go to  
[#0x10c-dev](irc://irc.freenode.net/#0x10c-dev) @ FreeNode.net

You can discuss the ideas, drafts and standards via IRC:  
[#0x10c-std](irc://irc.freenode.net/#0x10c-std) @ FreeNode.net
