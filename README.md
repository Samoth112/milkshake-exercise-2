TO VIEW ASSIGNMENT, NAVIAGATE TO https://milkshake-exercise-2-tc.netlify.app/

# Milkshake Studio Front-end Exercise

**The following excersice is meant for Milkshake Studio interview purposes.  It is not to be shared with outside parties.**

For this excercise you are tasked with recreating this article page with one interactive element, an editable title.

The page layout should be recreated using HTML/CSS to replicate the mockup as closely as possible. The mockup can be found in two formats, PNG and [Figma](https://www.figma.com/file/qSdVX11O2gPSxkvs9IqFP2/Article?node-id=0%3A84) in the excercise directory.  Assets for the page layout can be found in the excercise/assets directory. 

- [Design File](https://www.figma.com/file/qSdVX11O2gPSxkvs9IqFP2/Article?node-id=0%3A84)

The page layout uses a grid system (guides can be seen in the Figma file). At desktop size, this grid is made up of 12 fluid-width column with 13 fluid-width gutters. (If you're feeling ambitious, you're free to also re-interpret the grid system for smaller viewport sizes).

The non-standard fonts `PT Mono` and `Merriweather` that are used in this excersice can be found on Google Fonts. 

- [Merriweather](https://fonts.google.com/specimen/Merriweather) 
- [PT Mono](https://fonts.google.com/specimen/PT+Mono).

####Interactions
The primary interactive element of this excerise is the editable article header. Outside of this, everything on the page can be static - no hover states, no nothing. The article header follows a fairly standard 'edit in place' pattern. In 'edit mode', as the user types a title for the page, and a slug is automatically generated based off of that title. 

The UI interactions should be powered by Javascript using whatever patterns or frameworks you think are best suited. The title of the page should be persisted across page reloads in localstorage. 

It's not necessary to create any functionality that allows the user to create additional pages, or access other pages.


Specifications for the editable are listed below as user stories:

- In 'static', user sees page title.
- In 'static', user sees 'edit button'.
- User can click the edit button to switch to 'edit mode'.
- In 'edit mode', user sees 'cancel' and 'save button'.
- User can see existing page title in input field upon switching to 'edit mode'.
- User can modify title in 'edit mode'.
- User cannot submit title with 0 characters.
- User sees disabled (grayed out) save button if input contains 0 characters.
- User is presented with a generated slug upon modifying the value of the title input (on keyup).
- User can click 'save button' to persist title to localstorage and be returned to 'read mode'.
- User can click 'cancel button' to discard any modifications.


Please work from this directory, and share your implementation. Instructions should be added to this README file that allow us to take your code, run the application, and evaluate your work. Code should be annotated where sensible.

-- 

As a whole, this exercise aims to touch on a variety of skills and concepts involved in a lot of development at Milkshake Studio. Throughout the process, please feel free to reach out for help - while we're reluctant to give hints for implemenation, we're glad to clarify specifications. Please dedicate no more than 8 hours to the exercise - while 100% completion is great, it's not required - focus on the areas where you know you can excel and identify areas where you might need some help.
