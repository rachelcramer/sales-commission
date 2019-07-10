public class  Salescommission{

	public static int main(String[] args) {
     int i;
     int sales = 0;
     double salary = 0;
     int count[] = {0, /* not used  */
                      0, /* not used  */ 
                      0, /* $200-$299 */
                      0, /* $300-$399 */
                      0, /* $400-$499 */
                      0, /* $500-$599 */
                      0, /* $600-$699 */
                      0, /* $700-$799 */
                    0, /* $800-$899 */
                      0, /* $900-$999 */
                     0}; /* $1000 and over */


     System.out.printf("Enter employee's sales (-1 to end): ");

     while (sales != -1)
     {
        salary = (200 + .09 * sales);

        if (salary >= 1000)
        {
             count[10]++;
        }
        else if (salary >= 200)
       {
           count[salary]++;
        }
        
        System.out.printf("Enter employee's sales (-1 to end): ");
      }
 
     System.out.printf("Employees in salary range:\n");
      for (i = 2; i < 10; i++)
      {
    	  System.out.printf("$%d00 - $%d99: %d\n", i, i, count[i]);
      } 
      System.out.printf("$1000 and over: %d\n", count[10]);
 
      return 0;
 
 }
}
