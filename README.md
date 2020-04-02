# COVIDathon

## How-to add Ideas
- Fork
- Add your idea to the list below
- Use the (idea template)[IdeaTemplate.md] to add the relevant info
- Make a PR
  
## Logistics

- Kick-off April 4, 2020 2:30pm <details> <summary>link incoming</summary> ... https://zoom.us/j/618209372 ... </details>
- Form pairs, teams before kick-off or there will be a chance to get a team right after.



### Ideas
- [County Curves](CountyCurves.md)
- [Country Curves](CountryCurves.md)
- [Stay in, slow infection](StayInLivesSaved.md)
- [Uplifting stories](UpStories.md)
- [Perseverence texts](UpQuotes.md)
- [Skill match](SkillsMatch.md)
- [Tribute Site Generator](Tribute.md)
- [IoT data mapper](CreepyThermo.md)


### Ideas                                                   |ideas                                                | About the data                                              | API/Data                                                                                       | Tech estimate                                                                                                                                       | Originator                                                                             |
|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|

| Where is each country on possible curves                                                                | Country level data from day 1                               | https://covid19api.com/  https://www.xapix.io/covid-19-initiative                              | Get api data and use high charts, lots of css.                                                                                                      | https://helpwithcovid.com/projects/283-the-covid-tracking-project                      |
| Using the worst case curve, estimate how many lives saved by staying home on given day for my community |                                                             | https://covid19api.com/                                                                        | Get api data, little css, just compare. Include data for worst case curve                                                                           | https://helpwithcovid.com/projects/157-andrea-udani                                    |
| Sign up for texts or emails of uplifting/stories links                                                  | spreadsheet with summary and links of uplifting stories     | [Spreadsheet](https://docs.google.com/spreadsheets/d/19KBkEZ5XG1DJwgptBjWKfA7NnuBUyFlRpasp1R-wveA/edit#gid=0) | Scrape the sheet to save the links in a btter format, hash the url as an id, use twilio as mvp                                                      | [stories of human goodness summary](https://helpwithcovid.com/projects/271-stories-of-human-goodness-solidarity-resilience) |
| Sign up for texts or emails of mental health quotes                                                     | intial copy/paste dump. Stretch allow user generated quotes |                                                                                                | Same, minus the scraping                                                                                                                            | Leslie Pajuelo                                                                         |
| Matching skills/services                                                                                |                                                             |                                                                                                | Create profile, 1 page use oauth. Can be website not app as MVP                                                                                     | https://helpwithcovid.com/projects/307-matching-and-swiping-services                   |
| Make a tribute site for your loved one generator                                                        | Can use github pages                                        |                                                                                                | Create a form to get the base data, create a script that'll use the github api to crate a new org/repo. Generate markdown or html from field values | Leslie Pajuelo                                                                         |
| Map with infections over time/testing over time| there's this [Kinsha](https://healthweather.us/?regionId=49049&mode=Atypical) site  |using the network tab it's possible to get the info to use their API directly, explore if there's a time parameter.|Possibly might take a few of hours to be able to collect data from different endpoints in a way that can be useful| Leslie Pajuelo
