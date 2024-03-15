# [JSL02] Submission: Debug the DOM

# Brief

In the current code, users can add the same fitness goal multiple times, leading to duplicate entries in the goal list. To enhance the user experience and prevent duplicates, I had to  implement a check to ensure that the same goal cannot be added more than once. If a duplicate goal is detected, it should NOT be added to the list.

# Challenges

Figuring out how to correctly extract the node list and turn it into an array list to be able to access it with its content for comparison and ensuring that the would be no duplicates thereof.