you'll need to read data from a text file 
using sys.stdin

example:
data = []
for line in sys.stdin:
    data.append(line.strip())


to run, you must use a bash terminal
then type
python filename.py < inputname.txt

^^^ you may need to cd to the correct directory