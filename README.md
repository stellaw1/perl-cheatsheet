# Perl Cheatsheet

## Introduction
 - interpreted language, interpreter reads and executes code instead of target
   machine
 - dynamic scripting language, type and values are both dynamic, type checking
   done at runtime
 - powerful text processing
 - used to write Common Gateway Interface (CGI) scripts that allow web servers
   to communicate with external programs
 - powerful string parsing

## Setup
 - download Perl interpreter
 - '.pl' file extension
 - start with #! Shebang line pointing to interpreter's binary

## Syntax
``` perl
$variable = "string123";

my $localVariable = "local variable";
our $globalVariable = "global variable";

@array = (1, 2, 3);
@array[1];

%dictionary = ('hash', 1, 'key', 'value');
%dictionary{'key'};

if (5 > 10) {
    print "hi";
}
unless (5 < 10) {
    print "hi";
}

sub SomeFunction {
    my ($arg1, $arg2) = @_;
    print $arg1 + $arg2;
}
SomeFunction(1, 2);

if ($text =~ /cool/) {
    ## regex is built in
}
```

Render code: 
``` perl app.pl```
