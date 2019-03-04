## Last Week's Accomplishments
	This week I began working on my first bug. The issue I was trying to fix is that a student user is allowed to verify their own submission when only instructors should have access to this feature. I began by figuring out where the validate button is created which was in the the submissionCard.html file. The button would only should if the upload was not verified yet, so I should just need to add a check to see if the user a is an instructor or not. There is a function to check whether the user is an instructor or not within the submissionView.controller file but it does not seem to work. I used console logs to check the value of the isInstructor variable after the function is executed and the variable evaluates to false when the user is an instructor or a student. I tried to figure out what was causing this issue but could not. Instead I documented both component files so the code was easier to understand.

## This Week's Plan

This week I hope to figure out the problem described above so I can fix the bug.

## Anything Blocking?

I do not understand why isInstructor is false for both a student user and an instructor user.

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.
