# nfldata
NFL data used in personal projects


## nflteams.js 
Exports a teams constant variable which is an array of objects with the following structure for all 32 nfl teams.  May eventually update to include more information like team colors.  If you have suggestions, feel free to leave those.

```js
{
  id: "PIT",
  mascot: "Steelers",
  fullname: "Pittsburgh Steelers",
  stadium: "Heinz Field",
  division: "AFC North",
  city: "Pittsburgh",
  state: "PA"
 }
```

## pit-schedule-2021.js
Exports a schedule constant variable for the 2021 season for the Pittsburgh Steelers.  Currently no plans to do other teams, but I do plan on updating this throughout the football season for the steelers.

```js
{
  preseason: [
    {
      id: "p1",
      week: 1,
      opponent: "DAL",
      home: false,
      date: new Date("August 8, 2021 19:00"),
      venue: "Tom Benson Stadium",
      homeScore: "",
      awayScore: "",
    }
  ],
  season: [
      {
      id: "w1",
      week: 1,
      opponent: "BUF",
      home: false,
      date: new Date("September 12, 2021 12:00"),
      venue: "Highmark Stadium",
      homeScore: "",
      awayScore: "",
    }
  ],
  postseason: []
}

```
