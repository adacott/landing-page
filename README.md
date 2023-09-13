# odin-landing-page

https://adacott.github.io/odin-landing-page/ -- Link to see the webpage.

This is the first webpage I have ever created -- a landing webpage that illustrates various skills in CSS, HTML, and most-importantly, the rigorous use of flex-box to position elements on a webpage.

Below is a reflection on the popular methods I saw other creators use, and the various issues with my page that if I were to redo this entire project, I would change. My main issues tldr is that I used rigid sizing for each section, and defined the body to be 100vb, thus ensuring from the start my webpage would be squished and improperly porportioned. I also underutilized flex-grow,shrink,and basis.


======================= ISSUES WITH MY ODIN LANDING PAGE ================================
    -From what I saw, there were two major methods to organize the page. One was to define in the entire body the flex style,
        call them all flex columns, and then organize the page as a whole right there. This is what I did
    -The second method was to not define any global declarations other than margin and padding zero, and then the page was
        formatted through each individual section being laid out in the proper order, and then each section was defined as flex
        and set to proper orientation or direction

    Other than that my major issues are under-use of flex-wrap. Rigidity of containers - I often set the exact dimensions of 
        a container, which I should not have done. The other two example that I saw almost never set the width or height of a container
        manually. They would define the content inside of the flex container and let it resize itself, only adjusting the width to be 100%
        so it covered the whole page left to right.
        I also under-utilize different measurements for width, height, and padding and margin. Particularly vh and some of the non-common 
        ones.

        One of my major issues was that I set 100vh for the body at the very beginning. This is partially why my webpage is so squished.
        The BODY is the ENTIRE webpage. And I declared at the beginning that the body should only be an entire screen's size. This was a major
        mistake on the sizing of my webpage. I should not have delcared a size at the body, and instead sized any individual sections I wanted
        manually, and let the rest resize themselves automatically. I think I backed myself into this corner bc I saw the example page and   
        thought
        "Look, their webpage is only 1 viewport tall". I didnt think that they had a webpage that was much bigger that was simple captured 
        that 
        way using dev tools.

        I also still don't really understand how to use flex-grow, flex-shrink, flex-basis, so I need to review those things.

        Overall, my webpage is an accurate mimicry to the image provided to model off of. However, if I were to do it again, I would refine
        the appearance and sizing of each section of the page, removing any rigid declarations of size other than width or something like
        justify-alignment: stretch, letting the sections resize and redefine themselves based on the content.
