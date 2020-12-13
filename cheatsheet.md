# Perl one liners
## Replace by processing input line by line
```
perl -pe s/pattern/replacement/
```
Add regex mode flags at the end (e.g. /g etc) if necessary.

## Replace by processing input as one string
```
perl -0777 -pe s/pattern/replacement/
```
Add regex mode flags at the end (e.g. /g etc) if necessary.

# Linkage troubleshooting
objdump -x binary
readelf -d binary
