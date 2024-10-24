# Project_CricketManagement
1) Player Microservice's

//Navigation bar's
Player registration
Viewing teams
Viewing series
Viewing matches
Viewing/Updating player profile

// end point for player microservice's
POST /api/players/register - Register a new player.
GET /api/players/teams - Fetch all teams from the Team Microservice.
GET /api/players/series - Fetch all series from the Series Microservice.
GET /api/players/matches/:seriesId - Fetch matches for a series from the Match Microservice.
GET /api/players/profile/:id - Fetch a player's profile.
PUT /api/players/profile/:id - Update a player's profile



