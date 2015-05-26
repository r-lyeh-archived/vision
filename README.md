# vision
own vision of my ideal company, if i just had the money.

a few assorted premises and thoughts while coding for other (big) companies. 

# player dogmas
- candy the eye
- touch the heart
- master the brain

# game dogmas
- sorted by importance: sizeof( content ) > sizeof( mechanics ) > sizeof( code )
- ie, durability/diversity > uniqueness > dev effort.

# dev dogmas
- democracy { art, code, design }
- brainstorming: everybody in shared triangle edges 
- voting: rule 2-of-3 
- own your production

# dual organization
- designers: both mechanics and levels
- concepts: both textures and skinning
- coders: both tech and gameplay
- animators: both model and animation
- musicians: both music and sounds
- leads: both project and human resources
- producers: nope
- managers: nope
- HQ / staff / vip: nope

# inverse project flow
classic: staff requests features, workers do. loop forever. infinite development cycle. nonsense everywhere.
inverse: workers request features, staff approves or maybe not, devs do only if approved.

# project constrains
triangle of [detail/space,quality/performance,time/money].
pick a vertex for a given project.
everybody in the project have this is mind when creating { artwork, code, mechanics/levels, content }

# plus (when hiring)
- master of two: artsy coder, technical artist, game+level designer

# milestones & planning
1. do in-game-assets while( !art director && !hq approved ) ; preproduction
1. do gameplay-video-in-max while( !designers && !tech director && !hq approved ) ; preproduction
1. do convert-video-to-app while( !coders && !qa approved ) ; this is split in milestones
1. hint: UI is left as the last milestone

# mobile flow 4/4 rule: 4 steps/4 rewards
1. vibrant colors, nice graphics, lovely stupid chars (worms, minions, kerbals, rabids)
1. short game sessions [30s..2m]
1. long story/campaign [days...months]
1. tapping, one finger to rule them all
- rewarding: 0 stars (failed), 1 star (ok), 2 stars (great!), 3 stars (awesome!!)

# customer review flow
1. image: vivid colors, nice artwork
1. video: movement, feel, sound, additional details (history, easters, ..)
1. reviews: positive and negative details
1. store: price, availability, requeriments
1. (additionally pre: ads<->marketing<->networking: how did you know about the game?)

# gamebook

# presskit > landing page
- half page what/where/when/how much/who/why + media (img/vid)

# physical layout
- flat
- synergy
- freedom
- mixed environments
- mixed weekly reviews
- mixed game jams

# dual milestones
- `tech     |===|===|===|===|`
- `gameplay |===|===|===|===|===|==|`

# quad milestones
- `tech-cli     |===|===|===|===|`
- `tech-srv     |===|===|===|===|`
- `gameplay-cli |===|===|===|===|===|==|`
- `gameplay-srv |===|===|===|===|===|==|`

# tech
- deploy games purely as player+content.
- whole games as data driven.
- add features to the player, rather than to the game.

# monopoly dev
- hq is assigned a quantity of fake money for the whole project 
- every new feature gets evaluated in time: time x human resources = money
- if estimated money > remaining money then feature is not done (and HQ guy gets fired :o)
- else money is substracted from total amount and time is added to project schedules.

# studio dev tools
- clone a virtual box disk with the OS in it. keep it as os.vdi
- copy os.vdi tools.vdi; install all secondary apps (text/image editors, ...)
- copy tools.vdi dev.vdi; install all primary apps (SDKs, toolchains, ...)
- when minor upgrading, restart from tools.vdi and reinstall primary apps; save.
- when major upgrading, restart from os.vdi and reinstall primary and secondary apps; save.
- when deploying a new computer, copy dev.vdi disk from the network

# tools
- easy boot cd
- mozilla firefox (not ie, not chrome; because of "same origin policy" issue )
- toolchains and compilers
- python, ruby and nodejs
- sublime text 2
- tortoise git
- tortoise svn
