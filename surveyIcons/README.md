# Survey Icons
This is the repository for the survey icons for the Resilience iOS app. The file names of each icon correspond to the action value name in the Articles.json file, with no white spaces. These action value names also correspond to the survey identifiers in Bridge. All survey icons should be PNGs and highest quality version of the icon- resizing is done in the app.

**For Example:**

For the following two surveys, there are actionValue string values "Tick Bite Survey Sensitivity" and "Tick Bite Survey". The associated icons for these surveys should be named "TickBiteSurveySensitivity.png" and "TickBiteSurvey.png" respectively. Note, this only applies to actions with an  "actionType" of "survey".

```
...
				{
                    "title"             : "Are you sensitive to tick bites?",
                    "text"              : "When you get bitten by a tick do you experience any of the following: \n    •   pain from the bite \n    •   itch \n    •   a bump, similar to a mosquito bite \n    •   irritated skin around the bite ",
                    "buttonTitle"       : "Tell your story",
                    "actionType"        : "survey",
                    "actionValue"       : "Tick Bite Survey Sensitivity",
                    "showTopRule"       : 1
                },
                {
                    "title"             : "Are you resistant to tick bites? Do you regularly encounter ticks but rarely or never get bitten?",
                    "buttonTitle"       : "Tell your story",
                    "actionType"        : "survey",
                    "actionValue"       : "Tick Bite Survey",
                    "showTopRule"       : 1
                },
...
```