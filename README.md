# Finterest
> Food Pinterest


It lets the users "pin" dish photos in the opentable app (desktop or mobile).
This idea includes three elements:

1. Pinning: Allow a user to pin dish photos.
2. Personal Board: Let the user view his/her own “board”.
3. Restaurant Linking: Dish-to-restaurant page navigation.
4. Shared Boards (Optional): Let other users view the user’s board.


## Benefits

Allow users to directly bookmark dishes (not just restaurants) so that he/she can easily make reservations based on his/her food preference.
From the OpenTable/restaurants perspective, this can potentially increase revenue by making the app more sticky.



## [1] Pinning

We can do this in an Android mobile app and/or via Opentable.com website.
In the photo page (accessible from the gallery widget), we display an icon/button to “pin” the photo. When a photo is pinned, its pid and the user’s gpid (possibly, along with rid) will be stored in DB. 
(Optional) We may add an option for the user to add a comment/annotation/label to the pinned photo.
 
## [2] Personal Board (aka “Cornucopia”)

We will need to add a page/screen to display the user’s board.
For now, a user can have only one board, and all photos will be displayed in a grid layout or in a scrollable list view. 
The actual display format is TBD. We can just display photos only, or we can display them with some comments or restaurant names, etc.
We can also display photos in a map view (based on the dish’s restaurant location).

## [3] Restaurant Linking

When the user clicks on a pinned photo, it leads to the existing restaurant page/screen.

## [4] Shared Boards (Optional)

We’ll need a page/screen to display “top board” list and/or to search for users/boards.
Then, when a board item is clicked from the list/search result page, the board page is opened.
 We may allow users to add comment, etc. on a given board.


