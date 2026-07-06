# Turning messy data into clean data -- my Excel cleanup process 

## Steps I followed:

1) Looked at the data first to figure out what actually needed fixing

2) I used auto-fit column widths so everything was readable

3) Removed extra brackets "()" from client names

4) Used PROPER() + TRIM() to remove extra spaces and keep names properly capitalized

5) Split department and city into separate columns using text to columns

6) Filled blank payment/revenue cells with "NA" instead of leaving them empty

7) Used IFERROR() to fix the hashtag#DIV/0! errors in profit margin

8) Cleaned up formatting - headers, filters, the works


