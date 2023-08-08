echo "Hello, World" prints Hello, World to the standard output
echo "\"(Ôo)'"
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail that outputs the last lines of file
head that outputs th first few lines
head -n 3 iacta | tail -n 1 when you chain these commands together, head will show the first three lines of iacta, and then tail will display the last line from that output, which will be the third line of the original iacta file
ls -la >> ls_cwd_content
tail -n 1 iacta | tee -a iacta
find . -type f -name "*.js" -exec rm {} +
find . -type d | wc -l
ls -t | head -n 10
sort | uniq -u
grep "root"
grep -c
grep -A 3
grep -v
grep '^[[:alpha:]]'
tr 'Ac' 'Ze'
tr -d
rev for reverse words
awk -F: '{print $1, $6}' /etc/passwd | sort
find . -empty | sed 's|.*/||'
find . -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 1 | rev | LC_ALL=C sort -f 
