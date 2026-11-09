# Sweet Auburn Historic Trail

An interactive walking map of the Sweet Auburn Historic Trail in Atlanta, Georgia. It was made for the Georgia Tech School of City and Regional Planning Sweet Auburn Studio (Fall 2026), as part of our plan recommendations for the Historic Trail and its wayfinding signs.

**Live map:** https://kaamah8494.github.io/sweet-auburn-trail/

## Purpose

The Historic Trail links the landmarks of Sweet Auburn into a single walk along Auburn Avenue, from Woodruff Park to the Atlanta BeltLine. Each proposed trail sign carries a QR code. Scanning it opens this map at that stop, so visitors can see where they are, hear the story of the site and find their way to the next stop.

## Features

- The full trail route with eleven numbered stops
- A live location dot that follows the visitor as they walk, once they allow location access
- A short history of each stop, with a Listen button that reads it aloud
- Walking directions to any stop through Google Maps
- Stop-specific links for the QR codes on each sign, for example `?stop=4` opens the Municipal Market

## Trail stops

| Stop | Site | Address |
|---|---|---|
| 1 | Woodruff Park | 91 Peachtree St NW |
| 2 | APEX Museum | 135 Auburn Ave NE |
| 3 | Sweet Auburn Works | Auburn Ave NE near Jesse Hill Jr Dr |
| 4 | Municipal Market | 209 Edgewood Ave SE |
| 5 | John Wesley Dobbs Park | Auburn Ave NE at Fort St NE |
| 6 | Haugabrooks | 364 Auburn Ave NE |
| 7 | Ebenezer Church | 407 Auburn Ave NE |
| 8 | MLK Center | 449 Auburn Ave NE |
| 9 | King Birth Home | 501 Auburn Ave NE |
| 10 | HDDC | Auburn Ave NE |
| 11 | Beltline Eastside Trail | Atlanta BeltLine, Old Fourth Ward |

## How it was built

The map was built in R with the `leaflet` and `htmlwidgets` packages, and the QR codes were generated with the `qrcode` package. Stop names, coordinates and histories are kept in `stops.csv`, so the map can be updated by editing that file and rebuilding. The site is hosted on GitHub Pages.

## Sources

Stop histories draw on the Atlanta History Center, the National Park Service, Clio and Wikipedia. The trail route follows the Historic Trail map developed by the Sweet Auburn Studio team.

## Note

This is a student concept prepared for a planning studio. It is not an official product of the City of Atlanta, the National Park Service or any organization named on the map.
