# Training-JS-4-Basic-data-types--Array
In javascript, Array is one of basic data types. Define an empty array can use var arr=new Array() or var arr=[]  Array has an attribute: length, if there is an array named arr, using arr.length to know how many elements are contained in the array.  Each element in the array has an index, use arr[index] to get the value of element.  index always start from 0, so the first element of array is arr[0], the last element of array is arr[arr.length-1].  If we want to add new elements to the array, you can use the array method: push(). It can add an element to the end of the array. Instead, if we want to remove the last element of the array, you can use the array method: pop(). for example:  var arr=[1,2,3];     //define an array arr contains elements 1 2 3 arr.push(4);         //add element 4 to arr console.log(arr)     //[1,2,3,4] arr.pop();           //remove the last element from arr console.log(arr)     //[1,2,3] Task I've written five function, each function receives a parameter: arr(an array), you should code something with arr.      1. getLength(arr)    should return length of arr     2. getFirst(arr)     should return the first element of arr     3. getLast(arr)      should return the last element of arr     4. pushElement(arr)  should push an element to arr, and then return arr     5. popElement(arr)   should pop an element from arr, and then return arr When you have finished the work, click "Run Tests" to see if your code is working properly.  In the end, click "Submit" to submit your code pass this kata.


== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project.  We have an
[open {bug ticket, mailing list thread, etc.} ](INSERT_LINK) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the
[Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) to understand
some of the reasons why GitHub is not a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
[check this resource](INSERT_LINK) for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
