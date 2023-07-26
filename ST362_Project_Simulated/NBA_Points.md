# Simulated NBA data

```R
exam_scores <- read.csv("https://raw.githubusercontent.com/DB7-CourseNotes/Case_Studies/main/ST362_Project_Simulated/NBA_Points.csv")
```

| Variable name | Type | Description |
|---|---|---|
| `points` | numeric | Total points scored (response) |
| `position` | categorical | [Description.](https://en.wikipedia.org/wiki/Basketball_positions) (Note the organization of the page) |
| `minutes_played` | numeric | Minutes |
| `player_assists` | numeric | Number of assists |
| `rebounds` | numeric | |
| `steals` | numeric | |
| `blocks` | numeric | |
| `turnovers` | numeric | |
| `field_goal_percentage` | numeric | Field goals are all shots except free throws |
| `free_throw_percentage` | numeric | |
| `effective_field_goal_percentage` | numeric | Field goals, weighted by 2-point shots or 3-point shots. |
