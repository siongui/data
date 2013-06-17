# data format of dictionaries

All files are utf-8 encoded.

## format of dict-books.csv

row = [cell1, cell2, cell3, cell4], each row represents one dictionary.

1. cell1 (b_lang): "C" means chinese dictionary, "E" means non-chinese dictionary.

2. cell2 (b_num): id of the dictionary. Each dictionary has a unique value.

3. cell3 (b_dict): name of the dictionary.

4. cell4 (b_dictauthor): name and author of the dictionary.

## format of dict_words_1.csv and dict_words_2.csv

row = [cell1, cell2, cell3, cell4, cell5, cell6, cell7], each row represent represents the explanation of a pali word in one dictionary.

1. cell1: number of the row.

2. cell2: the same as cell1 of dict-books.csv

3. cell3: the same as cell2 of dict-books.csv

4. cell4: fuzzy spelling of the pali word

5. cell5 and cell6: the pali word. The first character of the cell may be upper-case.

6. cell7: the explanation of the pali word in one dictionary.
