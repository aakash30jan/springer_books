Original scrapper by chris-hamberg/springer_books.
Follow the original instructions from there.

OR

In your terminal(or command prompt): 

1)  Get the book list and edit it to remove the books/rows you don't want to download.
    ```
    wget https://github.com/aakash30jan/springer_books/raw/master/Free%2BEnglish%2Btextbooks.xlsx
    ```
2)  Get and run the scraper which downloads all the books from your list. 
    ```
    wget https://raw.githubusercontent.com/aakash30jan/springer_books/master/scraper.py
    python3 scraper.py
    ```
