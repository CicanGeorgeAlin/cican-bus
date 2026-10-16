# CICAN BUS

A mobile-first Progressive Web App foundation for Dublin Bus stops and real-time departures.

Project owner: CICAN GEORGE ALIN  
Hosting target: GitHub Pages  
First milestone: connect official transport data and verify real-time arrivals.

## Current status

The first interface foundation includes a responsive dark app-like layout, PWA manifest and icon, basic app-shell caching, and local-device favourites for entered stop numbers.

Important: this version does not display live arrival data. Stop entry and favourites are interface groundwork only; they are not validated stop lookups.

## Official data

Start with the National Transport Authority developer portal: https://developer.nationaltransport.ie/

The portal requires registration to access APIs. Before connecting the browser to a feed, verify the current API version, authentication method, CORS/browser support, usage terms, and GTFS-Realtime response format. Never commit a private API key to public client-side code.

## GitHub Pages

Repository: https://github.com/CicanGeorgeAlin/cican-bus  
Expected site URL: https://cicangeorgealin.github.io/cican-bus/

Enable GitHub Pages in Settings > Pages and select the main branch if it is not already configured.

## Planned next steps

1. Verify the deployed site and PWA manifest.
2. Confirm current NTA endpoints and authentication requirements.
3. Load official stop and route data.
4. Connect real-time estimates with clear freshness and error states.
5. Test on Android and desktop.

CICAN BUS is an independent project and is not an official Dublin Bus or National Transport Authority app.