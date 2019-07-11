
     _____    ____      ____        _   __     __  _____   ____      __   _
    |  ___|  / ___|    |  _ \      / \  \ \   / / | ___⁄  |  __ \   |  \ | |
    | |_    | |        | |_) |    /   \  \ \ / /  | |_    | |__) |  |   \| |
    |  _|   | |        |  __ \   / /_\ \  \   /   | __|   |  __ \   | |\   |
    | |     | |___     | |__) | /  ___  \  | |    | |___  | |  \ \  | | \  |
    |_|      \____|    |_____/ /_/     \_\ |_|    |_____\ |_|   \_\ |_|  \_|

 ----------------------------------------------------------------- 

# FC Bayern

Stream One Project - User-Centric Frontend Development - Code Institute

This site will provide you with information about the German football club FC Bayern Munich, their trophy collection and their team, both players and coaches. Additionally, you can find their upcoming matches and a table of the German Bundesliga. The website is available in both English and German.

## Demo

Check it out with this Github [link](https://alnibo.github.io/milestone-project-1/index.html).

## UX
The goal for this website was to provide information for anyone who is interested in and wants to find out more about the football club FC Bayern Munich. Besides a landing page (homepage), there are four separate pages providing different information about the club. The about page gives a short description of the club and additionally states all titles that FC Bayern has collected over the years. The team site shows members of the whole team. They are categorised in goalkeepers, defenders, midfielders and forwards, as well as the head coach and his assistance coaches. The next page - fixtures - gives an overview of upcoming matches. The last page contains a table with the standings of all teams of the 2019/2020 German Bundesliga.

In order to present the infromation in a clear and easy way, a modern look with light colors and a simple desgin was chosen.

The home page tries to grab the viewers attention with a YouTube clip and invites her/him to read more about FC Bayern with a central button underneath.

To enhance user experience more buttons were added to the team page in order to quickly jump to the desired section. Another button was used on the bottom of the team page in order to jump back to the top. Also, on both fixtures and table pages buttons can be used to easily switch in between.  

As part of the design process wireframes were created to visualise and give an outline of the structures and layouts. They can be viewed [here](https://github.com/alnibo/milestone-project-1/tree/master/wireframes).

## Features

1. Responsive design using the Bootstrap Grid system, making sure the website is compatible on all screen sizes
2. Fixed navbar, which collapses when in mobile use, so as not to overgrowd the screen
3. Footer with Font awesome icons for social media links
4. Pictures of team members with hover effect

### Features Left to Implement
As the website now only provides a static table the next step would be to integrate a dynamic table that updates itself when new games have been played. On top of this, another good expansion would be the integration of standings in other leagues Bayern playes in. These include for example the Champions League and the German Cup.

## Technologies Used

1. HTML
2. CSS
3. Bootstrap (4.3.1)

## Testing

This website was manually tested from the perspective of a first time user navigating through the site verifying that all links and buttons correctly function.

As part of the testing procedure this website was tested with https://validator.w3.org/. A few errors and several warnings were displayed in the CSS file due to the boostrap link.

All links to social media sites where manually tested. By using `target="_blank"` it was made sure that these links will open in a new tab.

Ensuring its responsiveness this website was tested across different mobile devices. In a second step it was then tested across the most common internet browsers (Safari, Chrome, Internet Explorer, and Firefox), making sure it is compatible. For an overview, please see this excel file [here](https://github.com/alnibo/milestone-project-1/blob/master/Testing-resp-comp.pdf).

During the testing procedure it became clear that some media queries need to be created in order to maintain a good design acroos all screen sizes.

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. 

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/alnibo/milestone-project-1.git` into your terminal.

## Credits

### Content
All written content on the about page was retrieved from [Wikipedia](https://en.wikipedia.org/wiki/FC_Bayern_Munich).

Information regarding honours, upcoming fixtures and the bundesliga table was found on FC Bayern's [homepage](https://www.fcbayern.com).

### Media
The team picture and the player's profile pictures where taken from [FC Bayern](https://fcbayern.com/en/teams/first-team). All other pictures where taken from the online image libraries [Unsplash](https://unsplash.com) and [Pexels](https://www.pexels.com).

The background patter of the home page is retrieved from [here](www.subtlepatterns.com).

### Acknowledgements

The navbar was retrieved from the Bootstrap [documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/) and then altered and customized for this site.

Parts of the footer were obtained from the Code Institute resume project.
