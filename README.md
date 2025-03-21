Known Places Toolkit Help Documentation
=======================================

Overview
--------

The Known Places Toolkit is a web-based tool that allows users to plot and manage known places on a map. Users can add, view, and delete locations, as well as upload and download location data in JSON or CSV format.

The downloaded files will be in a format that is usable for the import into Pro WFM via the Data Import Tool.

Features
--------

*   **Map Display:** Interactive map with Google Satellite and OpenStreetMap layers which supports zooming and panning.
*   **Add Locations:** Plot points on the map with custom names, radius, locations, and validation orders.
*   **Upload/Download Data:** Upload location data from JSON or CSV files and download the current data as a CSV file.
*   **Search:** Search for locations by name.
*   **Clear Table:** Clear all locations from the table and map.

How to Use
----------

### Adding Locations

To add a Known Place you can either use the Search function or Manual Plot function.

#### Search Address:

*   Enter the address including Street Number, Street Name, Suburb, State and Postcode or enter the latitude,longitude
*   Click the Search Address button or press Enter.
*   Fill in the fields within the control panel.
*   Adjust the radius as necessary
*   Click the "Add Known Place" button to add the location to the map and table.

#### Manual Plotting:

*   Click on the map to place a marker. NOTE: You can click around the map to move the marker and adjust the radius as necessary.
*   Fill in the fields within the control panel.
*   Click the "Add Known Place" button to add the location to the map and table.

#### Automatic Plotting:

*   When you upload a data file, the locations will be automatically plotted on the map and added to the table.

### Searching for Locations

*   Enter a Name, or part of a Name in the search bar.
*   The table will filter to show only locations that match the search query.

### Viewing and Deleting Locations

*   **View:** Click the "View" button next to a location in the table to center the map on that location.
*   **Delete:** Click the "Delete" button next to a location in the table to remove it from the map and table.

### Uploading Data

*   Click the "Upload" button.
*   Select a JSON or CSV file from your computer.
*   The JSON file should be in the format that is received when downloading known places from SDM in the response.json file.
*   The CSV file should be in the format that matches the Data Import Tool template for Known Places import.
*   The locations from the file will be plotted on the map and added to the table.

### Downloading Data

*   Click the "Download" button.
*   A CSV file containing the current locations will be downloaded to your computer.
*   The CSV file will match the Data Import Tool template for Known Places Import.

### Clearing the Table

*   Click the "Clear Table" button.
*   Confirm the action in the prompt.
*   All locations will be removed from the map and table.

Notes
-----

*   Ensure that the JSON or CSV file format matches the expected structure for successful uploads.

### CSV File Format

*   The CSV contains a header row
*   The mandatory columns in the file are:
    *   Name, Latitude, Longitude, Radius, Location Path, Validation Order
*   The optional columns in the file are:
    *   Description, Accuracy, Wi-Fi Networks
*   Location Path, Validation Order and Wi-Fi Networks fields contain comma separated list of values and is required to be in quotes.

Disclaimer: This is not a supported product by UKG. There is no guarantee that this application will function as intended. Use at your own risk.
