# thedom-and-events
TASK:
When the Take off button is clicked, the text The shuttle is on the ground changes to Houston, we have liftoff!. The Take off button has an id="liftoffButton" attribute.
button.addEventListener('click', event => {
   paragraph.innerHTML = 'Houston! We have liftoff!';
});

When the user's cursor goes over the Abort Mission button, the button's background turns red. The Abort Mission button has id="abortMission".

When the user's cursor leaves the Abort Mission button, the button's background returns to its original state (Hint: Setting the background color to the empty string, "", will force it to revert to the default browser styles.)
missionAbort.addEventListener("mouseout", function( event ) {
   event.target.style.backgroundColor = "";
});
When the user clicks the Abort Mission button, make a confirmation window that says Are you sure you want to abort the mission?. If the user confirms that they want to abort, the text changes to Mission aborted! Space shuttle returning home.
