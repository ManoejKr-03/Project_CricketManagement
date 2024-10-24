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


------------------------------------------prompt--------------------------------------------------------------------------
1. Landing Page:
A welcoming hero section with a banner showcasing local cricket matches.
Call-to-action buttons: "Sign Up," "Login," and "Explore Series."
Display a brief overview of the platform, including features like scheduling matches, player management, score tracking, and more.
Section to showcase upcoming matches or series with images and match details (e.g., team names, dates).
Footer with quick links to "About Us," "Contact," "Privacy Policy," and social media icons.
2. User Dashboard (for Players):
Display player profile picture, name, and basic information.
Navigation menu for:
Register for a team.
View series and upcoming matches.
Player statistics.
Match history.
A section to show the player’s registered teams, statistics, and any upcoming matches they are participating in.
3. Manager Dashboard:
Overview section with statistics on the number of series, teams, and matches managed.
Navigation options for:
Create a new series.
Create a team.
Schedule a match.
View and update match scores.
Manage player registrations.
View match results and team statistics.
Include a data table or card view to list all the series, teams, and matches managed.
4. Admin Dashboard:
Overview of total platform activity (users, matches, series, teams).
A section to manage:
User roles (view, update, or delete users).
All series and matches.
Platform settings.
Reports on match activity, user participation, and platform performance.
Include visual elements like charts or graphs to display statistics on user engagement and match activity.
5. Series Page:
List of all active and upcoming cricket series.
Each series card should display:
Series name.
Teams involved.
Start and end dates.
Series status (upcoming, ongoing, completed).
Buttons to view details and register a team.
A filter to search series by team or date.
6. Match Page:
Display detailed match information:
Match date, time, and location.
Teams involved with their logos.
Player lists for each team.
Real-time score updates (if the match is live).
Post-match statistics (if the match has ended).
Buttons to view full match statistics or download match reports.
7. Team Page:
List all the teams in the platform.
Each team card should display:
Team name, logo, and captain's name.
Number of players and matches played.
Button to view team details and player profiles.
Include a section to register or join a team.
8. Player Profile Page:
Display the player's profile picture, name, team name, and overall statistics (matches played, runs scored, wickets taken, etc.).
Section to show match history and individual performance in each match.
Buttons to edit profile and view player statistics.
9. Login/Sign Up Page:
Clean and simple form for users to log in or sign up.
Sign-up form with fields for:
Name, email, password, and role selection (Player/Manager/Admin).
Optional fields for team or player information (for players).
Buttons for social media login and forgot password.

