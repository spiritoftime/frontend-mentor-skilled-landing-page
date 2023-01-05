# frontend-mentor-skilled-landing-page
Deployed site link: https://spiritoftime.github.io/frontend-mentor-skilled-landing-page/
what i learnt:
transitioning between gradients require a pseudo element. should use background not background-color
to hide overflow dont set it on body, but the relative container.
to make it look like grid items are aligned, we need to align the first and last element. we can overwrite gap set on the flex container by setting margin: auto 0 0 0 on the last child of the flex container.

responsive font size: we need to set the variable part to be of significance (eg. font-size:clamp(1rem, 1rem +0.1 vw, 3rem)). it will increment by very little, because eg. vw is 1000px, 0.1vw is a mere 1px! so it will only be 1rem + 1px. we need to set a sensible number, like perhaps 1vw

problems faced: was stuck for quite a long time on why my image was not filling up the picture div - turns out i set max-inline-width and not inline-size to 100%

the ids and xref to the ids have to be unique in svgs, else it will not work.

this was the longest challenge so far (and still not done!), spent literally 12h, of which 8h was the hero image. trying to position it like the figma was (and will still be when i get back to it tmr), literal hell
i should not have set overflow-x and overflow-y:hidden on the body tag, it should have been on desktop-div!!
