## Antec Flux Pro Display Service
A small, lightweight app that runs in the background that gets system cpu and gpu temperature using libre hardware monitor's library. Data is displayed directly to your Antec Flux Pro display on the side of the case. 

Requires Administrator privileges in order to fetch CPU and GPU data from libre hardware monitor's library.

## Notes
To build and export the project locally, I run this
`dotnet publish -c Release -p:SelfContained=false`
