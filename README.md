# DroneSurveyPlanner
This is a LibreOffice Calc spreadsheet designed to help you plan an aerial drone mapping survey mission.

---

## Notes:

1. The formula for calculating image footprint assumes a nadir camera angle (straight down) and is: 
    - Ground distance in X plane = (Altitude / focal length of lens) * X length of camera sensor
    - Ground distance in Y plane = (Altitude / focal length of lens) * Y length of camera sensor
2. All other outputs are calculated based on these dimensions and the other input data
3. Flight time/flying speed is influenced by transect spacing, flying height, and the photo interval.
4. Flying height results in a trade off in coverage vs resolution, and flying higher means faster flight times for the same area to be covered.
