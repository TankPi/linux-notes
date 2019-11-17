- **pwd** Print Working Directory - ie. Where are we currently.
- **file** obtain information about what type of file a file or directory is.
- man <command>
    Look up the manual page for a particular command.
- man -k <search term>
    Do a keyword search for all manual pages containing the given search term.
- /<term>
    Within a manual page, perform a search for 'term'
- n
    After performing a search within a manual page, select the next found item.
- * - represents zero or more characters
- ? - represents a single character
- [] - represents a range of characters

## chmod
chmod has permission arguments that are made up of 3 components
- Who are we changing the permission for? [ugoa] - user (or owner), group, others, all
- Are we granting or revoking the permission - indicated with either a plus ( + ) or minus ( - )
- Which permission are we setting? - read ( r ), write ( w ) or execute ( x )

# Regular Expressions
- . (dot) - a single character.
- ? - the preceding character matches 0 or 1 times only.
- * - the preceding character matches 0 or more times.
- + - the preceding character matches 1 or more times.
- {n} - the preceding character matches exactly n times.
- {n,m} - the preceding character matches at least n times and not more than m times.
- [agd] - the character is one of those included within the square brackets.
- [^agd] - the character is not one of those included within the square brackets.
- [c-f] - the dash within the square brackets operates as a range. In this case it means either the letters c, d, e or f.
- () - allows us to group several characters to behave as one.
- | (pipe symbol) - the logical OR operation.
- ^ - matches the beginning of the line.
- $ - matches the end of the line. 
