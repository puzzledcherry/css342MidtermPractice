## 2022 UWB CSS 342(A) Midterm Exam (100pt) (EXAMPLE)
### "single choices":
1. (2pts) Queues are first in first out data structures </br> </br>

3. (2pts) When overloadding, the method signature must differ from an existing method </br> </br>

4. (4pts) Since arrays are great at direct access but expensive to update (adding/removing elements), </br> 
          a linkedlist might serve better for the companies needs! Linkedlists, although slower at directly accessing </br>
          elements, are more efficent at adding and moving elements since their size is dynamic while arrays are static. </br> </br> 
          
5. (10pts) the output of the code is: -1 2 1 4 3 6 5 8 16 10 </br> </br> 
6. (5pts) the return type is (int*) but you're not returning a pointer. </br> </br> 

9. (5pts) #include "math.h </br> 
          class ComplexNumber { </br>
          T x; </br>
          T y; </br>
          public: </br>
          ComplexNumber(T x, T y) : x(x), y(y) {} </br>
          T distance() { return sqrt((x * x) + (y * y));} </br>
       }; </br> </br> 
       
10. (15pts) int fifth_to_last(int) {

        int num_of_elms = 0;
        ListNode* curr = head;
        while (curr->next != nullptr)
        {
            num_of_elms++;
        }

        ListNode* finder = head->next;
        if (num_of_elms >= 5)
        {
            int whereIsFifth = num_of_elms - 5;
            for (int i = 0; i < whereIsFifth; i++)
            {
                finder = finder->next;
            }
            return finder->val;
        }
        else
        {
            return -1;
        }

    } </br> </br>
    
11. (5pts) A unit test is a way we're not only about to test the function of our code, but also help plan what our </br>
    code should be able to do. There's still a point for us to both write the code and the unit tests since the unit </br>
    tests can serve as a way for us to define different functions of the program and how they should work. So by writing </br>
    out our unit tests before even implementing the solutions in code (this is TDD) we're able to have confidence that once our </br>
    code does pass the unit tests we've written, that they're funtioning as they should (since we created these requirements before </br>
    implementing any code at all!). </br> </br>
    
13. (10pts) 60 steps is printed instead of 10 because inside of the walk() function, the line steps += 50 is called. </br>
    this will add 50 to whatever number of steps you pass through the parameters. </br> </br> 
