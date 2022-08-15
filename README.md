# Vlr-scrapper-Npm-package

const valorant_Scrapper = require('valorant-esports-data-scrapper')


Get information about all valorant Pro teams

`valorant_Scrapper.GetAllProTeams().then((data)=>{
    console.log(data);
})`

Get information about a particular region valorant Pro Mtches and Events with live status

You have to pass some required arguments to the function 
Available regions - NA , EU , BR , AP , KR ,JP ,LA

`
valorant_Scrapper.GetRegionalEvents("NA").then((data)=>{ 
    console.log(data);
})
`

Get information about all valorant Pro Mtches and Events with live status

`valorant_Scrapper.GetGlobalEvents().then((data)=>{
    console.log(data);
})`

Get detailed info about all valorant Pro Playrs like - K.D,ACS,first Blood,kills,deaths,etc..

`valorant_Scrapper.GetDetailedPlayerData().then((data)=>{
    console.log(data);
})`
