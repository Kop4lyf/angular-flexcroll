flexcrollAngularWrapper
=======================

This is a wrapper directive for flexcroll which is a popular custom scrollbar used in websites


Requirements:
============

angularjs
flexcroll


How to use:
===========

Just append this directive to an angular module.
Next thing, we need to add attribute 'flexcroll' to the element on which we need to apply custom scrollbar.
Also to note, the container should be one element whose height this directive takes to calculate the scrollbar.
Example: <div flexcroll style="height:100px;"><ul>lots of li</ul></div>


To Come:
=======

flexcroll with dynamic height which mimics max-height based default scrollbar.


To consider:
===========

Sometimes, angularjs does not know when the html is updated like it happens when we change it using Jquery.
For this, the directive does not know the change and hence does not update.
So, you need to update the flexcroll after you do such changes:
fleXenv.updateScrollBars();

