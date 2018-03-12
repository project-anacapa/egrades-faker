# egrades-faker

Generate random egrades roster data using Ruby Faker library

The format resembles the format of files downloaded from the eGrades
application used by faculty at UCSB to get their course rosters.
Since the data is all fake, you can test applications without
violating FERPA.

To use:

```
./egrades.rb --count 20

./egrades.rb

./egrades.rb --count 20 > roster.csv
```

