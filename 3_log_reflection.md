The two main issues I identified were:

Inconsistent date formatting: A # sign appeared in the date column after row 17, making the dates difficult to read and interpret.

Repeated information: The data_label column contained the same content throughout the dataset, making it appear redundant.


I used AI to obtain suggestions for cleaning the identified data-quality issues. However, I did not accept every suggestion without checking it.

i have written the code: df[df["date"].astype(str).str.contains("#")]   to solve the problem of # sign
 for the repeated content i have written the code: df["date"].unique()
 

these python codes just helped me get an insight but i have to work and think on my own to get the real answer
