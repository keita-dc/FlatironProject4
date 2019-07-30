# Taxi in DC -To tip or not to tip, that is the question

## Objectives
Despite the popularity of Uber and Lyft, taxicabs are still relevant today. Unlike Uber or Lyft, taxicabs are able to accept cash, do not require a smartphone for reservations, and are easily identified on the streets. These differences allow taxicabs to remain in demand. Our objective is to analyze the taxi trips data in DC and figure out what determines the fares and tips.

## Contributors
Emefa Agodo and Keita Miyaki

## Dataset
We use "Taxicab Trips Sampling in July 2017" provided by the DC Government, which has 228,611 observations over July 23 to July 30, 2017. After the initial cleaning, we obtained 201,887 observations.

### Data Cleaning
We filter out taxi trips with distance over 100 miles, total fare over 1,000 dollars, or trip duration over two hours, because we aim to analyze taxi trips in DC and adjacent areas but not inter-regional trips. We also filtered out trips with average mileage per minute over 2 (we may see high numbers due to rounding errors of trip duration which is measured in minute, but believe numbers beyond 2 would be unreasonable).

## General Description of Dataset
