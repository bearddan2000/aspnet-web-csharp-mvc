# aspnet-web-csharp-mvc

## Description
A POC running asp.net in linux.
This is using c# as the code behind.
All my asp.net repos use the MVC pattern

## Tech stack
- iproute2
- supervisor
- ca-certificates-mono
- fsharp
- mono-vbnc
- nuget
- referenceassemblies-pcl
- mono-fastcgi-server4
- nginx
- nginx-extras
- tar

## Docker stack
- mono:latest

## To run
`sudo ./install.sh -u`
Availble at http://localhost

## To stop
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`
