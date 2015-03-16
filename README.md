# pa-state-budget
Machine-readable format, extracted from PDF of 2015-2016 Pennsylvania State Budget / General Fund

###About
Underlying raw data in machine-readable format powering [this budget dashboard](http://www.portal.state.pa.us/imageserver/budget2015/GBD_2015.html), released by PA Governor Tom Wolf last month. _Note_: Sadly, only the General Fund Line Items Appropriations data was published.


###Process
- Downloaded [PDF](2015-16_Line_Item_Appropriations.pdf) 
- Using [Tabula](https://github.com/tabulapdf/tabula), extract tabular data to CSV.
- Cleaning/formatting, verified import accuracy
- Moved footnotes to 'Notes' column to prevent interferance with numeric columnar calculations
- Row numbers in PDF should match column 'Row' in CSV for comparison

###Format(s): 
- [CSV](PA_Budget-General_Fund_15-16.csv)
- [Google spreadsheet (link)](https://docs.google.com/spreadsheets/d/14yVqUxCbK70aHMW-lKCwfxBYkeUW5glEh_E_zFfBaog/edit?usp=sharing)
