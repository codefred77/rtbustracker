# rtbustracker
Real Time Bus Tracker Demo

## Description
This project is intended as a demonstrations of a web app that tracks the location of
public transportation buses live.

It uses the Massachusetts Bay Transportation Authority (MBTA) API to obtain bus locations
and displays them as an animation on Google maps.

The starting base code was taken from one of MITxPro's Proffesional course coding excercises.
This excersice maps one fixed route: Route 1.

This refactoring adds the capability to request the tracking of any route. The user enters
the route to track.

## How to run
To run:
1. Download all of the files in the repository
2. Edit the file index.html and modify the following line as indicated
    (replace REPLACE_WITH_YOUR_KEY with your own user key)

    <script src="http://maps.google.com/maps/api/js?REPLACE_WITH_YOUR_KEY"></script>

3. Load the index.html file into your browser
4. Enter the route you want to track (for demonstartion purposes only routes 1 and 9 are valid)
5. Hit the "Enter" button


NOTE: If you want to add more valid routes, check with MTBA which numbers are valid and modify
      the matrix variable validRoutes in mapanimation.js to include the routes you want to track

## Future improvements
- If possible query the MTBA API for valid routes and add them to the validRoutes matrix
- Modifications will be needed to allow the user to enter a string as opposed to a number for
  route names that contain strings (example: CS1, CS2,etc.)

## License