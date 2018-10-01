# Tesla Go
Tesla Go is a simple app that helps you start your day allowing you to intelligently schedule the tasks you do most frequently. It's goal isn't to allow you control everything about your car, but simply automate the slowest, or most repetative tasks.

## Example Scenarios
* Schedule your car to be preheated every weekday morning if the interior temperature is below 50F
* Schedule your car to finish charging before you plan to start your roadtrip
* Defrost the windows every weekday morning if frost is forecasted

    ### Sprint 0 
    * Architecture decisions 
    * Tesla API capability exploration

    ### Sprint 1
    * Create basic website and publish
    * Create secure auth; planned: OpenID (e.g. Login with Facebook)
    * Implement keyvault for Tesla OAuth token
    * Display text based car information

    ### Sprint 2
    * Implement backend to persist scenario by user
    * Implement schedule climate scenario with no customization as PoC

    ### Sprint 3
    * Build flexible UI to support creating scheduled "Tasks"
    * Display static climate scenario in flexible UI

    ### Sprint 4
    * Implement adding/removing scenarios with limited customization 

    ### Sprint 5
    * Example scenarios are supported with no 3rd party service integration
    * UI Polish

    ### Sprint 6 - v1.0.0-Alpha1
    * Release initial Alpha to limited testers
    * Collect blocking bugs

    ### Sprint 7 - v1.0.0-Beta1
    * Initial Beta

## Background
[Original Redit Post](https://www.reddit.com/r/teslamotors/comments/9joh3c/ill_build_your_unofficial_tesla_owner_app_or/)

*I want to make a free unofficial app or website to control my model 3. mainly just for fun, but I wanted to learn more about the tesla API.
Pitch me on what you want, and I'll build one of the top 3 upvoted options (if it's possible). Good ideas solve a specific, currently unsolved problem, instead of try to replace the Tesla app. My day job is a software engineer, so I could probably build most client/server web apps/services. If your idea is an app, I would probably build it in iOS first since that's what I use.*
