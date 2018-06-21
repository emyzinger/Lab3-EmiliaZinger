**Try with a Linked List- Does this make any difference? (list)**

No, running the program with a Linked List does not make any difference. All the tests pass without any changes to their code.  

**list.remove(5); // what does this method do?**

This method removed the the value in a list at the 5th index, So it removes the third 77. 

**list.remove(Integer.valueOf(5)); //  what does this one do?**

This method removed the value 5 from the list. This value is at the 4th index. 

**// TODO also try with a LinkedList - does it make any difference? (Iterator)**

The LinkedList does not change how the tests run because they all pass without any changes. There is a small difference in the performance of them methods the testRemove(), and testNotEmpty() and slightly faster. 

**TODO what happens if you use list.remove(Integer.valueOf(77))?**

If you use that, it will only remove the first 77 and not the other 33. So the array that you will be left with will be 33, 44, 77, 55, 77, 66. 

**which of the two lists performs better as the size increases?**

For the access method the ArrayList works better, and scales much better as the size and reps scale up, as the size goes up the time to access something in an ArrayList does not change very much. In a LinkedList however, the time to access something goes up very quickly. The add remove method works better with a LinkedList, the speed stays pretty consistent and low as the size goes up. 

*google drive with the TestPerformance results
https://docs.google.com/spreadsheets/d/1JSRycRqrEkF_xmYbCLVkCKTw6q6JGl6ZUJTt4DRxozk/edit?usp=sharing



