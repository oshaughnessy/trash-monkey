# NAME

trash-monkey - delete old messages from a mailbox



# SYNOPSIS

__trash-monkey__ \[--nodelete\] \[--verbose\] _cutoff-date_ _mailbox_ \[ _mailbox_ ... \]

__trash-monkey__ --version

__trash-monkey__ --help

__trash-monkey__ --man



# DESCRIPTION

You specify the cutoff-date and give the name of the mailbox (more than one
can be named).  The script will lock each box, remove all the messages
older than that, and then unlock it.  The maximum age can be specified
in many ways:  '24 hours ago', 'yesterday', 'Jan 1 2003', ....  See
Date::Manip for a list of all possible options.



# SEE ALSO



Date::Manip, Mail::Box, http://perl.overmeer.net/mailbox/



# AUTHOR

Copyright (c) 2003-2013 O'Shaughnessy Evans <shaug-github @ wumpus.org>

https://github.com/oshaughnessy/trash-monkey
