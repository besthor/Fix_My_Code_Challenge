## 4. Double linked list
#advanced
Please find here my implementation of a Double linked list in C: source code

Something is going wrong….

<p>$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint</p>
<p>$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------</p>
<p>$
It doesn’t look right…</p>

##Repo:

* GitHub repository: Fix_My_Code_Challenge
* Directory: 0x00-challenge
* File: 4-delete_dnodeint/
