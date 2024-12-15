# Roblox Game Joiner

<small>Forked this README off returnrqt</small>

This tool allows you to launch Roblox with custom parameters directly from a website.

## Roblox Launch Parameters

### Game Parameters
- **`placeid`**: Launches a Roblox game using its place ID.
- **`gameInstanceId`**: Joins a server using its Job ID.
- **`linkCode`**: Joins a server using a private server invite code.
- **`launchData`**: Launches a Roblox game with [launch data](https://devforum.roblox.com/t/developer-deeplinking-beta/1904069).
- **`accessCode`**: Joins a server using an access code (disconnects the player).
- **`reservedServerAccessCode`**: Launches a game using a reserved server access code (disconnects the player).
- **`userID`**: Follows a specific user into a game.
- **`callId`**: Joins a game using a [call ID](https://devforum.roblox.com/t/the-future-of-immersive-communication-on-roblox/2701137).
- **`eventId`**: Adds the ID of an [experience event](https://create.roblox.com/docs/production/promotion/experience-events).
- **`id`**: ?
- **`browserTrackerId`**: ?

### Tracking Parameters
- **`joinAttemptOrigin`**: Indicates the [origin of the join](https://gist.github.com/returnrqt/c524cd4f93062ee90df8c5b2604133d4) attempt.
- **`launchtime`**: The local Unix timestamp at the time of launch.
- **`joinAttemptId`**: A unique UUID identifying the join attempt.

## Example URLs
- **Join Crossroads**:  
  `https://justap1ayer.github.io/RedblueExperience/index.html?placeid=1818`

- **Join Crossroads Server with Job ID**:  
  `https://justap1ayer.github.io/RedblueExperience/index.html?placeid=1818&gameInstanceId=6a62d499-b69c-4300-ac3f-ad2f395f4097`
  
- **Follow User ID 1**:  
  `https://justap1ayer.github.io/RedblueExperience/index.html?userID=1`
  
- **Join Roblox Call ID 123**:  
  `https://justap1ayer.github.io/RedblueExperience/index.html?callId=123`
