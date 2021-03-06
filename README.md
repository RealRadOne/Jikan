# Jikan
A simple commandline timestamp logger.  Jikan (時間) is Japanese for time.

## TODO
- [ ] Log [tags]
- [ ] Todolist [~~add~~, start, ~~done~~]
- [ ] STATS 
- [ ] EXPORT [html, csv]

## Build
1. Update `path` and `filename` in `jikan.cpp`
2. Run ` ./build.sh `

## Add path
Add current repository path to `.bashrc` like so:
```
# .bashrc 
    PATH="$PATH:<jikan-repository-path>"
```
Run `source ~/.bashrc` to reload bashrc

Jikan can now be run using `$ jikan`

## Usage
``` 
usage: jikan <command> [<args>]
These are common Jikan commands:

todo list
   add <item>           Adds item
   done <item>          Logs item
   remove <item>        Removes an item

print
   log                  Print log
   todo                 Print todo

print paths
   path                 Show repository path

stats
   stats                Show statistics
```
## References
&lt;ctime&gt; [link](https://www.tutorialspoint.com/cplusplus/cpp_date_time.htm)

