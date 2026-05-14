# findaed (AED Navi)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An open-source web application to locate nearby AED (Automated External Defibrillator) stations in Japan using your device's GPS and display them on Google Maps.

## Demo

[**Live Demo**](https://code4fukui.github.io/findaed/)

## Features

-   Automatically locates the nearest AED stations using your device's GPS.
-   Displays facility locations on an interactive Google Map.
-   Supports multiple languages, including Japanese, English, Chinese, and Korean.
-   Includes data definitions for other public facilities like emergency shelters, medical institutes, and public toilets.

## Setup for Local Development

This project requires a Google Maps API key to run locally.

1.  Obtain a Google Maps API key from the [Google APIs Console](https://console.developers.google.com/projectselector/apis/credentials).
2.  In the `lib/gmap.js` file, replace the placeholder `API_KEY` value with your own key.
3.  Open the `index.html` file in a web browser.

## Data Source

This application retrieves facility data from the [Open Data Portal (ODP) SPARQL endpoint](https://sparql.odp.jig.jp/data/sparql) in Japan.

## Acknowledgements

This project utilizes the `fukuno.js` utility library by Taisuke Fukuno (CC BY).

## License

[MIT](LICENSE)