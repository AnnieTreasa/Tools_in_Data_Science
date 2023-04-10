# Tools_in_Data_Science
## FILES :
### ratings.csv
- contains ratings sorted by time.Ratings go from one to five. Both book IDs and user IDs are contiguous. For books, they are 1-10000, for users, 1-53424.
### to_read.csv
- provides IDs of the books marked "to read" by each user, as user_id,book_id pairs, sorted by time.
### books.csv
- has metadata for each book (goodreads IDs, authors, title, average rating, etc.). The metadata has been extracted from goodreads XML files.
### book_tags.csv 
- contains tags/shelves/genres assigned by users to books. Tags in this file are represented by their IDs. Each book_id has multiple tag_id.The field "count" denotes ‘user records’ (the number of users tagged the given tag_id with the goodreads_book_id).
