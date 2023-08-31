# capitalbikeshare_dataset
Aggregated data from the Capital Bikeshare system (https://capitalbikeshare.com/), what I've done is count the number of trips by day by user type, I'll use this data for a time series project.

The raw data can be freely downloaded from https://capitalbikeshare.com/system-data and the data licence agreement is found at https://ride.capitalbikeshare.com/data-license-agreement

I'll just copy and paste their own description of their datasets:

### Trip History Data
Each quarter, we publish downloadable files of Capital Bikeshare trip data. The data includes:

- Duration – Duration of trip
- Start Date – Includes start date and time
- End Date – Includes end date and time
- Start Station – Includes starting station name and number
- End Station – Includes ending station name and number
- Bike Number – Includes ID number of bike used for the trip
- Member Type – Indicates whether user was a "registered" member (Annual Member, 30-Day Member or Day Key Member) or a "casual" rider (Single Trip, 24-Hour Pass, 3-Day Pass or 5-Day Pass)

This data has been processed to remove trips that are taken by staff as they service and inspect the system, trips that are taken to/from any of our “test” stations at our warehouses and any trips lasting less than 60 seconds (potentially false starts or users trying to re-dock a bike to ensure it's secure).
