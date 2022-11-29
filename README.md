# OntrackBarcodeReader

this scripts is for scanning barcode with address. CSV file contains barcode with 83709 zipcodes adresses data.  Each record in this zip code has zone attached in the "Name" Column.
The "name" column represent Section for this are 
if you scann bacrode it will extract address from barcode scanned information and query address row in csv file
The output should be address and section.
If address doesn't exist it will populate error message and restart script.
