# longest_word_Python
# A code that helps to find the longest word in a paragraph of text.

text = ("Lorem ipsum dolor sit amet consectetur adipiscing elit Aliquam rhoncus facilisis consequat "
        "Nam ultricies quis dolor vitae placerat Integer in ante sit amet eros egestas porttitor Phasellus "
        "semper lectus dapibus volutpat consequat Duis gravida sit amet ipsum eget maximus Mauris condimentum "
        "sem porta aliquet mi ut fringilla erat Nunc maximus magna ac volutpat mattis tellus mi dignissim "
        "dolor vel rutrum nulla risus quis quam Vestibulum ante ipsum primis in faucibus orci luctus et ultrices "
        "posuere cubilia Curae; Integer ut urna nunc Morbi id iaculis augue "
        "Proin malesuada scelerisque massa et tristique Sed blandit nisi nunc nec euismod nulla dignissim eu "
        "Pellentesque consequat mauris eu augue blandit quis consectetur urna convallis Phasellus eget molestie "
        "libero ac hendrerit eros Quisque ut tellus sed metus finibus dictum Nullam rhoncus purus ac finibus "
        "placerat sapien sapien maximus nunc a tempor lorem mauris eu eros Integer gravida est eget lacinia "
        "aliquam Phasellus sem urna varius ac quam a fringilla vehicula neque Duis faucibus purus arcu ac "
        "vehicula mauris lacinia quis Nunc vel dolor non ex luctus efficitur quis in leo Sed vehicula lectus sit "
        "amet ante commodo luctus Etiam ac ullamcorper turpis ac ornare urna "
        "Nulla sit amet posuere eros eget viverra dolor Suspendisse potenti Mauris scelerisque mauris id lectus "
        "auctor ultrices Vivamus sodales malesuada erat in ornare felis auctor id Curabitur at quam pellentesque "
        "pharetra sem a pulvinar magna Integer nisl mi rhoncus eget urna eget posuere accumsan risus In nisi est "
        "condimentum vel ornare sit amet semper ut nunc Nam risus leo maximus eu aliquet non fringilla id ligula In "
        "metus ipsum gravida in lectus eget aliquam egestas ipsum Fusce placerat cursus mi ultrices luctus Maecenas eu "
        "ipsum diam Nullam nec augue a diam rhoncus lobortis at id sapien Ut in erat laoreet porta nunc quis luctus "
        "justo Pellentesque dictum sit amet mauris et sodales Morbi fermentum sem hendrerit hendrerit ex eu laoreet sem "
        "Nam at tristique quam Aliquam erat volutpat Quisque rhoncus augue a luctus hendrerit Pellentesque at eros "
        "ut nulla volutpat ullamcorper Curabitur varius nisl hendrerit est rhoncus suscipit Duis gravida erat sit "
        "amet nunc maximus laoreet Cras dictum quam eu pellentesque commodo Phasellus non mauris non dolor tincidunt "
        "ultrices et in eros Aenean quis enim mollis aliquet lorem a commodo leo Phasellus elementum quis quam "
        "eget condimentum Nam convallis enim id faucibus ornare augue erat rhoncus eros at vehicula lacus mi sit amet "
        "leo Mauris libero mi commodo blandit consectetur et bibendum id magna In hac habitasse platea dictumst "
        "Sed in diam ut neque pretium gravida "
        "Nullam venenatis elit nec quam lobortis nec rutrum justo ullamcorper Pellentesque eleifend lacus elit "
        "nec gravida purus lacinia in Cras imperdiet dui in elementum feugiat est mauris dignissim quam in facilisis "
        "purus lorem vel velit Suspendisse potenti Duis a venenatis enim Vestibulum vitae neque odio Ut eget ex at "
        "libero vehicula faucibus "
        "Integer placerat lobortis sem a ullamcorper nunc pharetra quis Integer id consequat mauris ac rhoncus "
        "purus Nunc sit amet sodales ante eget rutrum odio Nullam elementum pretium velit et facilisis Duis "
        "porttitor quam a pharetra ullamcorper Donec sollicitudin blandit sem ut rhoncus leo feugiat in Morbi quis "
        "dui a massa sagittis mattis Curabitur malesuada eros nec pharetra fermentum diam nulla euismod nulla "
        "rutrum hendrerit mi nisi feugiat est Vivamus diam est iaculis et orci non fringilla hendrerit nulla Etiam "
        "consectetur eros libero a ultrices magna blandit quis Proin eu augue vel ante convallis viverra et sodales "
        "magna Nullam ullamcorper arcu at justo lobortis at malesuada risus gravida Curabitur sapien est tristique "
        "in varius eget consequat a leo ")

x = text.split()
x.sort() #Sorts the text permanently (alphabetically)
print(x) 
longest_word = max(x, key=len)
longest_lword=(len(longest_word))
print("The longest word has " ,longest_lword, " letters.")

# How does it work: the selected text is 
# saved in a variable "text" within the
# brackets like this : text = (...)

# The command .split() will split the
# given text in a variable (specify
# your variable which you want to save)
# , in this case, it is variable
# text, in to a list. .sort()
# command will sort the list
# of words in ascending order
# (that is, A-Z).
# You can see the result by 
# using the print() command.

# To find the longest word
# the command 
# longest_word = max(x, key=len)
# the longest word will be found this way.

# Note: it is possible to find how many 
# letters are there in the longest
# code. The longest word saved in a
# variable needs to be used with
# a function len(variable_longest_word).
