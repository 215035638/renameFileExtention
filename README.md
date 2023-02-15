#rename all the files with extension hpp to the extension h

filenames = ["program.c", "stdio.hpp", "sample.hpp", "a.out", "math.hpp", "hpp.out"]

new_filenames = [i.replace('.hpp', '.h') for i in filenames]

print(new_filenames)
