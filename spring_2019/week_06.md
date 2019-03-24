## Last Week's Accomplishments
	This week I fixed an issue where the verifying a student into a class would not put the student in the database. When I clicked the verify button I noticed the console logged an Internal server error which means that sometime went wrong in the backend. This issue was marked as a frontend bug, but is was not so I had to learn how the backend code worked. The sectionview.html files contains the verify student button. When this is button clicked, the code in the section controller is executed calling the section service which creates a call to the backend ("PUT") to store the student in the database. After inspecting all the code in these files everything looked correct. Apparently the version of mongodb was causing issues with the push function. I fixed this by using concat instead and I also changed the remove function to a splice because remove is not a javascript function.

## This Week's Plan

This I plan to work on more issues or create a verify all button.

## Anything Blocking?

N/A

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.
