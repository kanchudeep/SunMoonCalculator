# SunMoonCalculator
A very simple Sun/Moon calculator without using JPARSEC library.

This is a Swift port of the excellent [ephemerides (in Java)](http://conga.oan.es/~alonso/doku.php?id=blog:sun_moon_position) by Tomás Alonso Albi.

For specified observer date/time and location (Geodetic: longitude/latitude), following information is calculated:
- **Sun**
  - Rise, set, noon (transit) time
  - Azimuth, elevation and transit elevation angles
  - Distance
- **Moon**
  - Rise, set, transit time
  - Azimuth, elevation and transit elevation angles
  - Distance
  - Age
  - Moon illumination (percentage)
  - Moon position angle of axis, bright limb angle and paralactic angle
  - Moon phase

## Usage
See `example.swift`.
