############ReadData#############
1-if data was text -> call read_doc and will return all elements (words,charachters and evrey thing) in the text document
   need words and label -> call read_doc twice

2-if data was csv file -> call read_csv and will return all elemnts in the first column
   need words and label -> add return words.iloc[:,1]

3-if data was XML file -> enter read_xml -> access needed attributes -> call read_xml
 
