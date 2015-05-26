# Vision
- a few assorted premises and thoughts while coding for other (big) companies. 
- this is just my own vision of an ideal company, if i just had the money.

1. Dogmas
  1. Studio
  1. Product
  1. Player
1. Studio
1. Design
1. Coding
1. Pre-production
1. Production
1. IT
1. Marketing

## Dogmas
- studio dogmas
  - democracy { art, code, design }
  - brainstorming: everybody can propose.
  - voting: requires 2-of-3 votes from different departments to proceed.
  - own your production
- product dogmas
  - sorted by importance: sizeof( content ) > sizeof( mechanics ) > sizeof( code )
  - ie, durability/diversity > uniqueness > dev effort.
- player dogmas
  - candy the eye (provice candy aesthetics)
  - touch the heart (provide valuable content)
  - master the brain (provide fun mechanics)

## Studio: inverse development flow
- classic: staff requests features, workers do. loop forever. infinite development cycle. nonsense everywhere.
- inverse: workers request features, staff approves or maybe not, devs do only if approved.

### Studio: dual organization roles
- designers: both mechanics and levels
- concepts: both textures and skinning
- coders: both tech and gameplay
- animators: both model and animation
- musicians: both music and sounds
- leads: both project and human resources
- producers: nope
- managers: nope
- HQ / staff / vip: nope

## Studio: constraints when authoring content
- triangle of [detail/space,quality/performance,time/money].
- pick a vertex for a given project.
- everybody in the project have this is mind when creating { artwork, code, mechanics/levels, content }

## Studio: physical layout
- flat
- synergy
- freedom
- mixed environments
- mixed weekly reviews
- mixed game jams

## Studio: human resources pluses (when hiring)
- master of two: artsy coder, technical artist, game+level designer

## Design: Five rules for mobile games (that you might have disregarded)
1. vibrant colors, nice graphics, lovely stupid chars (worms, minions, kerbals, rabids)
1. short game sessions [30s..2m]
1. long story/campaign [days...months]
1. tapping, one finger to rule them all
1. rewarding: 0 stars (failed), 1 star (ok), 2 stars (great!), 3 stars (awesome!!)

## Design: game pitch
see https://github.com/r-lyeh/pitch

## Design: game book
see https://github.com/r-lyeh/gamebook

## Coders: main tech mission
- deploy games purely as player+content.
- whole games as data driven.
- add features to the player, rather than to the game.

## Preproduction
1. do in-game-assets while( !art director && !hq approved ) ; preproduction
1. do gameplay-video-in-max while( !designers && !tech director && !hq approved ) ; preproduction
1. do convert-video-to-app while( !coders && !qa approved ) ; this is split in milestones
1. hint: UI is left as the last milestone

## Production: offline games == dual milestones
- `tech     |===|===|===|===|`
- `gameplay |===|===|===|===|===|==|`

## Production: online games == quad milestones
- `tech-cli     |===|===|===|===|`
- `tech-srv     |===|===|===|===|`
- `gameplay-cli |===|===|===|===|===|==|`
- `gameplay-srv |===|===|===|===|===|==|`

## Production: monopoly dev
- HQ is assigned a quantity of fake money (budget) for the whole project 
- every new feature gets evaluated in time: time x human resources = money
- if estimated money > remaining money then feature is not done,
- else money is substracted from total amount and time is added to project schedules.
- after shipping, remaining budget is added to the next project budget.

## ITs: studio dev tools
1. clone a virtual box disk with the OS in it. keep it as os.vdi
1. copy os.vdi tools.vdi, install all primary apps (SDKs, toolchains, ...), save tools.vdi
1. copy tools.vdi dev.vdi, install all secondary apps (text/image editors, ...), save dev.vdi
1. copy dev.vdi to a shared network folder

- when major upgrading, restart from 2)
- when minor upgrading, restart from 3)
- when deploying a new computer, copy dev.vdi disk from the network and profit.

## ITs: tools
- easy boot cd
- mozilla firefox (not ie, not chrome; because of "same origin policy" issue )
- toolchains and compilers
- python, ruby and nodejs
- sublime text 2
- tortoise git
- tortoise svn

## Marketing: customer review flow
1. image: vivid colors, nice artwork
1. video: movement, feel, sound, additional details (history, easters, ..)
1. reviews: positive and negative details
1. store: price, availability, requeriments
1. (additionally pre: ads<->marketing<->networking: how did you know about the game?)

## Marketing: presskit >> landing page
- half page of { what/where/when/how much/who/why } + media { img, vid } + contact + social network
