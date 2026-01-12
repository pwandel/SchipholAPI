In here the description how to connect the Schiphol API to Power Query from Microsoft

The Power Query itself is part of Microsoft Excel (used to be an Add In) and Power BI.

Due to the pagination (max 20 results per page) trouble was after connecting to load a complete set of data into excel.

The pagination issue is solved via the List.Generate command however trouble was finding the right parameters.

The given M code can be parsed into the Advanced Editor, the thing you need to complete is the

app-id and the app-key, now filled with XXXXX.

Once these have been updated to your credentials it should work.

It will show after refresh the current (today) Departures Amsterdam/Schiphol for KLM into an Excel Sheet 
