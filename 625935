/*2. Write a java program to find the minimum value from the given
type of elements using a generic function.*/
import java.util.*;
public class min_val
{
    public static void main(String[] args) 
    {
        Integer num[]={1,6,5,9,10};
        java s=new java();
        s.min(num);                                                                                                       
    }
}
class java
{
    < T extends Comparable<T>> void min(T[]y)
    {
        T min;
        min=y[0];
        for(int i=1;i<y.length;i++ )
        {
            if(min.compareTo(y[i])>0)
            {
                min=y[i];
            }
        }
        System.out.println(min);
    }
}