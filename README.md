MCVE of https://github.com/Choices-js/Choices/issues/1019.

To run:
npm i -g http-server
http-server -o .


Wait 5 seconds. Note that the dropdown displayed becomes a Choices() style dropdown.
Open the modal using 'Inline' link.
Note that the dropdown in the modal does not work as expected.

Refresh the page.
Immediately open the modal using 'Inline' link.
Wait 5 seconds.
Note that both the dropdown on the page, and the dropdown in the modal, function as expected.


