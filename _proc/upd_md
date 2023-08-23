import fileinput,re

for f in fileinput.input(inplace=True):
    print(f)
    print(re.sub(r'^(!.*]\()(\w+_files/)', r'\1/images/\2', f), end='')


