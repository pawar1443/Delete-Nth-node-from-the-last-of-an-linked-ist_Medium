# Read-Me
it took me 3 days to solve this problme , first we made a dummy node and placed it befor head , in case we have to delete the head node , and then we made two pointers , fast and slow , and we place the fast pointer at n+1 index , and then we start the iteration using while loop till the fast is at null , we increment both slow and fast till the fast reaches to null , and once it reaches to null , it means the node we awnt to delet is in the next node of slow , so we remove the node by replacing it with the next node , :- slow.next = slow.next.next .
thank you 
